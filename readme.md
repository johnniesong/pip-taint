### Do not install, just for test
# 简介
 pip包供应链污染示例,需要自行完成pip账号注册

# 使用说明
逻辑都在setup里面,打包后产生的文件在dist目录
打包和安装时都会执行内部逻辑,所以增加了一个本地文件检测,在打包时不执行逻辑  
打包压缩： python3 setup.py sdist  
上传包：twine upload dist/*

### 仅用于实验或测试
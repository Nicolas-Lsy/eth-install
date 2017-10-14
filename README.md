在Ubuntu/Debian 上安装 

# 先安装系统依赖以成功构建Python包，命令行中输入： 

$ apt-get install build-essential automake pkg-config libtool libffi-dev libgmp-dev

# 安装Pyethapp并通过PyPI依赖Python包：

($ mkvirtualenv pyethapp)
$ pip install pyethapp

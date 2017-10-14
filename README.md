在Ubuntu/Debian 上安装 

# 先安装系统依赖以成功构建Python包，命令行中输入： 

$ apt-get install build-essential automake pkg-config libtool libffi-dev libgmp-dev

# 安装Pyethapp并通过PyPI依赖Python包：

($ mkvirtualenv pyethapp)
$ pip install pyethapp


# 开始！

准备好捐款了吗？下面是如何建立地方发展pyethapp。

叉pyethapp回购在GitHub上。

克隆你的叉子：

$ git clone git @ GitHub网站：your_name_here / pyethapp.git

安装您的本地副本为virtualenv。假设你有virtualenvwrapper安装，这是你如何建立你的叉子地方发展：

mkvirtualenv美元pyethapp

$ cd pyethapp /

python setup.py美元发展

为地方发展创造一个分支：

$ git checkout -你修正或特征B的名字

现在您可以在本地进行更改了。

当您完成更改后，请检查您的变化通过flake8和测试，包括测试其他Python版本与弓形虫：

flake8美元pyethapp试验

python setup.py美元测试

托克斯美元

让flake8和TOX，只是pip安装它们到你的virtualenv。

提交你的修改并把你分到Github：

Git加。

您的详细描述您的更改。

$ git push起源的名字你的修正或特征

通过GitHub网站提交pull请求。

在Ubuntu/Debian 上安装 

# 先安装系统依赖以成功构建Python包，命令行中输入： 

$ apt-get install build-essential automake pkg-config libtool libffi-dev libgmp-dev

# 安装Pyethapp并通过PyPI依赖Python包：

($ mkvirtualenv pyethapp)
$ pip install pyethapp


# 开始！

准备好了吗？下面是如何建立地方发展pyethapp。

pyethapp在GitHub上。

克隆你的分支：

$ git clone git@github.com:your_name_here/pyethapp.git

安装您的本地副本为virtualenv。假设你有virtualenvwrapper安装，如何建立你的分叉：


    $ mkvirtualenv pyethapp
    $ cd pyethapp/
    $ python setup.py develop

创造一个分支：

 $ git checkout -b name-of-your-bugfix-or-feature

现在您可以在本地进行更改了。

当您完成更改后，请检查您的变化通过flake8和测试，包括测试其他Python版本：

    $ flake8 pyethapp tests 
    $ python setup.py test 
    $ tox

让flake8和TOX，只是pip安装它们到你的virtualenv。

提交你的修改并把你分到Github：

    $ git add .
    $ git commit -m "Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature 

通过GitHub网站提交pull请求。



#  操作 


    git clone https://github.com/ethereum/pyethapp
    cd pyethapp
    python setup.py install
    pyethapp (shows help)
    pyethapp run (starts the client)


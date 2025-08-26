$ which virtualenv
/usr/local/py-utils/bin/virtualenv
$ vihrtualenv --help

$ virtualenv ~/.venv
$ source ~/.venv/bin/activate

$ which python
/home/codespace/.venv/bin/python

$ vim ~/.bashrc 
# source virtualEnv
source ~/.venv/bin/activate

$ touch Makefile
$ touch requirements.txt
$ touch hello.py
$ touch test_hello.py

$ make
all         debug       debugthree  format      install     lint        one-test    test 
$ make install
$ pytest --help

$ ipython
In [1]:from hello import more_hello
In [2]:more_hello()
Out[2]: 'hi'
In [3]:assert "hi" = more_hello
In [4]:from hello import more_goodbye
In [5]:more_goodbye()
Out[5]: 'bye'
In [6]: exit()

$ make test
$ make lint
$ make format
$ pip freeze | less
$ make all

$ git config pull.ff only
$ git pull --tags origin main
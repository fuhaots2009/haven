
## 虚拟环境
创建 `virtual environment`, 可在其中安装有特定Python版本，以及许多其他包。这样可以满足不同应用需要使用不同的虚拟环境。[1](https://docs.python.org/zh-cn/3/tutorial/venv.html) [2](https://cewing.github.io/training.python_web/html/presentations/venv_intro.html)

- 创建虚拟环境
```shell
~$ python3 -m venv name-env
```
这将创建`name-env`目录。

- 激活
```shell
~$ source name-env/bin/activate
```
这样就进入了特定的虚拟环境。
```shell
~$ source name-env/bin/activate
(name-env) ~$ python
Python 3.5.2 (default, Nov 23 2017, 16:37:01) 
[GCC 5.4.0 20160609] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```
- 退出
```shell
~$ deactivate
```

##Pip管理包
https://pip.pypa.io/en/stable/user_guide/
https://docs.python.org/zh-cn/3/tutorial/venv.html

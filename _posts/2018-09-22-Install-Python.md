---
layout: post
title: "Install Python"
date: 2018-09-22
---

# Python 1 - Installation

## Python

[Python](https://www.python.org/about/) is a programming language that is popular nowadays for data science, such as machine learning. 

- When we download python from the website, it include its *distribution, i.e., Python Shell,* and a simple text *editor*. 
- We can execute a python program (`.py` files which can be coded using another editors like Atom, Notepad++, etc. ) through `Cmd` (on Win) or `Terminal` (on Mac)
- Check the python version in `Terminal`

```
    $ python3.7
    Python 3.7.0 (v3.7.0:1bf9cc5093, Jun 26 2018, 23:26:24) 
    [Clang 6.0 (clang-600.0.57)] on darwin
    Type "help", "copyright", "credits" or "license" for more information.
    >>> print("Hello World")
    Hello World
    >>> quit()
```

## Anaconda

[Anaconda](https://www.anaconda.com) is a Python and R *distribution*, which includes several IDEs.
After installing Anaconda, the default python version is now that provided by Anaconda, for example

```
    $ conda # check anaconda installation
    #
    $ python
    Python 3.6.5 |Anaconda, Inc.| (default, Apr 26 2018, 08:42:37) 
    [GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)] on darwin
    Type "help", "copyright", "credits" or "license" for more information.
    >>> 
```

We can see that the default python version now is Python 3.6.5 instead of Python 3.7.0 as above. 

**Install libs (libraries) of Python via Anaconda**

In order to check if a library is imported into Spyder or not, in the Spyder console, type:

```python
    import numpy
    # no output means the lib already improted
    import cvxopt
    Traceback (most recent call last):
    
      File "<ipython-input-2-01f8b2e0f668>", line 1, in <module>
        import cvxopt
    
    ModuleNotFoundError: No module named 'cvxopt'
```

Since the library cvxopt has not been installed, we now do it through Anaconda using `Terminal`

```
    $ conda install cvxopt
```
## Colaboratory lab of Google

Colaboratory is an online IDE for Python. The disadvantage of this platform is that it is hard to install external library such as cvxopt. 

## Atom

[Atom](https://atom.io) is a text editor, not an IDE.


## References
- [Python IDEs and Code Editors (Guide)](https://realpython.com/python-ides-code-editors-guide/)
- [Install Python and Anaconda on Windows (in Vietnamese)](https://chieupham.github.io/2017/02/18/Python-Windows/)

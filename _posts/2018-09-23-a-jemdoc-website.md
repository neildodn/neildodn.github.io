---
layout: post
title: "A Jemdoc Website"
date: 2018-09-23
---

*Jemdoc is stable with Python2.7 on both Windows and MacOS*

## On Windows
### Download

There are two main files we need to download, namely [jemdoc.py](http://jemdoc.jaboc.net/download.html) and [jemdoc.css](http://jemdoc.jaboc.net/download.html). Put these two files into the same folder.

### Create index.html

Create a file and named `index.txt` using, for example, Notepad or Notepad++, and save to the folder mentioned above. The `index.txt` file can be (or can be empty)


    == My Name
    This is my website.

Next, change the extension `.txt` to `.jemdoc`, and now we have a file name `index.jemdoc`. Then, on Command Prompt (Windows/cmd), check the version of python (and quit), and then direct to the folder to create `index.html`

```
    > cd <your directory>\Jemdoc
    > cd <your directory>\Jemdoc>jemdoc.py index.jemdoc
    # or we can use a shorten command
    > cd <your directory>\Jemdoc>jemdoc.py index
```

Now, in the folder, we have a new file named `index.html` which created by `jemdoc.py` . Follow the same process to create other html files. 

### Create a Menu

Our method is to download a menu file from [jemdoc source code](https://github.com/jem/jemdoc) and then edit it. 


## On MacOS

First, install [Python for Mac](https://www.python.org/downloads/).
Next, use the built-in Terminal to run Python, e.g., check it version

    $ python
    Python 2.7.10 (default, Oct  6 2017, 22:29:07) 
    [GCC 4.2.1 Compatible Apple LLVM 9.0.0 (clang-900.0.31)] on darwin
    Type "help", "copyright", "credits" or "license" for more information.
    >>> 

Next, go to the folder that stores Jemdoc source, and execute Jemdoc

```
    $ python2.7 jemdoc.py index.jemdoc
```

We can edit the `.jemdoc` files using a text editor, e.g., TextEdit. 

My sample website: [https://trinhudo.github.io/](https://trinhudo.github.io/)

## References
- [Jemdoc](http://jemdoc.jaboc.net)

---
layout: post
title: python学习
date: 2015-05-12
categories: blog
tags: [python]
description: 学习廖雪峰老师的教程笔记
---


##python简介

python简单优雅，运行速度没有C快，适合做网络应用、小工具

##python解释器

CPython IPython PyPy Jython IronPython

##开发秘诀

完全可以一边在文本编辑器里写代码，一边开一个交互式命令窗口，在写代码的过程中，把部分代码粘到命令行去验证，事半功倍

##数据类型和变量

注意：Python的整数没有大小限制，而某些语言的整数根据其存储长度是有大小限制的，例如Java对32位整数的范围限制在-2147483648-2147483647。
Python的浮点数也没有大小限制，但是超出一定范围就直接表示为inf（无限大）。

##字符串与编码

ord()函数获取字符的整数表示，chr()函数把编码转换为对应的字符
以Unicode表示的str通过encode()方法可以编码为指定的bytes
反过来，如果我们从网络或磁盘上读取了字节流，那么读到的数据就是bytes。要把bytes变为str，就需要用decode()方法
Python 3的字符串使用Unicode，直接支持多语言。
str和bytes互相转换时，需要指定编码。最常用的编码是UTF-8。Python当然也支持其他编码方式，比如把Unicode编码成GB2312：

##if
if <条件判断1>:
    <执行1>
elif <条件判断2>:
    <执行2>
elif <条件判断3>:
    <执行3>
else:
    <执行4>
	
##循环

循环是让计算机做重复任务的有效的方法，有些时候，如果代码写得有问题，会让程序陷入“死循环”，也就是永远循环下去。这时可以用Ctrl+C退出程序，或者强制结束Python进程。

##dict和set

使用key-value存储结构的dict在Python中非常有用，选择不可变对象作为key很重要，最常用的key是字符串。












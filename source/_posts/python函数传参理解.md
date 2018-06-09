---
title: python函数传参理解
date: 2018-06-01 21:03:09
tags:
---
python 中函数传参还是传引用？
例子：
```python
def func1(n):
    n = 5
    return n

o = 4
print(func1(o))  //输出5
print(o)   //输出4


def func(m):
    m[0] = 20
    m = [4,5,6]
    return m
l = [1,2,3]
print(func(l)) //输出[4,5,6]
print(l)       //输出[20,2,3]
	
```

[具体内容可查看该链接](https://www.cnblogs.com/zhijun/p/6559983.html)
---
layout: post
title: JavaScript 解构赋值
date: 2018-01-22 07:52:20 +0800
---

- 结构赋值变量提前生命使用报错问题
```
var x, y;
{x, y} = {x: 1, y: 2}; // 此时会报错，可以使用下面方式解决
({x, y} = {x: 1, y: 2})
```

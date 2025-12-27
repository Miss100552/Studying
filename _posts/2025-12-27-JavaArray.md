---
layout: post
title: "我的第四篇学习笔记：Java数组"
date: 2025-12-26
categories: study
---
## 数组
### 一、数组的创建
下面以整形数组为例：
```java
int[] nums;
nums=new int[10];
```
注意，与c语言不同，这里的数组创建的形式不一样  
不是int nums[]  
而是int[] nums
### 二、数组的初始化
有三种初始化方式
```java
//静态初始化
        int[] a={1,2,3,4};

        //动态初始化:包含默认初始化
        int[] b=new int[10];
```

@[TOC](aaaaaa)

# 概述
简单介绍Markdown
> Markdown 是一种轻量级标记语言，它允许人们使用易读写的纯文本格式编写文档，然后转换成格式丰富的HTML页面。--[[维基百科]](https://zh.wikipedia.org/wiki/Markdown)

# 标题
**例子**
# 标题1
## 标题2
### 标题3
#### 标题4
##### 标题5
###### 标题6


# 区块引用
> 这是一个区块引用
> 
> 这个同一个区块引用
> ### 这是一个标题
> 1. 这是第一个列表项
> 2. 这是第二个列表项
> 
> `System.out.println("Hello Markdown!");`
> 
> ```java
> System.out.println("Hello Markdown!");
> ```
> 

# 分隔线
hello
*** 
world
*****
markdownaaa
********
-----

# 强调
*使用一个`*`的强调*
**使用两个`*`的强调**

# 列表
## 无序列表
无序列表使用`*`号、`+`号或者`-`号作为列表标记，如下：
* 条目1
* 条目2
* 条目3

+ 条目1
+ 条目2
+ 条目3

- 条目1
- 条目2
- 条目3

## 有序列表
一个数字加一个英文句点`.`加至少一个空格加列表项内容，如下：
1. 条目1
2. 条目2
5. 条目3

## 多段列表
1. 学习Markdown
    学习起来很简单。
2. 使用Markdown
    可以使用在线编辑器练习。
    > 这个是多段列表里面包含一条引用。
    > 前面需要缩进4个空格。

# 链接
## 自动式链接
这个可点击的URL：
<http://www.csdn.net/>
<https://www.baidu.com>

## 文本式链接
[CSDN](http://www.csdn.net/)

# 代码
## 行内代码
`System.out.println('Hello Markdown');`

## 区域代码
```java
System.out.println('Hello Markdown');
return 0;
```

# 高亮
学习==Markdown==，需要==多多==练习。

# 图片
## 行内式图片
![演示图片](https://imgconvert.csdnimg.cn/aHR0cDovL2ltZy5ibG9nLmNzZG4ubmV0LzIwMTUwMzE1MTUwMjQ2Mzgy)

# 表格
**Markdown语法说明：**

> 1.  **|** 为分隔符。
> 2.  对齐方式
>     * 左对齐为 :---
>     * 右对齐为 ---:
>     * 居中对齐为 :---:
> 3.  第二行中的短线的数量可以根据美观来定

|姓名|年龄|性别|公司|
|:--|:--:|--:|:--:|
|bobo|30|man|dahua|
|naonao|4|man|无|

[TOC]

# markdown

这是markdown的学习笔记

标题部分省略啊

正文部分： 直接写文字，没有格式，直接两个空格 然后回车  

## 斜体粗体粗斜体

*斜体文本*
_斜体文本_
**粗体文本**
__粗体文本__
***粗斜体文本***
___粗斜体文本___

## 分隔线删除线下划线

***

* * *

*****

- - -

----------



~~删除线~~

<u>下划线</u>

## 脚注

脚注[^创建脚注]

[^创建脚注]:这是脚注啦





## markdown列表

### 普通列表

* 第一项
* 第二项
* 第三项

+ 第一项
+ 第二项
+ 第三项


- 第一项
- 第二项
- 第三项



### 带序号的列表

1. 第一项
2. 第二项
3. 第三项



### 列表嵌套

1. 第一项：
    - 第一项嵌套的第一个元素
    - 第一项嵌套的第二个元素
2. 第二项：
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素



### 列表和区块嵌套

> 最外层
> > 第一层嵌套
> >
> > > 第二层嵌套

#### 区块中使用列表

> 区块中使用列表
> 1. 第一项
> 2. 第二项
> + 第一项
> + 第二项
> + 第三项

#### 列表中使用区块

* 第一项
    > 菜鸟教程
    > 学的不仅是技术更是梦想
    
* 第二项



## markdown函数

```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```



## markdown链接

[这是一个b站账号](https://space.bilibili.com/34222806)

<https://space.bilibili.com/34222806>



## 高级链接

这个链接用 1 作为网址变量 [Google][1]
这个链接用 Shadowstar 作为网址变量 [Shadowstar][Shadowstar]
然后在文档的结尾为变量赋值（网址）

[1]: http://www.google.com/
[Shadowstar]: https://space.bilibili.com/34222806





## markdown图片

格式如下：

```makedown
![alt 属性文本](图片地址)

![alt 属性文本](图片地址 "可选标题")
```

```
还可以使用<img src="" width=50%>
```

## markdown 表格

| 左对齐 | 右对齐 | 居中对齐 |
| :----- | -----: | :------: |
| 单元格 | 单元格 |  单元格  |
| 单元格 | 单元格 |  单元格  |



## markdown公式

很nb但没必要

```makedown
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
${$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$
```

$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
${$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$



## markdown流程图

类似latex，网址链接如下：

<https://www.runoob.com/markdown/md-advance.html>
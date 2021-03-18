---
layout:     post
title:       我的GFM标准 MarkDown 文件学习之旅（一）
subtitle:   设计目标：半天入门，一月掌握，两年精通
date:       2021-03-18
author:     Nafish Narang
header-img: img/BT-3.jpg
catalog: true
tags:
    - 随笔杂谈

---



# 我的GFM标准 MarkDown 文件学习之旅（一）





## Hello大家好，我是纳鱼

**此篇文章记录于 2021年3月18日，也是本博客的第一篇内容。**



本博客建立自GitHub Pages服务，源码Fork自[klovien](https://github.com/klovien)/**[klovien.github.io](https://github.com/klovien/klovien.github.io)**，非常感谢一众大佬无私开放的精神。不然对代码一窍不通的我也不会有机会建立一个属于自己的博客了。



建立Nafish Club这个博客呢，主要是想网罗一众关系特好的哥们朋友，分享生活中的趣味，畅聊人生中的杂谈，分享己见，畅所欲言，以及推广我个人构想的系列作品世界观体系。



为方便个人练习以MarkDown文件为基础的网页编辑模式，在此记录个人学习笔记；





------





一级标题
=========



```text
一级标题
=========
```





二级标题
--------



```text
二级标题
--------
```





# 一级标题

## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题



```text
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```





> 引用



```text
> 引用内容
```



~~删除线~~

**粗体** 

*斜体*



```text
~~删除线~~
**粗体** 
*斜体*
```





##### 有序列表

1. Python
2. R
3. SQL



##### 无序列表

- Python
- R
- SQL



```text
##### 有序列表
1. Python
2. R
3. SQL

##### 无序列表
- Python
- R
- SQL
```



```text
##### 嵌套列表
- Python
    - 数据库编程
        - Python 的 DB-API
            - 模块属性
            - Connection 对象
            - Cursor 对象

##### 有序列表和无序列表互相嵌套
1. Python 文本处理
    - 逗号分割值（CSV）
    - JSON
    - 可标记扩展语言
        1. XML 简介
        2. Python 和 XML
        3. XML 实战
```





##### 下面是分隔线

---

##### 上面是分隔线





```text
##### 下面是分隔线
---
##### 上面是分隔线
```





自动链接：https://nafish-narang.github.io

进入 [纳鱼之家](https://nafish-narang.github.io)

进入 [Markdown官网](https://daringfireball.net/projects/markdown/)

```text
进入 [Markdown官网](https://daringfireball.net/projects/markdown/)
```





图片插入：BT-3.jpg

Typora支持直接拖拽……



![图片替代文字](K:\[同步]\GitHub\[素材]\BT-3.jpg)



~~~text
```
![图片替代文字](图片地址)
```
~~~

```text
![Markdown](https://www.fullstackpython.com/img/logos/markdown.png)
```





- [ ] 待办事项1
- [ ] 待办事项2
- [x] 待办事项3
- [ ] 待办事项4



```text
- [ ] 待办事项1
- [ ] 待办事项2
- [x] 待办事项3
- [ ] 待办事项4
```





表格：




| 姓名 | 年龄 | 性别 |
| ---- | ---- | ---- |
| 小明 | 18   | 男   |
| 小刚 | 29   | 女   |
| 李三 | 20   | 男   |



```text
| 姓名 | 年龄 | 性别 |
| ---- | ---- | ---- |
| 小明 | 18   | 男   |
| 小刚 | 29   | 女   |
| 李三 | 20   | 男   |
```





| 表头1 | 表头2 | 表头3 |
| ----- | ----- | ----- |
| 内容1 | 内容2 | 内容3 |
| 内容1 | 内容2 | 内容3 |



1. 单元格使用 `|` 来分隔，为了阅读更清晰，建议最前和最后都使用 `|`
2. 单元格和 `|` 之间的空格会被移除
3. 表头与其他行使用 `---` 来分隔
4. 表格对齐格式如下

- 左对齐（默认）： `:----`
- 右对齐： `----:`
- 居中对齐： `:----:`



```text
| 表头1 | 表头2 | 表头3 |
| ---- | ---- | ---- |
| 内容1 | 内容2 | 内容3 |
| 内容1 | 内容2 | 内容3 |
```





代码表格：



```三个反引号标记代码块
function sum(a,b) {
	return a + b;
}

```



```java 

public class HelloWorld {
	public static void main(String[] args){
		System.out.println("Hello,World");
	}
}

```





Emoji：



:grinning:
:heart_eyes:
:speech_balloon:
:peach:





超链接：



GitHub官网：<https://github.com/

>

```text
GitHub官网：<https://github.com/>
```





```text
在日常工作中，我们经常使用的网址有 [Google]、[Github] 和 [Stack Overflow]
[Google]: https://www.google.com/
[GitHub]: https://github.com/
[Stack Overflow]: https://stackoverflow.com/?utm_source=rss&utm_medium=rss
```


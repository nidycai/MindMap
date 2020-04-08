# Markdown笔记

## 1.设计理念

>Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like #or *.

## 2.标题

\#数量表示标题大小，1-6级标题

## 3.字体

* **加粗**
要加粗的字体用两个*包裹

* **斜体**
要倾斜的字体用一个*包裹

* **斜体加粗**
三个*包裹

* **删除线**
两个~~包裹
~~删除线~~

* **下划线**
原生markdown不支持，用html格式<\u>
<u>下划线</u>

## 4.引用

引用文字前加>，可以嵌套
>这是引用的内容
>>可以嵌套
我不知道

## 5.分割线

***
三个或以上的- *均可
***

## 6.超链接

[链接名](超链接地址 "超链接title")
[dogedoge](http://www.baidu.com "多吉搜索")

## 7.图片

语法类似超链接，前加!
![dogedoge](https://www.dogedoge.com/assets/new_logo.min.png "多吉搜索")

## 8. 列表

### 无序列表

语法：
-+*都可以，后接空格

* 列表1

* 列表2

* 列表3

### 有序列表

语法：
数字+点，后接空格

1. 列表内容1
2. 列表内容2
3. 列表内容3

### 列表嵌套

上一级和下一级间敲两个空格

* 一级无序内容

  * 二级无序内容

  * 二级无序内容

* 一级无序内容

上一级和下一级之间敲三个空格

1. 一级有序列表

   1. 二级有序列表
   2. 二级有序列表

2. 一级有序列表

## 9.表格

语法
| 表头 | 表头 | 表头 |
|------|:----:|-----:|
| 内容 | 内容 | 内容 |

| 姓名 | 技能 | 排行 |
|------|:----:|-----:|
| 刘备 |  哭  | 大哥 |
| 关羽 |  打  | 二哥 |
| 张飞 |  骂  | 三弟 |

## 10.代码

单行代码 一个反引号包裹`代码内容`

代码块：三个反引号，后加语言

```python
if __name__ == "__main__":
    print("Yes")
```

## 11.流程图

```flow
st=>start: Start:>https://www.zybuluo.com
io=>inputoutput: verification
op=>operation: Your Operation
cond=>condition: Yes or No?
sub=>subroutine: Your Subroutine
e=>end

st->io->op->cond
cond(yes)->e
cond(no)->sub->io
```

### 更多语法参考[语法参考](http://adrai.github.io/flowchart.js)

## 12.目录

[toc]

## 13.标签分类

Tags: 数学 英语 Markdown

## 14.注脚

[^keyword]表示注脚
注脚[^footnote]

[^footnote]: http://www.baidu.com

## 15.LaTeX公式

\$表示行内公式
$E=mc^2$

\$\$表示整行公式
$$\sum_{i=1}^n a_i=0$$
$$f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2 $$
$$\sum^{j-1}_{k=0}{\widehat{\gamma}_{kj} z_k}$$

访问[MathJax](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)参考更多使用方法。

## 16.序列图

```seq
Alice->Bob: Hello Bob, how are you?
Bob->Alice: I am good thanks!
```

## 17.甘特图

```gantt
    title 项目开发流程
    section 项目确定
        需求分析       :a1, 2016-06-22, 3d
        可行性报告     :after a1, 5d
        概念验证       : 5d
    section 项目实施
        概要设计      :2016-07-05  , 5d
        详细设计      :2016-07-08, 10d
        编码          :2016-07-15, 10d
        测试          :2016-07-22, 5d
    section 发布验收
        发布: 2d
        验收: 3d
```


## 18.emoji

| |a|b|c|d|e|f|
|--|--|--|--|--|--|--|
|1|:punch:|:notebook:|:e-mail:|:smile:|:movie_camera:|:camera:|
|2|:fa-car:|:telephone_receiver:|:phone:|:heart:|:alarm_clock:|:loop:|
|3|:+1:|:books:|:email:|:-1:|:bulb:|:hammer:|
|4|:rocket:|:book:|:envelope:|:sunny:|:mag_right:|:chart_with_upwards_trend:|
|5|:cloud:|:bar_chart:|:wind_chime:|:hibiscus:|:paperclip:|:ghost:|
|6|:bug:|:date:|:balloon:|:beers:|:guitar:|:headphones:|
|7|:rice:|:guitar:|:mortar_board:|:house:|:mount_fuji:|:office:|
|8|:rocket:|:school:|:cupid:|:notes:|:shit:|:feet:|
|9|:speech_balloon:|

## 19.ToDo

* [ ] 需要什么
* [x] 已完成

## 20.Html标签

嵌套html标签

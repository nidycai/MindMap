# 一、概述

诞生自<u>Daring Fireball</u>之手。

语法标准因解析器和编辑器而异。

Typora使用Github Flavored Markdown标准。

# 二、块元件

## 1.段落和行间距

段落间以一行以上的空格作为分隔

## 2.标题

1-6#创建标题

## 3.引用

>这是一个由两个段落组成的引用块
>
>这是第二个段落

>这是另一个段落

### 4.普通清单

* 清单事项1
* 清单事项2

## 无序列表

* 红色
* 绿色

## 有序列表

1. 红色
2. 蓝色

## 5.任务清单

- [ ] fdsa
- [x] fdsaf

## 6.代码块

```javascript
function test(){
    console.log("notice the blank line before this function?");
}
```

## 7.数学公式

$$
x = y + 1
$$

$ x = y + 1 $

$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$

## 8.表格

| First Header   | Second Header |
|:---------------|--------------:|
| *content cell* |  content cell |

## 9.脚注

你可以创建一个脚注
脚注示范[^这是一个脚注]

[^这是一个脚注]:哈哈哈哈

vim-surround 操作
"test" 
ds 删除"
cs "'
ys\<motion>\<desired char>



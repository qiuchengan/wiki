# HOW
## 一.待办
**todo**
- [ ] 1
- [x] 2

## 二.表格
时间|任务|结果
-|-|-
0516|eat|done

## 三.流程图
```
graph LR
A[发起]-->B((审批))
B-->|Y|C{完成}
B-->|N|D{打回}
```
## 四.甘特图
```
gantt
dateformat YYYY-MM-DD
title 项目进度表
section 准备阶段
问题收集:done,des1,2016-05-01,3d 
问题分析:done,des2,2016-05-02,3d
问题结果:done,des3,2016-05-05,1d
section 实施阶段
阶段1:active,des1,2016-05-06,5d
阶段2:active,des2,2016-05-11,5d
```
***
# 基本
1.有序列表
+ 无序列表a
- 无序列表b
* 无序列表c
> *引用*

[超链接显示文本](https://www.baidu.com)

![图片说明,可缺省](http://note.youdao.com/favicon.ico)

**粗体**  *斜体* ~~删除线~~ ++下划线++ ==标记==

`$y=x^2$`

```math
e=mc^2
```
    $var='aa'
***
==**总结:**==

==goal:==

**待办清单
表格,流程图,甘特图
code(``或tab/4个空格)**

==how:==

标题:六级标题,#开头,逐级缩小

列表:无序/有序,-开头,1.开头

引用:>

字体:粗体斜体下划线删除线标记

超链接:[显示文本]'(链接地址)' ![]'(图片链接地址)'

分隔线:三个星号

表格: -|-|- 表示

流程图:以```开头并结尾,另起一行graph xx(TB,LR,BT,RL)
[],(()),{};---,-->,-->|插入文本|

甘特图:以```开头并结尾,另起一行gantt dateformat YYYY-MM-DD title section 任务名称:done/active,行数,开始时间,结束时间/所需天数


---
layout:     post
title:      input标签的autocomplete属性
subtitle:   input标签的autocomplete属性用来关闭表单的自动提示填充
date:       2020-5-09
author:     Mr.Gao
header-img: img/post-bg-keybord.jpg
catalog: false
tags:
    - html/css/js学习
---


## 禁止表单提示输入--autocomplete属性
### 在我们进行web程序开发中，经常会遇到这样的问题，就是制作了一个表单，当用户点击输入框进行输入时，会显示以前的历史记录，这对之前数据的输入安全具有很大的隐患，解决方案有两个，一是通过设置浏览器的取消表单自动填充功能，二是在开发中在input标签中使用autocomplete="off"，关闭表单的自动输入。  
代码如下:  
```HTML
<input type="text" autocomplete="off">            //关闭输入框的自动提示填充功能
<input type="text">                               //默认输入框为自动提示填充
```

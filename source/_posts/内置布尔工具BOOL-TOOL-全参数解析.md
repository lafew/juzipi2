---
title: 内置布尔工具BOOL TOOL 全参数解析
tags: blender
description: blender学习记录
abbrlink: 4f74
date: 2021-11-22 20:26:16
---

# BOOL TOOL 工具

![image-20211122203355574](https://cdn.jsdelivr.net/gh/lafew/picgo_xyz@main//img/image-20211122203355574.png)

对是以上两个选项进行勾选

此工具分为自动布尔和brush布尔，自动布尔为运行后直接进行布尔然后应用修改器

而brush布尔是为所选物体添加修改器

![image-20211122205445517](https://cdn.jsdelivr.net/gh/lafew/picgo_xyz@main//img/image-20211122205445517.png)

## 快捷键

***brush布尔***

差集 ctrl+小键盘减号

并集 ctrl+小键盘加号

交集 ctrl+小键盘乘号

切片 ctrl+小键盘除号

***自动布尔***

多按一个shift，其余与上述快捷键一致

***菜单调出快捷键***

ctrl+shift+b

---

# 集合绘制布尔技巧与快速新建工具全解

先对物体添加布尔修改器，运算类型改成集合，然后在大纲视图新建一个集合，将该集合设置成布尔用的集合，blender默认新建物体的时候，以当前所在集合或集合内的物体主进行新建

这样就可以设置一个布尔集合

但是无法使该集合为线框显示

此时可以新拖出来一个窗口，按N键选择视图将本地集合下的布尔集合进行隐藏，新拖出来的窗口作为布尔运算的一个预览窗口

![image-20211122210931930](https://cdn.jsdelivr.net/gh/lafew/picgo_xyz@main//img/image-20211122210931930.png)

## 快速新建工具全解

按住ctrl会产生一个该工具自带的吸附，会自动吸附到网格物体上

![image-20211122211404041](https://cdn.jsdelivr.net/gh/lafew/picgo_xyz@main//img/image-20211122211404041.png)

若要使用全局吸附，则将吸附至几何数据改为默认

直接点击鼠标左键为以该点作为角进行创建，按住alt则是以鼠标左键点击的点为中心向外扩散进行创建

等比创建需要再按下shift，等比创建完平面后再按shift则会创建一个正方体

---

关于视角朝向，开启坐标系选择表曲面，基础设置中的平面轴改为自动定轴

![image-20211122212255594](https://cdn.jsdelivr.net/gh/lafew/picgo_xyz@main//img/image-20211122212255594.png)

***深度***

游标平面

以游标所在的平面进行创建

---
layout: post
title: 网易前端位专业 - 页面制作 - PhotoShop切图
categories: PhotoShops
description: 网易前端位专业 - 页面制作 - PhotoShop切图。
keywords: 页面制作,PhotoShop,切图
---

### 为什么要切图？
主要是给网页提供素材  

> 注意： .. 两个点号用法 ， sprite 用法 

- HTML:img

```
	<img src="images/avatar.jpg" alt="头像">
```
- CSS：backgroud

```
	.icon{
		background-image: url(../images/sprite.png);
		background-position: 0 0;
	}	
```

### PS工具初步   
一,介绍  
1.首选项 设置像素模式。  
2.主要面板: 工具 选项 信息 图层 历史记录  
3.保存工作区（等于是自定义）  
4.常用工具: 移动,矩形,魔棒,裁剪,缩放,取色器等  
5.常用快捷键:  
- 缩放: alt+鼠标  
- ✋ : space +鼠标即可  
6.标尺,参考线: 你得新建参考线
> 注意:   
> 移动工具(自动选择要勾上,我们要选图层而不是组)  
> 魔棒工具(容差越小,选取范围越小) 

### 获取信息
1.尺寸信息 利用矩形选框工具  
2.颜色信息 利用拾色器
> 注意:  
> font-size(文字的高度),line-height(上一行底部到下一行的底部)  
> 纯色(注意是否渐变)

3.拉取图标  
可拉伸: 自由变换 CTRL + T  拉伸后enter或双击即可

不可拉伸 背景有纹理等不可拉伸,只能移动覆盖

使用移动工具 + alt 覆盖 不需要自由变换,其实本质是复制覆盖.

直接每次同时按住 shift 和alt 则可以水平移动


### 切图
1.修饰性图片 一般用background属性引入 保存为PNG8 PNG24(IE6不支持半透明)

- 图标 logo
- 特殊效果的按钮,文字
- 非纯色背景灯  

> 注意: PNG8默认是索引颜色,要改为RGB8颜色(图像,模式下更改)

2.内容性图片 一般用img标签引入  保存为jpg

- Banner 广告图片
- 文章中的配图等

3.切片工具 批量切图(利用参考线)  
4.图片压缩:

- 无损压缩(Minimage neteaseWD,github上)
- 有损压缩(TinyPNG)










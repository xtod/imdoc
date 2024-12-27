---
title: ImageMagick命令行工具
slug: ImageMagick_command-line-tools
date: 2024-12-26
weight: 2
---
# ImageMagick命令行工具

ImageMagick 是可用于修改和操作图像的命令行工具的集合。以下是每个命令行工具的简短描述。单击程序名称可获取有关程序使用情况的详细信息以及更改程序行为方式的命令行选项列表。如果您刚刚熟悉 ImageMagick，请从 magick 程序开始。请务必仔细阅读 Anthony Thyssen 的教程，了解如何使用 ImageMagick 实用程序从命令行创建、编辑、编写或转换图像。
|命令|说明|
|-|-|
|[magick](/docs/guide/ImageMagick_command-line-tools/#magick)|在图像格式之间进行转换以及调整图像大小、模糊、裁剪、去斑点、抖动、绘制、翻转、加入、重新采样等等。|
|magick-script|使用此脚本语言解释器在图像格式之间进行转换以及调整图像大小、模糊、裁剪、去斑、抖动、绘制、翻转、加入、重新采样等等。|

还支持与 ImageMagick 版本 6 兼容的子命令：
|命令|说明|
|-|-|
|magick animate|在任何 X server上为图像序列制作动画。|
|magick compare|以数学和视觉方式注释图像与其重建之间的差异。|
|magick composite|将一个图像重叠在另一个图像上。|
|magick conjure|解释和执行以 Magick 脚本语言 （MSL） 编写的脚本。|
|magick display|在任何 X server上显示图像或图像序列。|
|magick identify|描述一个或多个图像文件的格式和特征。|
|magick import|
在 X server上保存任何可见窗口，并将其输出为图像文件。您可以捕获单个窗口、整个屏幕或屏幕的任何矩形部分。|
|magick mogrify|调整图像大小、模糊、裁剪、去斑点、抖动、绘制、翻转、加入、重新采样等等。Mogrify 会覆盖原始图像文件，而 magick 会写入其他图像文件。|
|magick montage|通过组合多个单独的图像来创建合成图像。图像平铺在复合图像上，可选择使用边框、框架、图像名称等进行装饰。|
|magick stream|一个轻量级工具，用于将图像的一个或多个像素组件或图像的一部分流式传输到您选择的存储格式。当像素组件从输入图像中读取像素组件时，它一次一行写入像素组件，从而在处理大型图像或需要原始像素组件时需要流。|

## magick

使用 `magick` 命令在图像格式之间进行转换以及调整图像大小、模糊、裁剪、去斑点、抖动、绘制、翻转、加入、重新采样等等。有关如何构建 magick 命令的建议，请参见 命令行处理 ，或者查看下面的命令用法示例。

我们在此处列出了 `magick` 命令的几个示例，以说明其有用性和易用性。首先，让我们将 JPEG 格式的图像转换为 PNG：

```sh
magick rose.jpg rose.png 
```

接下来，我们在将图像写入 PNG 格式之前减小图像大小：

```sh
magick rose.jpg -resize 50% rose.png 
```

<ul>
  <img src="/image/rose.jpg" width="70" height="46" alt="rose" />
  <img style="margin-top:13px; margin-bottom:13px;" src="/image/right.gif" width="20" height="20" alt="==>" />
  <img style="margin-top:11px; margin-bottom:12px;" src="/image/rose.png" width="35" height="23" alt="rose" />
</ul>
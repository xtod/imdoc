---
date: 2017-10-19T15:26:15Z
title: 首页
description: "ImageMagick中文使用手册大全"
images:
- images/wizard.png
---

# ImageMagick中文手册

ImageMagick® 是一个免费的开源软件套件，用于编辑和处理数字图像。它可用于创建、编辑、合成或转换位图图像，并支持多种文件格式，包括 JPEG、PNG、GIF、TIFF 和 Ultra HDR等。

ImageMagick 广泛应用于 Web 开发、平面设计和视频编辑等行业，以及科学研究、医学成像和天文学。其多功能和可定制的特性，以及强大的图像处理功能，使其成为各种图像相关任务的热门选择。

ImageMagick 包括一个用于执行复杂图像处理任务的命令行界面，以及用于将其功能集成到软件应用程序的 API。它是用 C 语言编写的，可以在各种操作系统上使用，包括 Linux、Windows 和 macOS。

ImageMagick 的主网站可以在 https://imagemagick.org 上找到。可用的最新版本是 ImageMagick 7.1.1-43。该软件的源代码可以通过存储库访问。此外，我们还维护了 ImageMagick 的旧版本，即版本 6。

## ImageMagick特性和功能
ImageMagick 的主要功能之一是它对脚本和自动化的支持。这允许用户创建可以自动运行的复杂图像处理管道，而无需手动干预。这对于需要处理大量图像的任务或需要定期执行的任务特别有用。

除了核心图像处理功能外，ImageMagick 还包括许多其他功能，例如对动画、色彩管理和图像渲染的支持。这些功能使其成为适用于各种图像相关任务的多功能工具，包括图形设计、科学可视化和数字艺术。

总体而言，ImageMagick 是一款功能强大且用途广泛的软件套件，用于显示、转换和编辑图像文件。它对脚本和自动化的支持以及其他功能使其成为各种图像相关任务的宝贵工具。

以下是 ImageMagick 可以为您做什么的一些示例：

|||
|-|-|
|Animation	|create a GIF animation sequence from a group of images.|
|Bilateral blur|	non-linear, edge-preserving, and noise-reducing smoothing filter.|
|Color management|	accurate color management with color profiles or in lieu of-- built-in gamma compression or expansion as demanded by the colorspace.|
|Color thresholding|	force all pixels in the color range to white otherwise black.|
|Command-line processing|	utilize ImageMagick from the command-line.|
|Complex text layout	|bidirectional text support and shaping.|
|Composite	|overlap one image over another.|
|Connected component labeling|	uniquely label connected regions in an image.|
|Convex hull	|smallest area convex polygon containing the image foreground objects. In addition, the minimum bounding box and unrotate angle are also generated.|
|Decorate	|add a border or frame to an image.|
|Delineate image features|	Canny edge detection, Hough lines.|
|Discrete Fourier transform	|implements the forward and inverse DFT.|
|Distributed pixel cache|	offload intermediate pixel storage to one or more remote servers.|
|Draw|	add shapes or text to an image.|
|Encipher or decipher an image|	convert ordinary images into unintelligible gibberish and back again.|
|Format conversion	|convert an image from one format to another (e.g. PNG to JPEG).|
|Generalized pixel distortion|	correct for, or induce image distortions including perspective.|
|Heterogeneous distributed processing|	certain algorithms are OpenCL-enabled to take advantage of speed-ups offered by executing in concert across heterogeneous platforms consisting of CPUs, GPUs, and other processors.|
|High dynamic-range images	|accurately represent the wide range of intensity levels found in real scenes ranging from the brightest direct sunlight to the deepest darkest shadows.|
|Histogram equalization	|use adaptive histogram equalization to improve contrast in images.|
|Image cache|	secure methods and tools to cache images, image sequences, video, audio or metadata in a local folder..|
|Image calculator|	apply a mathematical expression to an image, image sequence, or image channels.|
|Image gradients|	create a gradual blend of two colors whose shape is horizontal, vertical, circular, or elliptical.|
|Image identification|	describe the format and attributes of an image.|
|ImageMagick on the iPhone	convert, edit, or compose images on your iOS device such as the iPhone or iPad.|
|Large image support|	read, process, or write mega-, giga-, or tera-pixel image sizes.|
|Montage	juxtapose image thumbnails on an image canvas.|
|Morphology of shapes|	extract features, describe shapes, and recognize patterns in images.|
|Motion picture support|	read and write the common image formats used in digital film work.|
|Multispectral imagery|	support multispectral imagery up to 32 bands, 22 of them meta channels.|
|Noise and color reduction|	Kuwahara Filter, mean-shift.|
|Perceptual hash|	map visually identical images to the same or similar hash-- useful in image retrieval, authentication, indexing, or copy detection as well as digital watermarking.|
|Special effects	blur, sharpen, threshold, or tint an image.|
|Text & comments	|insert descriptive or artistic text in an image.|
|Threads of execution support	|ImageMagick is thread safe and most internal algorithms execute in parallel to take advantage of speed-ups offered by multicore processor chips.|
|Transform	|resize, rotate, deskew, crop, flip or trim an image.|
|Transparency	|render portions of an image invisible.|
|Virtual pixel support	|convenient access to pixels outside the image boundaries.|
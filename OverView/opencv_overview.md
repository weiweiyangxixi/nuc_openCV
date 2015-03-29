# OpenCV 概述

##OpenCV编程简介


- 了解[什么是OpenCV](http://zh.wikipedia.org/wiki/OpenCV)
- 阅读[OpenCV编程简介(英文)](http://www.cs.iit.edu/~agam/cs512/lect-notes/opencv-intro/)

## 相关工具

### ImageMagick

[ImageMagick](http://www.imagemagick.org/script/index.php)它是主要专注于数字图像处理任务的工具，主要为通过命令行方式来使用。也就是说，我们可以把它当作以命令行交互形式存在的 PhotoShop。建议程序员们要学会使用它来完成切图等简单的工作——对于程序员来说，这确实应该是很酷的体验。Apress 出过一本介绍 ImageMagick 的书——[The Definitive Guide to ImageMagick](http://book.douban.com/subject/1798283/)


### Codeblocks MinGW OpenCV

Codeblocks绝对是我最喜欢的IDE，没有之一(sublime不算IDE)，满满都是信仰，相信有很多人可能在不知不觉中用上了Codeblocks，可能都是我的功劳哟，OpenCV中文网有关于[Codeblocks如何配置OpenCV](http://wiki.opencv.org.cn/index.php/Codeblocks_MinGW_openCV)如果会配置vs2013那么相信配置Codeblocks也是非常简单的

### OpenCV Java with Eclipse

相信有不少同学希望自己能够做一个基于OpenCV的安卓小软件，我们的任务之一也是完成一个基于OpenCV图像识别的安卓软件，OpenCV提供了OpenCV Java为Java用户提供了强大的库,[如何配置Eclipse](http://docs.opencv.org/doc/tutorials/introduction/java_eclipse/java_eclipse.html#java-eclipse)

### OpenCV For Android

移动开发神器，详看[Introduction into Android Development](http://docs.opencv.org/doc/tutorials/introduction/android_binary_package/android_dev_intro.html#android-dev-intro)及[Android Development with OpenCV](http://docs.opencv.org/doc/tutorials/introduction/android_binary_package/dev_with_OCV_on_Android.html#dev-with-ocv-on-android),[Android SDK OpenCV](http://docs.opencv.org/doc/tutorials/introduction/android_binary_package/O4A_SDK.html#o4a-sdk)

## 练习题

1.什么是OpenCV
OpenCV是一个开源的计算机视觉库，包含大量的图形图像处理函数，方便我们进行计算机视觉的程序开发

2.OpenCV基本架构有哪些
分为6个部分：
1 CXCORE，他是opencv的一个子库，提供基本的数据结构定义，以及矩阵&数组的基本运算，还有错误处理基本函数[http://blog.csdn.net/wangjie0377/article/details/6629293]有详细的讲解
   概览：基础结构：CvPoint,CvSize,CvScalar等
         数组操作：cvCreateImage,cvCreateMat等
         动态结构：CvMemStorage,CvMemBlock等
         绘图函数：cvLine,cvRectangle等
         数据保存和运行时类型信息：CvFileStorage,cvOpenFileStorage等
         错误处理和系统函数:cvGetErrStatus,cvAlloc,cvFree等
2 CV[http://blog.csdn.net/wode0239/article/details/8483923]
   概览：图像处理：cvSobel，cvCanny等
         结构分析：ContourArea等 :（轮廓分析，轮廓提出等）
         运动分析与目标跟踪：cvMeanShift等
         模式识别：CvHaarFeature
         摄像头定标与三维重建：cvCalibrateCamer2
3 HighGUI提供图像和视屏的输入输出技术[http://www.cnblogs.com/luluathena/archive/2010/09/29/1838471.html]
   概览：图像界面函数：cvNamedWindow
         读图像和保存图像：cvLoadImage，cvSaveImage
         读视频和写视频：CvCreateFileCapture
4 CVCAM摄像机接口（已经撤销）
5 CVAUX即将淘汰以及试验阶段的算法于函数
6 ML（machine learing~~）包含许多聚类、分类和数据分析函数。如Bayes分类器，K近邻算法，支持向量机，决策树，神经网络等等
##[http://s9.sinaimg.cn/middle/68ed8b21hc6ac9e00f298&690]这张图可以直观的表达OPENCV各模块的关系
###@LKel

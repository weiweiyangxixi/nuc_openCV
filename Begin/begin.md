# OpenCV 入门


## 下载OpenCV


下载[OpenCV3.0 for Windwos](http://opencv.org/downloads.html)

## 配置OpenCV

为VS2013配置好OpenCV，详细方法自行Google

## 练习题

1.上传vs2013配置文件至repo

2.写一个简单的小程序，读取一张图片并显示出来

3.写一个简单的小程序，读取一段视频并播放出来，并使用cvCreateTrackbar()为该视频创建一个滚动条

4.观察下列代码:

```
int main( int argc, char** argv ) {

  IplImage* img = cvLoadImage( argv[1] );
  cvNamedWindow("Example1", CV_WINDOW_AUTOSIZE );
  cvShowImage("Example1", img );
  cvWaitKey(0);
  cvReleaseImage( &img ); 
  cvDestroyWindow("Example1");

}
```
这段代码可以运行么，可以运行的话它的作用是什么，不能的话原因是什么


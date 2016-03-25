# MyAndroidNote
介绍android相关笔记

> * 整理知识，学习笔记
> * 发布日记，杂文，所见所想
> * 撰写发布技术文稿

## Android网络知识
[Android网络请求心路历程](http://www.jianshu.com/p/3141d4e46240)

## Android图片处理知识
### 1. Bitmap
[Android Bitmap面面观](http://jayfeng.com/2016/03/22/Android-Bitmap%E9%9D%A2%E9%9D%A2%E8%A7%82/)
[Android 开发绕不过的坑：你的 Bitmap 究竟占多大内存？](http://bugly.qq.com/bbs/forum.php?mod=viewthread&tid=498)

**Bitmap** “在不兼容Android2.3的情况下，别在使用recycle方法来管理Bitmap了，那是GC的事！
详情请看[Bitmap.recycle引发的血案](http://blog.csdn.net/eclipsexys/article/details/50581162) 但是事实上这个说法是不准确的，是不能作为recycle()方法不调用的依据的。
因为从commit history中看，这行注释早在08年初始化代码的就有了，但是早期的代码并没有因此不需要recycle()方法了。医生说的那个bug，显然是一种优化策略，APP开发中加个两个bitmap不相等的判断条件即可。

## Android动画

## Android性能优化
[Android界面性能调优手册](https://androidtest.org/android-graphics-performance-pattens/)
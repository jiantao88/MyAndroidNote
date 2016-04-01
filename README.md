# MyAndroidNote
介绍android相关笔记

> * 整理知识，学习笔记
> * 发布日记，杂文，所见所想
> * 撰写发布技术文稿

## Android网络知识
[让你升级的网络知识](https://segmentfault.com/a/1190000004569460)

[Android网络请求心路历程](http://www.jianshu.com/p/3141d4e46240)

[移动网络下的性能优化之网络篇](https://segmentfault.com/a/1190000004561343)

## Android图片处理知识
### 1. Bitmap
[Android Bitmap面面观](http://jayfeng.com/2016/03/22/Android-Bitmap%E9%9D%A2%E9%9D%A2%E8%A7%82/)
[Android 开发绕不过的坑：你的 Bitmap 究竟占多大内存？](http://bugly.qq.com/bbs/forum.php?mod=viewthread&tid=498)

**Bitmap** “在不兼容Android2.3的情况下，别在使用recycle方法来管理Bitmap了，那是GC的事！
详情请看[Bitmap.recycle引发的血案](http://blog.csdn.net/eclipsexys/article/details/50581162) 但是事实上这个说法是不准确的，是不能作为recycle()方法不调用的依据的。
因为从commit history中看，这行注释早在08年初始化代码的就有了，但是早期的代码并没有因此不需要recycle()方法了。医生说的那个bug，显然是一种优化策略，APP开发中加个两个bitmap不相等的判断条件即可。

**setBackgroundResource导致内存溢出** [android 内存溢出oom错误的一些小见解](http://blog.csdn.net/xuhui_7810/article/details/9493681)

## Android动画
[Android动画开发——Animation动画效果详解](http://jcodecraeer.com/a/anzhuokaifa/androidkaifa/2012/1113/548.html)

## Android性能优化
[Android界面性能调优手册](https://androidtest.org/android-graphics-performance-pattens/)

[Android之内存管理及优化](http://www.jianshu.com/p/9546d21376ed)

[Android 性能优化之使用MAT分析内存泄露问题](http://jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0309/2565.html)
## Android架构

[Android 中的依赖注入框架](http://jcodecraeer.com/a/anzhuokaifa/androidkaifa/2016/0226/3998.html)

## Java相关知识
[理解Java垃圾回收机制](http://www.jayfeng.com/2016/03/11/%E7%90%86%E8%A7%A3Java%E5%9E%83%E5%9C%BE%E5%9B%9E%E6%94%B6%E6%9C%BA%E5%88%B6/)

[Java虚拟机类加载机制](http://blog.csdn.net/u013256816/article/details/50829596)

## 设计模式

[设计模式](http://design-patterns.readthedocs.org/zh_CN/latest/structural_patterns/bridge.html)


## RxJava 
[深入浅出RxJava](http://blog.csdn.net/lzyzsd/article/details/41833541)

[RxJava应用场景：使用zip操作符等待多个网络请求完成](http://jcodecraeer.com/a/anzhuokaifa/androidkaifa/2016/0325/4080.html)

## 算法
[Java链表](http://blog.csdn.net/fightforyourdream/article/details/16353519)

[各种排序算法的实现Java](http://my.oschina.net/byronhs/blog/508615)

[最长回文串算法](http://blog.csdn.net/wdxin1322/article/details/12172487)
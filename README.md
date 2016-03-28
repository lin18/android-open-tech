# android-open-tech
另一个号星标的项目太多了，朝2000进发，重新开一个记录收集一些重要技术
<br>
<br>
<br>***热补丁***
<br>[各大Android热补丁方案分析和比较](http://www.tuicool.com/articles/Fraqeab)
<br>[Nuwa](https://github.com/jasonross/Nuwa)
<br>[dexposed](https://github.com/alibaba/dexposed)
<br>[AndFix](https://github.com/alibaba/AndFix)
<br>一开始用Nuwa，没混淆没有问题，混淆后没生成相应文件。后来使用AndFix接入项目成功
<br>
<br>***数据库 orm***
<br>[ActiveAndroid](https://github.com/pardom/ActiveAndroid)
<br>[greenDAO](https://github.com/greenrobot/greenDAO)
<br>[Realm](https://github.com/realm/realm-java)
<br>用过ActiveAndroid，使用方便很多，不过有bug，相同的代码后来出现bug，不知道是数据库越来越大还是其它原因导致的。Realm有很多大牛公司用，建议使用
<br>
<br>***插件化***
<br>[携程Android App插件化和动态加载实践](http://www.infoq.com/cn/articles/ctrip-android-dynamic-loading/)
<br>[Android 插件化 动态升级](http://www.trinea.cn/android/android-plugin/)
<br>[DynamicAPK](https://github.com/CtripMobile/DynamicAPK)
<br>[dynamic-load-apk](https://github.com/singwhatiwanna/dynamic-load-apk)
<br>[Android Dynamic Loader](https://github.com/mmin18/AndroidDynamicLoader)
<br>[DroidPlugin](https://github.com/Qihoo360/DroidPlugin)
<br>dynamic-load-apk用到的技术点和[Nuwa](https://github.com/jasonross/Nuwa)中使用到的技术有相同的地方。建议先尝试360团队出的DroidPlugin
<br>
<br>***进程常驻***
<br>[Android 进程常驻（0）----MarsDaemon使用说明](http://blog.csdn.net/marswin89/article/details/50917098)
<br>[MarsDaemon](https://github.com/Marswin/MarsDaemon)
<br>之前有一段时候是蜻蜓FM还是哪个FM所使用的方法，有时间研究下
<br>
<br>***Data Binding***
<br>[MasteringAndroidDataBinding](https://github.com/LyndonChin/MasteringAndroidDataBinding)
<br>[RoboBinding](https://github.com/RoboBinding/RoboBinding)
<br>MVVP模式感觉不是很好，好像用的不多，另外MVP方式使用起来也很蛋疼
<br>
<br>***RxJava***
<br>[给 Android 开发者的 RxJava 详解](http://gank.io/post/560e15be2dca930e00da1083)
<br>[ReactiveX](http://reactivex.io/)
<br>[ReactiveX中文文档](https://mcxiaoke.gitbooks.io/rxdocs/content/operators/From.html)
<br>[RxJava](https://github.com/ReactiveX/RxJava)
<br>[RxAndroid](https://github.com/ReactiveX/RxAndroid)
<br>[RxBinding](https://github.com/JakeWharton/RxBinding)
<br>一个在 Java VM 上使用可观测的序列来组成异步的、基于事件的程序的库。非常非常好的库
<br>
<br>***kotlin***
<br>[kotlin](https://github.com/JetBrains/kotlin)
<br>Kotlin 是一个基于 JVM 的新的编程语言，由 JetBrains 开发。
<br>
<br>***内存泄露检测和性能监控***
<br>[leakcanary](https://github.com/square/leakcanary)
<br>[BlockCanary](https://github.com/square/leakcanary)
<br>
<br>***svg代替png***
<br>[Android微信上的SVG](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=207863967&idx=1&sn=3d7b07d528f38e9f812e8df7df1e3322&scene=4&pass_ticket=ju78kdKHlS54rmyCsnYl0I90BsvhusA0qHyryj5uT9UqgjMG405GEwx1rT%2B0O6kF)
<br>[Vector Drawable](http://developer.android.com/tools/help/vector-asset-studio.html)
<br>[android-support-library](http://android-developers.blogspot.sg/2016/02/android-support-library-232.html)
<br>[vector-compat](https://github.com/wnafee/vector-compat)

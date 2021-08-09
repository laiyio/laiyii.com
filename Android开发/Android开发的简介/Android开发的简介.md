### Android的简介：

　　Android是一种基于Linux 内核和其他开源软件的修改版本的移动操作系统，主要为智能手机和平板电脑等触摸屏移动设备设计。Android是由一个被称为开放手机联盟的开发者联盟开发的，并由Google 提供商业赞助。它于 2007 年 11 月亮相，第一款商用 Android 设备HTC Dream于 2008 年 9 月推出。
<img src="https://raw.githubusercontent.com/laiyio/img/4bde7d4ec1ca9b8d7f208303d94f0e0ee64769ea/laiyii.com/Android%E5%BC%80%E5%8F%91/Android%E5%BC%80%E5%8F%91%E7%9A%84%E7%AE%80%E4%BB%8B/Android.png" alt="img" style="zoom:50%;" />


### Android的发展史：

　　Android操作系统最初由Andy Rubin（安迪 · 鲁宾）开发，后来被Google收购，并且让Andy Rubin继续负责开发Android项目。经过数年的研发，2007年11月，Google对外展示了这款名为Android的操作系统，并于84家硬件制造商，软件开发商以及电信运商组建开放手机联盟共同研发改良Android系统。随后Google以Apache开源许可证的授权方式，发布了Android的源代码。

　　2009年Google发布了Android1.5，该版本的Android界面非常豪华，吸引了大量开发者的目光。接下来，Android版本升级非常快，几乎每隔半年就会发布一个新的版本。目前Android的最新版本是11。

　　Android的各版本历史如下：

| API  |  发布日期  |             版本名称             |   版本别称   |
| :--: | :--------: | :------------------------------: | :----------: |
|  1   | 2008.9.23  |           Android 1.0            |              |
|  2   |  2009.2.9  |           Android 1.1            |              |
|  3   | 2009.4.27  |       Android 1.5 Cupcake        |   纸杯蛋糕   |
|  4   | 2009.9.15  |        Android 1.6 Donut         |    甜甜圈    |
|  5   | 2009.10.27 |        Android 2. Eclair         |     泡芙     |
|  6   | 2009.12.3  |       Android 2.0.1 Eclair       |     泡芙     |
|  7   | 2010.1.11  |        Android 2.1 Eclair        |     泡芙     |
|  8   | 2010.5.20  |        Android 2.2 Froyo         |    酸冻奶    |
|  9   | 2010.12.6  |     Android 2.3 Gingerbread      |     姜饼     |
|  10  |  2011.2.9  |    Android 2.3.3 Gingerbread     |     姜饼     |
|  11  | 2011.2.22  |      Android 3.0 Honeycomb       |     蜂窝     |
|  12  | 2011.5.10  |      Android 3.1 Honeycomb       |     蜂窝     |
|  13  | 2011.7.15  |      Android 3.2 Honeycomb       |     蜂窝     |
|  14  | 2011.10.18 |  Android 4.0 Ice Cream Sandwich  | 冰淇淋三明治 |
|  15  | 2011.12.16 | Android 4.0.3 Ice Cream Sandwich | 冰淇淋三明治 |
|  16  |  2012.7.9  |      Android 4.1 Jelly Bean      |    果冻豆    |
|  17  | 2012.11.13 |      Android 4.2 Jelly Bean      |    果冻豆    |
|  18  | 2013.7.24  |      Android 4.3 Jelly Bean      |    果冻豆    |
|  19  | 2013.10.31 |        Android 4.4 KitKat        |  奇巧巧克力  |
|  20  | 2014.6.24  |       Android 4.4W KitKat        |  奇巧巧克力  |
|  21  | 2014.11.4  |       Android 5.0 Lollipop       |    棒棒糖    |
|  22  |  2015.3.2  |       Android 5.1 Lollipop       |    棒棒糖    |
|  23  | 2015.10.2  |     Android 6.0 Marshmallow      |    棉花糖    |
|  24  | 2016.8.22  |        Android 7.0 Nougat        |    牛轧糖    |
|  25  | 2016.10.4  |        Android 7.1 Nougat        |    牛轧糖    |
|  26  | 2017.8.21  |         Android 8.0 Oreo         |    奥利奥    |
|  27  | 2017.12.5  |        Android 8.1.0 Oreo        |    奥利奥    |
|  28  |  2018.8.6  |          Android 9 Pie           |      派      |
|  29  |  2019.9.3  |            Android 10            |              |
|  30  |  2020.9.8  |            Android 11            |              |
|  31  |    待定    |            Android 12            |              |

### Android的平台架构：

　　Android系统构架，主要从高到低分为4层，依次是Android应用层，Android应用框架层，Android系统运行库层和Linux内核层。
　　
<img src="https://raw.githubusercontent.com/laiyio/img/main/laiyii.com/Android%E5%BC%80%E5%8F%91/Android%E5%BC%80%E5%8F%91%E7%9A%84%E7%AE%80%E4%BB%8B/pintaijiagou.png" alt="pintaijiagou" style="zoom:50%;" />

##### 1.Android应用层：

　　应用程序层是一个核心应用程序的集合，所有安装在手机上的应用程序都属于这一层。例如E-mail 客户端、SMS 短消息程序、日历、地图、浏览器、联系人管理程序等，它们一般都是使用Java进行编写。

##### 2.Android应用框架层：

　　应用框架层主要提供了构建应用程序时用到的各种API。开发人员可以完全访问核心应用程序所使用的API框架。该应用程序的架构设计简化了组件的重用；任何一个应用程序都可以发布它的功能块并且任何其它的应用程序都可以使用其所发布的功能块(不过得遵循框架的安全性限制)。同样，该应用程序重用机制也使用户可以方便的替换程序组件。

　　隐藏在每个应用后面的是一系列的服务和系统，其中包括（以下都是Android自带的一些核心的API）：

　　视图(Views)，可以用来构建应用程序，它包括列表(lists)，网格(grids)，文本框(textBoxes)，按钮(buttons)，甚至可嵌入的web浏览器。

　　内容提供器(ContentProviders)使得应用程序可以访问另一个应用程序的数据(如联系人数据库)，或者共享它们自己的数据。

　　资源管理器(ResourceManager)提供非代码资源的访问，如本地字符串，图形，和布局文件(layoutfiles)。

　　通知管理器(NotificationManager)使得应用程序可以在状态栏中显示自定义的提示信息。

　　活动管理器(ActivityManager)用来管理应用程序生命周期并提供常用的导航回退功能。

##### 3.Android系统运行库层：

1）程序库

　　Android包含一些C/C++库，这些库能被Android系统中不同的组件使用。它们通过Android应用程序框架为开发者提供服务。以下是一些核心库：

　　系统C库——一个从BSD继承来的标准C系统函数库(libc)，它是专门为基于embeddedlinux的设备定制的。

　　媒体库——基于PacketVideoopencore;该库支持多种常用的音频、视频格式回放和录制，同时支持静态图像文件。编码格式包括MPEG4,H.264,MP3,AAC,AMR,JPG,PNG。

　　SurfaceManager——对显示子系统的管理，并且为多个应用程序提供了2D和3D图层的无缝融合。

　　LibWebCore——一个最新的web浏览器引擎用，支持Android浏览器和一个可嵌入的web视图。

　　SGL——底层的2D图形引擎

　　3Dlibraries——基于OpenGLES1.0APIs实现;该库可以使用硬件3D加速(如果可用)或者使用高度优化的3D软加速。

　　FreeType——位图(bitmap)和矢量(vector)字体显示。

　　SQLite——一个对于所有应用程序可用，功能强劲的轻型关系型数据库引擎。

2）Android运行库

　　Android包括了一个核心库，该核心库提供了JAVA编程语言核心库的大多数功能。

　　每一个Android应用程序都在它自己的进程中运行，都拥有一个独立的Dalvik虚拟机实例。Dalvik被设计成一个设备可以同时高效地运行多个虚拟系统。Dalvik虚拟机执行(.dex)的Dalvik可执行文件，该格式文件针对小内存使用做了优化。同时虚拟机是基于寄存器的，所有的类都经由JAVA编译器编译，然后通过SDK中的“dx”工具转化成.dex格式由虚拟机执行。

　　Dalvik虚拟机依赖于linux内核的一些功能，比如线程机制和底层内存管理机制。

##### 4.Linux内核层：

　　Android的核心系统服务依赖于Linux2.6内核，如安全性，内存管理，进程管理，网络协议栈和驱动模型。Linux内核也同时作为硬件和软件栈之间的抽象层。 

#### Dalvik虚拟机：

　　Android应用程序主要的开发语言是Java。它通过Dalvik虚拟机来运行Java程序。Dalvik是Google公司自己设计用于Android平台的虚拟机。Dalvik虚拟机是Google等厂商合作开发的Android移动设备平台的核心组成部分之一。

　　它可以支持已转换为 .dex（即Dalvik Executable）格式的Java应用程序的运行，Dalvik 经过优化，允许在有限的内存中同时运行多个虚拟机的实例，每一个Dalvik 应用作为一个独立的Linux 进程执行，并且每个进程之间都可以进行通信。独立的进程可以防止在虚拟机崩溃的时候所有程序都被关闭。

　　dx是Dalvik虚拟机里面的一套工具，可以将 Java .class 转换成 .dex 格式. 一个dex档通常会有多个.class。由于dex有时必须进行最佳化，会使档案大小增加1-4倍，以ODEX结尾。

　　很长时间以来，Dalvik虚拟机一直被用户指责为拖慢安卓系统运行速度不如IOS的根源。

　　2014年6月25日，Android L 正式亮相于召开的谷歌I/O大会，Android L 改动幅度较大，谷歌将直接删除Dalvik，代替它的是传闻已久的ART。

#### ART模式：

　　ART模式英文全称为：Android runtime，谷歌Android 4.4系统新增的一种应用运行模式，与传统的Dalvik模式不同，ART模式可以实现更为流畅的安卓系统体验，对于大家来说，只要明白ART模式可让系统体验更加流畅，不过只有在安卓4.4以上系统中采用此功能。

　　ART模式与Dalvik模式最大的不同在于，在启用ART模式后，系统在安装应用的时候会进行一次预编译，在安装应用程序时会先将代码转换为机器语言存储在本地，这样在运行程序时就不会每次都进行一次编译了，执行效率也大大提升。

## 混合式移动开发

>目前主流移动应用程序大体分为四类：Web App、Hybrid App、 Native App 、小程序

- **Web App** 指采用Html5语言写出的App，不需安装。类似轻应用。生存在浏览器中的应用，基本上可以说是触屏版的网页应用
- **Hybrid APP** 指的是半原生半Web的混合类App。需安装，看上去类似Native App，但只有很少的UI Web View，访问的内容是 Web
- **Native APP** 指的是原生程序，一般依托于操作系统，有很强的交互，是一个完整的App，可拓展性强，需安装。
- **小程序** 指的是依附第三方平台（微信，支付宝），用户扫一扫或者搜一下即可打开应用，应用将无处不在，随时可用，但又无需安装卸载

----

#### 一、目前讯商采用Hybrid App开发的应用程序如下：

- 1.**E售易手机端**(cordova)
- 2.**E售易Ipad端**(cordova)
- 3.**电子看板**(cordova)
- 4.**手机报表**(hbuilder html5+规范)
- 5.**手机店铺**(phonegap)
- 6.**大自然开单助手**(phonegap)

#### 二、简述下  phonegap  cordova  hbuilder html5+规范
- 1.phonegap提出时间最早，大约在2008年，它是一个采用HTML，CSS和JavaScript的技术，创建移动跨平台移动应用程序的快速开发平台,它支持手机调试，支持云打包。截止2014年5月14日，phonegap支持以下功能：`加速计`,`摄像头`,`罗盘`,`通讯录`,`文档`,`地理定位`,`媒体`,`网络`,`通知(警告、声音和振动)`,`存储`。
- 2.cordova是PhoneGap被Adobe收购后贡献给Apache后的开源项目,是从PhoneGap中抽离出的核心代码，是驱动PhoneGap的核心引擎。有点类似Webkit(v8)和Google Chrome的关系,它不支持云打包，需要安装环境本地打包。
- 3.hbuilder html5+s是是运行于手机端的强化web引擎,除了支持标准HTML5外，还支持更多扩展的js api，使得js的能力不输于原生。5+ Runtime内置于HBuilder，在真机运行、打包时自动挂载.它支持云打包，支持本地打包，支持真机调试。


[安装环境](./安装环境)
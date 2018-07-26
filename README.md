# FlutterOSC
- 基于Google Flutter的开源中国客户端，支持Android和iOS。
- [GitHub戳这里](https://github.com/yubo725/FlutterOSC) 
- [关于Google Flutter](https://flutterchina.club/)

# Android扫码下载APK
- 请使用手机浏览器扫码下载，不要使用微信或者qq扫码
- <img src='./screenshots/qrcode.png'>

# 功能
- [x] 登录（使用osc账号）
- [x] 查看资讯（未登录即可查看）
- [x] 查看、回复、发表、评论动弹（需要登录）
- [x] 动弹小黑屋（需要登录）
- [x] “发现”部分的功能基本上都是用H5实现
- [x] 资讯列表、动弹列表、评论列表支持下拉刷新或分页加载
- [ ] 动弹中的图片预览暂未实现
- [ ] 摇一摇、“我的”页面功能暂时没完成
- [ ] 主题切换功能暂未实现

# 说明
1. 由于开源中国的openapi只提供了基于webview或浏览器的oauth认证方式，故该项目登录界面使用webview加载OSChina三方认证页面，请放心使用开源中国的账号和密码登录
2. 受开源中国openapi的限制，获取动弹数据需要登录，由于openapi的资讯接口提供的数据比较简单，故资讯部分采用python爬取的网页数据
3. 本项目纯属个人兴趣爱好而写，不是开源中国官方版本，源代码仅供学习交流，实际使用请下载安装开源中国[官方APP](https://www.oschina.net/app)

# 截图
#### iOS
<div>
    <img src='./screenshots/ios01.png' width=280>
    <img src='./screenshots/ios02.png' width=280>
    <img src='./screenshots/ios10.png' width=280>
</div>
<div>
    <img src='./screenshots/ios04.png' width=280>
    <img src='./screenshots/ios05.png' width=280>
    <img src='./screenshots/ios06.png' width=280>
</div>
<div>
    <img src='./screenshots/ios07.png' width=280>
    <img src='./screenshots/ios08.png' width=280>
    <img src='./screenshots/ios09.png' width=280>
</div>

#### Android
<div>
    <img src='./screenshots/android01.jpg' width=280>
    <img src='./screenshots/android02.jpg' width=280>
    <img src='./screenshots/android03.jpg' width=280>
</div>
<div>
    <img src='./screenshots/android04.jpg' width=280>
    <img src='./screenshots/android05.jpg' width=280>
    <img src='./screenshots/android06.jpg' width=280>
</div>
<div>
    <img src='./screenshots/android07.jpg' width=280>
    <img src='./screenshots/android08.jpg' width=280>
    <img src='./screenshots/android09.jpg' width=280>
</div>


### flutter doctor -v

        flutter doctor -v
        [✓] Flutter (Channel beta, v0.5.1, on Mac OS X 10.13.5 17F77, locale zh-Hans-CN)
            • Flutter version 0.5.1 at /Users/juju/libs/flutter
            • Framework revision c7ea3ca377 (8 weeks ago), 2018-05-29 21:07:33 +0200
            • Engine revision 1ed25ca7b7
            • Dart version 2.0.0-dev.58.0.flutter-f981f09760

        [✓] Android toolchain - develop for Android devices (Android SDK 28.0.1)
            • Android SDK at /Users/juju/Library/Android/sdk
            • Android NDK location not configured (optional; useful for native profiling support)
            • Platform android-28, build-tools 28.0.1
            • ANDROID_HOME = /Users/juju/Library/Android/sdk
            • Java binary at: /Applications/Android Studio.app/Contents/jre/jdk/Contents/Home/bin/java
            • Java version OpenJDK Runtime Environment (build 1.8.0_152-release-1024-b01)
            • All Android licenses accepted.

        [✓] iOS toolchain - develop for iOS devices (Xcode 9.4.1)
            • Xcode at /Applications/Xcode.app/Contents/Developer
            • Xcode 9.4.1, Build version 9F2000
            • ios-deploy 1.9.2
            • CocoaPods version 1.5.3

        [✓] Android Studio (version 3.1)
            • Android Studio at /Applications/Android Studio.app/Contents
            • Flutter plugin version 26.0.1
            • Dart plugin version 173.4700
            • Java version OpenJDK Runtime Environment (build 1.8.0_152-release-1024-b01)

        [✓] Connected devices (2 available)
            • iPhone 7 • C528A610-1B20-479A-AC60-266F78EE6EE6 • ios • iOS 11.4 (simulator)
            • iPhone X • A4A4D952-A762-41E2-B4B2-75C7D3B5C069 • ios • iOS 11.4 (simulator)

        • No issues found!
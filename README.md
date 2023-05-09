# iOS Development Relevant Resource Collection
我收藏的iOS开发相关技术资料

<br />

- [iOS10系统自动升级防止办法介绍](https://m.cr173.com/w/115259)
- [如何在iOS地图上高效显示大量数据](http://www.cocoachina.com/gamedev/misc/2013/1216/7548.html)
- [asn1c](https://github.com/vlm/asn1c/blob/master/INSTALL.md)
- [Xcode 添加多语言设置](https://www.bobolee.me/xcode-project-support-international.html)
- [Developing for Apple M7](http://conradstoll.com/blog/2013/11/24/developing-for-the-m7)
- [using AudioToolbox and AVFoundation to play music and sounds within you app – Tutorial](http://www.xappsoftware.com/wordpress/2013/12/05/ios-sdk-using-audiotoolbox-and-avfoundation-to-play-music-and-sounds-within-you-app-tutorial/)
- [opengl展开一张鱼眼图](http://www.cocoachina.com/bbs/read.php?tid=177145)
- [UIView边缘的glow动画特效 附效果图 + demo工程](http://www.cocoachina.com/bbs/read.php?tid=176102)
- [iOS将UIView转换成UIImageView](https://blog.csdn.net/ICHENKE/article/details/49181355)
- Quartz2D之如何将iOS默认上下文坐标系改变为Quartz通常坐标系——由于iOS的UIKit默认的坐标系的原点处于视图矩形的左上角，而Quartz的通常坐标系中的原点位于左下角。因此我们在使用Qaurtz处理图形的时候往往需要将坐标系转为与Quartz相一致的状态：
```objectivec
void translateCoordSystem(CGContextRef context, CGRect viewFrame)
{
    CGContextTranslateCTM(context, 0.0f, viewFrame.size.height);
    CGContextScaleCTM(context, 1.0f, -1.0f);
}
```
这样就可以正常绘制了。否则用默认方式绘制会出现上下颠倒的图形。

- [实现iOS应用内购买的三个核心步骤](http://blog.csdn.net/nimingzhe2008/article/details/19759589)
- [swift版内购](http://www.cnblogs.com/helloandroid/p/4613683.html)
- [iOS Fonts](http://iosfonts.com)
- [iOS使用自定义字体的方法(内置和任意下载ttf\otf\ttc字体文件)](https://blog.csdn.net/liuyang11908/article/details/62044319)
- [iOS开发之详解剪贴板](http://blog.csdn.net/zhuqilin0/article/details/6661044)
- [Xcode 7 Bitcode的工作流程及安全性评估](http://www.cocoachina.com/ios/20151218/14744.html)
- [Swift语言Storyboard教程：第一部分](http://www.cocoachina.com/swift/20150112/10892.html)
- [Swift语言Storyboard教程：第二部](http://www.cocoachina.com/swift/20150114/10924.html)
- [Xcode7 设置iOS启动界面（Launch Image）](https://www.jianshu.com/p/a3315f6896a7)
- [Apple Pay编程指南](http://www.cocoachina.com/ios/20150126/11019.html)
- [Apple Watch人机交互指南](http://www.cocoachina.com/design/20150312/10314.html)
- [App Store Marketing Guidelines](https://developer.apple.com/app-store/marketing/guidelines/)
- [App Store 营销准则](https://developer.apple.com/app-store/marketing/guidelines/cn/)
- [App Store Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)
- [你的App真正适配了iOS 9吗？（校验、禁用ATS）](http://www.csdn.net/article/2015-09-11/2825675)
- [iOS的iPhone屏幕尺寸、分辨率、PPI和使用123倍图](https://www.jianshu.com/p/31a1aca46ef8)
- [关于苹果IDFA 新规 以及在iOS 14中的获取](https://www.jianshu.com/p/4e40eebc7b8c)
- [iOS 一些设备信息的获取方法](https://blog.csdn.net/u013712343/article/details/120525765)
- [iOS传感器（指南针、GPS、加速计、摇一摇）](https://www.jianshu.com/p/41f279f2f439)
- [如何用Swift实现一个好玩的弹性动画](http://www.cocoachina.com/swift/20150911/13215.html)
- [iOS dSYM文件结构剖析（上）](http://www.csdn.net/article/2015-08-04/2825369)
- [iOS dSYM文件结构剖析(下)](http://blog.csdn.net/MaximLi/article/details/47300171)
- [iOS内核单字节利用技术](https://www.toutiao.com/a6856589621313470989/)
- [如何用 Keynote 做App原型设计？](http://www.cocoachina.com/design/20141023/10017.html)
- [IOS开发之----锁屏状态播放音乐时显示专辑信息和图片](http://blog.sina.com.cn/s/blog_71715bf801019xxr.html)
- [How to make a Swift framework?](https://theswiftdev.com/2017/10/23/how-to-make-a-swift-framework/)
- [动画黄金搭档:CADisplayLink & CAShapeLayer](http://www.cocoachina.com/ios/20161202/18252.html)
- [IOS开发之自定义CALayer方式实现绘图](https://www.jianshu.com/p/2c37530a80c9)
- [提取UIColor的RGBA](https://blog.csdn.net/iteye_7514/article/details/82483602)
- [从Swift看Objective-C的数组使用](http://www.cocoachina.com/ios/20161222/18420.html)
- [如何用Xcode 8和Swift 3 构建条形码和二维码识别器](http://www.cocoachina.com/ios/20161228/18394.html)
- [How To Scan QR Code Using AVFoundation Framework](https://www.appcoda.com/qr-code-ios-programming-tutorial/)
- [Xcode 中的相对路径与绝对路径的相关设置](http://www.cnblogs.com/sandyzhang/p/5639586.html)
- [WebView与JS的几种交互](http://www.jianshu.com/p/0042d8eb67c0)
- [AVPlayer缓存实现](http://www.cnblogs.com/graveliang/p/5711783.html)
- [iOS下拉刷新的实现](http://www.jianshu.com/p/423150df669d)
- [关于iOS开发中使用到的AES加密和SHA256加密的使用](http://blog.csdn.net/codingfire/article/details/50384986)
- [iOS中使用的MD5与Base64 (Objective-C)](https://www.jianshu.com/p/bdcd1c5f2685)
- [iOS扩大UIButton按钮的可点击区域](https://my.oschina.net/zhxx/blog/833549?utm_medium=referral)
- [为什么要用-all_load&-ObjC](http://www.cocoachina.com/bbs/read.php?tid=141097)
- [微信 iOS 收款到帐语音提醒开发总结](http://geek.csdn.net/news/detail/235961)
- [iOS开发之微信自动抢红包功能](http://blog.csdn.net/zhonggaorong/article/details/51224813)
- [Building a QR Code Generator with Core Image Filters](https://www.appcoda.com/qr-code-generator-tutorial/)
- [Working with the Files App in iOS 11](https://www.bignerdranch.com/blog/working-with-the-files-app-in-ios-11/)
- [Implementing iOS 8 Document Pickers](https://www.macstories.net/tutorials/implementing-ios-8-document-pickers/)
- [iOS 播放系统音效](https://blog.csdn.net/zhangdalang/article/details/53906910)
- [Unity项目接入IOS的Admob Native(原生视频广告) IOS SDK](https://blog.csdn.net/qq_39108767/article/details/84426400)
- [\[Unity3D\]关于XCode 工程的生成和 iOS 插件的编写](https://www.jianshu.com/p/ac37de27b404)
- [Unity3D学习笔记之调用iOS的*.a库](https://gameinstitute.qq.com/community/detail/111853)
- [Unity3D研究院之IOS全自动编辑framework、plist、oc代码（六十七）](https://blog.csdn.net/anypkv/article/details/72303571)
- [iOS 应用内直接评分问题](https://blog.csdn.net/a18337101357/article/details/80282891)
- iOS中将两个不同架构的库文件进行合并：**`lipo -create <lib1_path> <lib2_path> ... -output <dst_path>`**
- [史诗级规范！全新Apple iOS设计规范指南](https://www.toutiao.com/a6745640758742614535/)
- [iOS标准库中常用数据结构和算法之cache](https://www.toutiao.com/a6745643341427245571/)

<br/>

### iOS上获取某个文件的修改日期

```objectivec
let tmpFile = [NSTemporaryDirectory() stringByAppendingPathComponent:@"a.txt"];
let attrs = [NSFileManager.defaultManager attributesOfItemAtPath: tmpFile error:NULL];
if(attrs != nil && attrs.count > 0)
{
    let date = attrs.fileModificationDate;
    if(date != nil)
    {
        let formatter = NSDateFormatter.new;
        formatter.dateFormat = @"yyyy-MM-dd HH:mm:ss";
        NSLog(@"The modification date is: %@", [formatter stringFromDate:date]);
        [formatter release];
        
        NSLog(@"Time stamp: %llu ms", (int64_t)(date.timeIntervalSince1970 * 1000.0));
    }
}
```

<br />

### iOS获取应用当前Caches目录路径以及当前日期

```objectivec
    NSArray<NSString*> *paths = NSSearchPathForDirectoriesInDomains(NSCachesDirectory, NSUserDomainMask, YES);
    NSString *path = [paths[0] stringByAppendingString:@"/hi.dat"];
    
    [NSFileManager.defaultManager createFileAtPath:path contents:NULL attributes:NULL];
    
    NSURL *url = [NSURL.alloc initFileURLWithPath:path];
    NSLog(@"URL is: %@", url);
    [url release];

    NSDate *date = [NSDate dateWithTimeIntervalSinceNow:0.0];
    // 打印日期：中间的空格可以用'at'或'T'等字符来分隔
    NSDateFormatter *dateFomatter = NSDateFormatter.new;
    [dateFomatter setDateFormat:@"yyyy-MM-dd HH:mm:ss"];
    NSLog(@"Current date is: %@", [dateFomatter stringFromDate:date]);
    [dateFomatter release];
```

<br />

### iOS上使用iconfont

我们可以参考这篇文章做基础配置：[iOS使用iconFont](https://www.jianshu.com/p/36007fc8ba10)

首先将iconfont.ttf放入图片资源的assets中。在Xcode工程设置首页能跳转到那个页面，即放图标和首屏图片的地方。

如果我们要避免自己项目的iconfont与别家项目的iconfont混起来，那么我们可以编辑我们当前项目iconfont的**font family**。我们在阿里巴巴iconfont的首页中将光标移动到“图标管理”，然后选择“我的项目”。进入到项目界面之后，将光标移动到“更多操作”，然后选择“编辑项目”，随后我们可以修改**Font Family**。各位需要注意的是，iconfont的文件名与Font Family两者之间是没有关系的，所以光修改文件名还没用。
假定我们这里的Font Family修改为了“xxx_iconfont”，那么我们可以这么使用：
```objectivec
    UILabel *label = [UILabel.alloc initWithFrame:CGRectMake(20.0, 300.0, 30.0, 30.0)];
    label.font = [UIFont fontWithName:@"xxx_iconfont" size:26.0];
    label.textColor = UIColor.redColor;
    label.text = @"\ueb9b";     // iconfont所对应的图标编码（Unicode编码值）
    [self.view addSubview:label];
    [label release];
```

另外，在info.plist文件中添加字体支持的属性代码为：
```xml
	<key>UIAppFonts</key>
	<array>
		<string>xxx_iconfont.ttf</string>
	</array>
```

这么一来，我们自己的iconfont与别家的就能很好的区分了。


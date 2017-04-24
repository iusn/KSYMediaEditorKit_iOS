# KSYMediaEditorKit_iOS

## 一. 功能特性
* [x] 短视频SDK鉴权
* [x] 短视频录制
* [x] 短视频文件导入
* [x] 录制或导入视频预览编辑
* [x] 编辑合成添加滤镜
* [x] 编辑合成添加水印
* [x] 编辑文件合成
* [x] 合成文件上传KS3
* [x] 上传后文件预览播放 
## 二. SDK集成方法介绍   
### 2.1 系统要求 
2.1 系统要求    
* 最低支持iOS版本：iOS 7.0
* 最低支持iPhone型号：iPhone 4
* 支持CPU架构： armv7,armv7s,arm64(和i386,x86_64模拟器)
* 含有i386和x86_64模拟器版本的库文件，录制功能无法在模拟器上工作，合成、播放功能完全支持模拟器。

### 2.2 下载工程
本SDK 提供如下列出获取方式:     
#### 2.2.1 从[github](https://github.com/ksvc/KSYMediaEditorKit_iOS.git) clone

目录结构如下所示:  
- demo.xcodeproj              : demo工程为demo.xcodeproj ，演示本SDK的主要接口的使用
- prebuilt                    : 预编译库和资源文件
  - KSYMediaEditorKit.podspec : 本地podspec
  - libs                      : 预编译库
  - resource                  : 资源文件

```
$ git clone https://github.com/ksvc/KSYMediaEditorKit_iOS.git
```

### 2.2.2 GPUImage依赖

请参考官方cocoapods提供的[GPUImage](https://github.com/BradLarson/GPUImage/releases/tag/0.1.7)，当前我们测试通过的版本是[0.1.7](https://github.com/BradLarson/GPUImage/releases/tag/0.1.7)

### 2.3 开始运行demo工程
#### 2.3.1 使用Cocoapod的的方式来运行demo 
demo 目录中已经有一个Podfile, 指定了本地开发版的pod    
在demo目录下执行如下命令, 即可开始编译运行demo  
```
$ pod install
$ open demo.xcworkspace
```

注意:
1. 更新pod之后, 需要打开 xcwrokspace, 而不是xcodeproj


## 四. 反馈与建议
* 主页：[金山云](http://www.ksyun.com/)
* 邮箱：<zengfanping@kingsoft.com>
* QQ讨论群：574179720 [视频云技术交流群] 
* Issues:<https://github.com/ksvc/KSYMediaEditorKit_iOS/issues>

<a href="http://www.ksyun.com/"><img src="http://www.ksyun.com/assets/img/static/logo.png" border="0" alt="金山云计算" /></a>
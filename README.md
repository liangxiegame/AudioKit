# AudioKit

一套音频管理工具

由 QFramework 团队官方维护的独立工具包（不依赖 QFramework）。

## 环境要求

* Unity 2018.4LTS

## 安装

* PackageManager
    * add from package git url：https://github.com/liangxiegame/AudioKit.git 
    * 或者国内镜像仓库：https://gitee.com/liangxiegame/AudioKit.git
* 或者[点此下载 AudioKit.unitypackage](AudioKit.unitypackage) 并安装到自己项目中的任意脚本中

## 使用指南

``` csharp
// load from resources
AudioKit.PlaySound("SaySomething");
AudioKit.PlayVoice("SomeVoice");
AudioKit.PlayMusic("SomeMusic");

// load from ResKit
AudioKit.Config.AudioLoaderPool = new ResKitAudioLoaderPool();
AudioKit.PlaySound("resources://saysomething");
AudioKit.PlayVoice("resources://somevoice");
AudioKit.PlayMusic("resources://somemusic");
```



## 更多

* QFramework 地址: https://github.com/liangxiegame/qframework


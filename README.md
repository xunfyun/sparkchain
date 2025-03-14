# SparkChain 语音能力 Android SDK

[![](https://jitpack.io/v/xunfyun/sparkchain.svg)](https://jitpack.io/#xunfyun/sparkchain)

更多集成文档请参考讯飞开放平台官网文档说明： [https://www.xfyun.cn/doc/](https://www.xfyun.cn/doc/)

## Gradle
在根目录的 build.gradle 添加：

```
allprojects {
    repositories {
        // ...
        maven { url 'https://www.jitpack.io' }
    }
}
```

添加依赖：
```
dependencies {
    implementation 'com.github.xunfyun:sparkchain:2.0.0_rc5'
}
```

打包冲突解决

```
android {

    ....

    packagingOptions {
        exclude 'META-INF/NOTICE.md'
        exclude 'META-INF/LICENSE.md'
        exclude 'META-INF/INDEX.LIST'
        exclude 'META-INF/DEPENDENCIES'
        exclude 'META-INF/io.netty.versions.properties'
    }
}
```


## 更新日志
[Releases](https://github.com/xunfyun/SparkChain/releases)
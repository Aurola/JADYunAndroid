# JADYunAndroid
京东广告联盟 京准通SDK

# 接入说明

一、在项目的build.gradle中配置：

```
repositories {
  maven { url 'https://jitpack.io' }      
}
```


二、在module的build.gradle中配置：
## 单广告位按需接入 

```
dependencies {
    implementation 'com.github.Aurola.JADYunAndroid:jad_yun_core:1.0.2'
    implementation 'com.github.Aurola.JADYunAndroid:jad_yun_splash:1.0.2'
    implementation 'com.github.Aurola.JADYunAndroid:jad_yun_banner:1.0.2'
    implementation 'com.github.Aurola.JADYunAndroid:jad_yun_feed:1.0.2'
    implementation 'com.github.Aurola.JADYunAndroid:jad_yun_interstitial:1.0.2'
    implementation 'com.github.Aurola.JADYunAndroid:jad_yun_native:1.0.2'
}
```

## 全广告位接入
```
dependencies {
    implementation 'com.github.Aurola.JADYunAndroid:jad_yun_sdk:1.0.2'
}
```
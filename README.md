# Loading
![](https://img.shields.io/badge/platform-android-orange.svg)
![](https://img.shields.io/badge/language-java-yellow.svg)
![](https://jitpack.io/v/iwdael/loading.svg)
![](https://img.shields.io/badge/build-passing-brightgreen.svg)
![](https://img.shields.io/badge/license-apache--2.0-green.svg)
![](https://img.shields.io/badge/api-19+-green.svg)

一个为Android平台设计的加载动画，简单好用。

![avi](screenshots/avi.gif)

## 使用教程

#### 代码示例
```
<com.iwdael.loading.LoadingView
        android:id="@+id/avi"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:indicatorName="BallPulseIndicator"//指示器名称
        app:indicatorColor="your color" //图标颜色
        />
```

### 配置项目

#### 配置工程根目录build.gradle
```
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}
```
#### 配置App Module下build.gradle
```
dependencies {
    implementation com.iwdael:loading:$version
}
```

## Indicators

如上**Demo**所示，指标如下：

**Row 1**
 * `BallPulseIndicator`
 * `BallGridPulseIndicator`
 * `BallClipRotateIndicator`
 * `BallClipRotatePulseIndicator`

**Row 2**
 * `SquareSpinIndicator`
 * `BallClipRotateMultipleIndicator`
 * `BallPulseRiseIndicator`
 * `BallRotateIndicator`

**Row 3**
 * `CubeTransitionIndicator`
 * `BallZigZagIndicator`
 * `BallZigZagDeflectIndicator`
 * `BallTrianglePathIndicator`

**Row 4**
 * `BallScaleIndicator`
 * `LineScaleIndicator`
 * `LineScalePartyIndicator`
 * `BallScaleMultipleIndicator`

**Row 5**
 * `BallPulseSyncIndicator`
 * `BallBeatIndicator`
 * `LineScalePulseOutIndicator`
 * `LineScalePulseOutRapidIndicator`

**Row 6**
 * `BallScaleRippleIndicator`
 * `BallScaleRippleMultipleIndicator`
 * `BallSpinFadeLoaderIndicator`
 * `LineSpinFadeLoaderIndicator`

**Row 7**
 * `TriangleSkewSpinIndicator`
 * `PacmanIndicator`
 * `BallGridBeatIndicator`
 * `SemiCircleSpinIndicator`
 
**Row 8**
 * `com.iwdael.loading.demo.MyCustomIndicator`


### 感谢
Power by [HarlonWang/AVLoadingIndicatorView](https://github.com/HarlonWang/AVLoadingIndicatorView)
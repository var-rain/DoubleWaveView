#### 波浪加载动画

#### 效果预览

- 圆形遮罩

![Screen Capture](https://github.com/1934016928/DoubleWaveView/raw/master/capture/screen_capture_1.gif)

- 非圆形遮罩

![Screen Capture](https://github.com/1934016928/DoubleWaveView/raw/master/capture/screen_capture_2.gif)

#### 属性介绍
- 波浪高度,范围 0-100
```
app:dw_base_line="40"
```
- 背景颜色
```
app:dw_bg_color="#666666"
```
- 圆形遮罩
```
app:dw_circle="false"
```
- 速度,越大越慢
```
app:dw_speed="0.8"
```
- 透明度,范围 0-255
```
app:dw_wave_alpha="120"
```
- 波浪颜色
```
app:dw_wave_color="#ffffff"
```
- 浪高
```
app:dw_wave_level="20"
```
#### 使用方式
```xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#444444"
    tools:context=".MainActivity">

    <com.var.doublewaveview.DoubleWaveView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_centerInParent="true"
        app:dw_base_line="40"
        app:dw_bg_color="#666666"
        app:dw_circle="false"
        app:dw_speed="0.8"
        app:dw_wave_alpha="120"
        app:dw_wave_color="#ffffff"
        app:dw_wave_level="20" />

</RelativeLayout>
```
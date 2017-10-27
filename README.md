#FlycoRoundView
A library helps Android built-in views easy and convenient to set round rectangle background and accordingly related shape resources can be reduced.
一个扩展原生控件支持圆角矩形框背景的库,可以减少相关shape资源文件使用.
##Demo
![](https://github.com/H07000223/FlycoRoundView/blob/master/preview.gif)

##Gradle

```groovy
dependencies{
    compile 'com.flyco.roundview:FlycoRoundView_Lib:1.1.4@aar'
}
```

###Attributes

|name|format|description|
|:---:|:---:|:---:|
| rv_backgroundColor | color | background color 背景颜色
| rv_backgroundPressColor | color | background press color 背景触摸颜色
| rv_cornerRadius | dimension | background rectangle corner radius,unit dp 圆角半径,单位dp
| rv_strokeWidth | dimension | background rectangle stroke width,unit dp 线宽 单位dp
| rv_strokeColor | color |background rectangle stroke color 外框线条颜色
| rv_strokePressColor | color |background rectangle stroke press color 外框线条触摸颜色
| rv_textPressColor | color |text press color 文字触摸颜色
| rv_isRadiusHalfHeight | boolean | corner radius is half of height 左右对称圆角效果
| rv_isWidthHeightEqual | boolean | width and height is the same size which is the max value of them 宽高相等
| rv_cornerRadius_TL | dimension | corner radius top left,unit dp 左上角半径
| rv_cornerRadius_TR | dimension | corner radius top right,unit dp 右上角半径
| rv_cornerRadius_BL | dimension | corner radius bottom left,unit dp 坐下角半径
| rv_cornerRadius_BR | dimension | corner radius bottom right,unit dp 右下角半径
| rv_isRippleEnable | boolean | is ripple effect enable for Api21+  是否开启水波纹效果


## Android 常用自定义控件

* [CircleImageView 原型图片](#CircleImageView)



#### CircleImageView
    该类是圆形图片，主要包含一个继承AppCompatImageView类的自定义控件类，
    需要在styles.xml中定义控件的属性。包括图片外围的宽度颜色等等。使用比较简单
    例如：
```
<com.dawn.dawn.views.CircleImageView
        android:id="@+id/circle"
        android:layout_width="96dp"
        android:layout_height="96dp"
        android:src="@mipmap/ic_launcher"
        app:civ_border_width="2dp"
        app:civ_border_color="#FF000000"/>
```
![CircleImageView](../../../../../../../assets/circle_image_renderings.png "圆形图片效果图")

Android XML 绘制牛皮纸背景色

```
<?xml version="1.0" encoding="utf-8"?>
<layer-list xmlns:android="http://schemas.android.com/apk/res/android">
    <item>
        <shape android:shape="rectangle" >
          <padding
              android:left="16dp"
              android:right="16dp"/>
        </shape>
    </item>
    <item>
        <shape android:shape="rectangle" >
            <gradient
                android:startColor="#FFE9CC"
                android:centerColor="#FFF0D7"
                android:endColor="#FFF9E6"
                android:type="linear"
                android:angle="90"
                android:centerX="0.5"
                android:centerY="0.5" />
        </shape>
    </item>
    <item
        android:top="100dp">
        <shape android:shape="rectangle" >
            <gradient
                android:startColor="#FFD28B"
                android:centerColor="#00FFF9E6"
                android:endColor="#00FFF9E6"
                android:type="linear"
                android:angle="90"
                android:centerX="0.5"
                android:centerY="0.08" />
        </shape>
    </item>
    <item
        android:bottom="100dp">
        <shape android:shape="rectangle" >
            <gradient
                android:startColor="#FFD28B"
                android:centerColor="#00FFF9E6"
                android:endColor="#00FFF9E6"
                android:type="linear"
                android:angle="-90"
                android:centerX="0.5"
                android:centerY="0.08" />
        </shape>
    </item>
    <item>
        <shape android:shape="rectangle" >
            <gradient
                android:startColor="#FFD28B"
                android:centerColor="#00FFF9E6"
                android:endColor="#00FFF9E6"
                android:type="linear"
                android:angle="180"
                android:centerX="0.5"
                android:centerY="0.08" />
        </shape>
    </item>
   <item>
        <shape android:shape="rectangle" >
            <gradient
                android:startColor="#FFD28B"
                android:centerColor="#00FFF9E6"
                android:endColor="#00FFF9E6"
                android:type="linear"
                android:angle="0"
                android:centerX="0.5"
                android:centerY="0.08" />
        </shape>
    </item>

</layer-list>
```
效果图


![image](https://github.com/hui32/drawable/blob/master/images/brown_paper_bg_image.png)

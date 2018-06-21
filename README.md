# MyProgressBar
MyProgressBar
<br/><br/>

## 效果图

 ![Screenshots](https://github.com/xqgdmg/MyProgressBar/blob/master/imgs/progress.jpeg)
 <br/><br/>
 
 style="?android:attr/progressBarStyleHorizontal"<br/>
 style="@android:style/Widget.ProgressBar.Horizontal"<br/>
 style="?android:attr/progressBarStyle"<br/>
 style="?android:attr/progressBarStyleInverse"<br/>
 style="?android:attr/progressBarStyleLarge"<br/>
 style="?android:attr/progressBarStyleLargeInverse"<br/>
 style="?android:attr/progressBarStyleSmall"<br/>
 style="?android:attr/progressBarStyleSmallInverse"<br/>
 style="?android:attr/progressBarStyleSmallTitle"<br/>
 <br/>
 最后一个，模仿系统，自定义样式 <br/>
 style="@style/mProgress_horizontal"<br/>
 android:background="@drawable/custom_progressbar_horizontal"<br/><br/>
 
 <?xml version="1.0" encoding="utf-8"?><br/>
 <layer-list xmlns:android="http://schemas.android.com/apk/res/android"><br/>
     <item android:id="@android:id/background"><br/>
         <shape><br/>
             <corners android:radius="5dip" /><br/>
             <gradient<br/>
                 android:startColor="#ff9d9e9d"<br/>
                 android:centerColor="#ff5a5d5a"<br/>
                 android:centerY="0.75"<br/>
                 android:endColor="#ff747674"<br/>
                 android:angle="270"<br/>
                 /><br/>
         </shape><br/>
     </item><br/>
     <item android:id="@android:id/secondaryProgress"><br/>
         <clip><br/>
             <shape><br/>
                 <corners android:radius="5dip" /><br/>
                 <gradient<br/>
                     android:startColor="#80ffd300"<br/>
                     android:centerColor="#80ffb600"<br/>
                     android:centerY="0.75"<br/>
                     android:endColor="#a0ffcb00"<br/>
                     android:angle="270"<br/>
                     /><br/>
             </shape><br/>
         </clip><br/>
     </item><br/>
     <item android:id="@android:id/progress"><br/>
         <clip><br/>
             <shape><br/>
                 <corners android:radius="5dip" /><br/>
                 <gradient<br/>
                     android:startColor="#55ff0000"<br/>
                     android:centerColor="#550000ff"<br/>
                     android:centerY="0.75"<br/>
                     android:endColor="#5500ff00"<br/>
                     android:angle="270"<br/>
                     /><br/>
             </shape><br/>
         </clip><br/>
     </item><br/>
 </layer-list><br/>
 


# Widget
Android 自定义Button
目的：解决重复引用selector,减少图片资源占用apk瘦身
![image](https://github.com/xing609/Widget/blob/master/UniversalButton/app/assets/universal_button.gif)

----------
**只设置背景**
 `<com.star.widget.UniversalBtn
android:layout_width="70dp"
android:layout_height="70dp"
android:layout_gravity="center"
app:normalDrawable="@drawable/ic_launcher" />`

**只设置正常颜色**
 ` <com.star.widget.UniversalBtn
                android:id="@+id/normalBtn"
                android:layout_width="wrap_content"
                android:layout_height="50dp"
                android:layout_gravity="center"
                android:layout_marginTop="10dp"
                android:text="默认矩形一种颜色"
                android:paddingLeft="15dp"
                android:paddingRight="15dp"
                app:normalSolid="@color/c1" />`

**正常引用selector,改变字体按下颜色**
 `  <com.star.widget.UniversalBtn
                android:id="@+id/selectedBtn"
                android:layout_width="60dp"
                android:layout_height="60dp"
                android:layout_gravity="center"
                android:layout_marginTop="10dp"
                android:background="@drawable/sel_btn_love"
                android:text="图片"
                android:textSize="12sp"
                app:normalTextColor="@color/c1"
                app:selectedTextColor="@color/c4" />`



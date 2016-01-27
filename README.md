MultiImgUpload
====
参考lovetuzitong/MultiImageSelector
https://github.com/lovetuzitong/MultiImageSelector
#动态截图
![](https://github.com/a741762308/MultiImgUpload/blob/master/Screenshots.gif)
#例子
#######请参考本例
#使用方法
#######鉴于lovetuzitong并没有上传maven或jcenter，我仅是将代码上传
## build.gradle文件
```java
dependencies {
  compile 'com.wuxiaolong.pullloadmorerecyclerview:library:1.0.4'
}
```
##manifest文件
###权限
```java
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.MOUNT_UNMOUNT_FILESYSTEMS" />
<uses-permission android:name="android.permission.CAMERA" />
```
###需要声明的activity
```java
 <activity android:name="me.nereo.multi_image_selector.ViewPhotoActivity" />
 <activity
            android:name="me.nereo.multi_image_selector.MultiImageSelectorActivity"
            android:configChanges="orientation|screenSize" /> 
```

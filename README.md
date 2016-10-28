# `android.graphics.Path` working wrong on Android 6.0

Some `Path` displayed wrong on android 6.0 but on android 4.1 (and othes) all correct.

Next `Path` displayed incorrect:

``` java
mPath = new Path();
mPath.moveTo(77.35896f, 60.400444f);
mPath.cubicTo(77.35896f, 60.400444f, 79.225426f, 29.841496f, 45.79181f, 26.622204f);
mPath.cubicTo(17.59754f, 23.541723f, 12.924118f, 48.732895f, 12.924118f, 48.732895f);
mPath.cubicTo(5.9657674f, 87.16086f, 64.28567f, 132.59851f, 64.28567f, 132.59851f);
mPath.cubicTo(64.28567f, 132.59851f, 134.76442f, 110.88812f, 141.79378f, 72.06799f);
mPath.cubicTo(141.79378f, 72.06799f, 146.64627f, 46.909233f, 118.7662f, 39.836056f);
mPath.cubicTo(87.89501f, 31.411335f, 77.35896f, 60.400436f, 77.35896f, 60.400436f);
mPath.close();
```

## On Android 6.0 and Android 4.1

![Android 6.0](https://github.com/tepikin/Android6_bug_in_android.graphics.Path/blob/master/screenshots/android_6_short.png?raw=true)
![Android 4.1](https://github.com/tepikin/Android6_bug_in_android.graphics.Path/blob/master/screenshots/android_4_short.png?raw=true)

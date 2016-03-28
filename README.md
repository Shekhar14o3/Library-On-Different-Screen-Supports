# Library-On-Different-Screen-Supports
A library for supporting different screen resolutions. In this library you can find 17 different screen resolutions supports.

This library supports different screens resolutions. In this library I created the values folder for almost every screen 
resolutions, ranging from 1dp to 300dp. A sample project is also enclosed with it. The library name is supportdifferentscreen.
Different Screen Resolutions listed in this library are as:

01. sw-300dp
02. sw-330dp
03. sw-360dp
04. sw-390dp
05. sw-420dp
06. sw-450dp
07. sw-480dp
08. sw-510dp
09. sw-540dp
10. sw-570dp
11. sw-600dp
12. sw-630dp
13. sw-660dp
14. sw-690dp
15. sw-720dp
16. sw-750dp
17. sw-780dp

HOW TO USE:

In layout instead of hardcoding the value as android:paddingLeft="24dp", 
use it in this way android:paddingLeft="@dimen/_24dp"

In your build.gradle file, add this in your dependencies
  compile project(':supportdifferentscreens')

# CMakeUninstallFeedBackExample
new version of cmake ndk work for when android application uninstall open a browers to feedback. just work on 5.0- 

[![](https://www.jitpack.io/v/susyimes/CMakeUninstallFeedBackExample.svg)](https://www.jitpack.io/#susyimes/CMakeUninstallFeedBackExample)
# Usage 

#1
```
compile 'com.github.susyimes:CMakeUninstallFeedBackExample:1.0.0
```
#2

In Application Add

FeedbackUtils.openUrlWhenUninstall(context, "http://www.google.com");

# CMakeUninstallFeedBackExample
new version of cmake ndk work for when android application uninstall open a browers to feedback. just work on 5.0- 

[![](https://www.jitpack.io/v/susyimes/CMakeUninstallFeedBackExample.svg)](https://www.jitpack.io/#susyimes/CMakeUninstallFeedBackExample)
# Usage 


#1

Add to project build.gradle

```
allprojects {
    repositories {
        jcenter()
        maven { url 'https://www.jitpack.io' }
    }
}
```

#2

Add to app build.gradle

```
compile 'com.github.susyimes:CMakeUninstallFeedBackExample:1.0.0
```

#3

In Application Add

FeedbackUtils.openUrlWhenUninstall(context, "http://www.google.com");

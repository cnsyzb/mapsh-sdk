# mapsh-sdk
A custom layout component for Android

# 如何使用
Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:
```java
    allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```
Step 2. Add the dependency
```java
	dependencies {
	        compile 'com.github.cnsyzb:sdk:1.0.6'
	}
```
# 说明
##  如出现如下build错误
![](doc/build_error.png)
```java
android {

    configurations.all {
        resolutionStrategy.force 'com.google.code.findbugs:jsr305:3.0.1'
    }
}
```

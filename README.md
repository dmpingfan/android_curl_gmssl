# android-curl
so支持x86和v7a、arm64架构，模拟器和真机都可以运行。
通过openssl和mozilla根证书支持https。
独立的aar module，可以直接引入项目使用，结合app中的封装demo，可以快速集成进入项目中。
更多请见文档：https://www.jianshu.com/p/895a4e5052e2

keywords: android curl jni ndk https http gmsll

关键字：安卓 curl jni ndk https https gmsll

-----------------------------------------------------------------
[![](https://jitpack.io/v/liyuzhao/android_curl_gmssl.svg)](https://jitpack.io/#liyuzhao/android_curl_gmssl)


### Step 1.
Add it in your root build.gradle at the end of repositories:

```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

### Step 2.

```
dependencies {
	        implementation 'com.github.liyuzhao:android_curl_gmssl:1.0.0'
}
```


-----------------------------------------------------------------
<a href="https://996.icu"><img src="https://img.shields.io/badge/link-996.icu-red.svg" alt="996.icu"></a>

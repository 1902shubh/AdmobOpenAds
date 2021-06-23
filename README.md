[![Version](https://img.shields.io/badge/version-1.0.1-green.svg)](https://shields.io/)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# AdmobOpenAds
Implement admob open ads in your android app.<br/><br/>
 <img src="https://user-images.githubusercontent.com/46995327/122922701-8b862b80-d381-11eb-8431-4030ef740f81.jpg" width="250"  alt="DEMO"/>

# How to Implement
To get a Git project into your build:
> Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories: <br/>
```gradle
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```
    
> Step 2. Add the dependency

Add it in your root app.gradle at the end of repositories: <br/>
```gradle
dependencies {
	...
	implementation 'com.github.1902shubh:AdmobOpenAds:1.0.1'
	...
}
```

# How do I use Admob open Ads
Simple use cases will look something like this:
> Step 1. Create a class like MyApplication.class <br/>
```java
new AppOpenManager(context, "ADMOB_OPEN_ADS_ID");
```
> Step 2. Update menifest
```xml
<application 
	name=".MyApplication"
	...
>
```

## Made with :sparkling_heart: [Papaya Coders](https://papayacoders.in/)

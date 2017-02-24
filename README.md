![Image](/asdpbanner.png)

# ASDP - a scalable size unit by Adhish

You must be developing app for that Android device in your pocket but wait, what happens when you try to run the same code on tablet or an Android mobile phone of different size or say an Android TV? Boom! The dimensions messes up. :tired_face:

So, here is the solution to your problem! :innocent:

This is a very simple library which works with your sp and dp values for almost all Android devices. All you need to do is install this library into your project and call it with your sp (Example : 10sp) or dp (Example : 10dp). Once you specify this according to this libary, the layouts will automatically adjust itself according to the devices! :open_mouth:

Don't believe me? Here is the screenshots on Android TV, Nexus 5x and Nexus One :relieved:

![Image](/screens.png)

### Installing

1) Add it in your root build.gradle at the end of repositories:
```
	allprojects {
		repositories {
			...
			maven { url 'https://www.jitpack.io' }
		}
	}
```

2) Step 2. Add the dependency
```
	dependencies {
	        compile 'com.github.adhishlal:asdp:1.1'
	}
```
And it's done. Just give the dimensions as ````@dimen/_<your value>asdp```` and it will take the sizes automatically!

### Example
```
        <TextView
            android:id="@+id/tvExample"
            android:layout_width="@dimen/_50asdp"
            android:layout_centerInParent="true"
            android:layout_margin="@dimen/_5asdp"
            android:layout_height="@dimen/_50asdp"
            android:layout_gravity="center" />
```

### Show Some :heart:
[![GitHub stars](https://img.shields.io/github/stars/badges/shields.svg?style=social&label=Star)](https://github.com/adhishlal/asdp)
[![GitHub forks](https://img.shields.io/github/forks/badges/shields.svg?style=social&label=Fork)](https://github.com/adhishlal/asdp/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/badges/shields.svg?style=social&label=Watch)](https://github.com/adhishlal/asdp) 
[![GitHub followers](https://img.shields.io/github/followers/espadrine.svg?style=social&label=Follow)](https://github.com/adhishlal/)
[![Twitter Follow](https://img.shields.io/twitter/follow/espadrine.svg?style=social&label=Follow)](https://twitter.com/er_adhish)

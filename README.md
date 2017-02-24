![Image](/asdpbanner.png)

# ASDP - a scalable size unit by Adhish

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

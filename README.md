# intentanimation
animation between activities
**Intent animations**
===================

### It`s top animations between activities.

## **Usage** ##
![image](https://image.ibb.co/kGHZSn/ezgif_com_video_to_gif_1.gif)

[![Android Arsenal]( https://img.shields.io/badge/Android%20Arsenal-Intent%20animations-green.svg?style=flat )]( https://android-arsenal.com/details/1/6816 )


**Gradle**

    allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

    dependencies {
         compile 'com.github.hajiyevelnur92:intentanimation:1.0'
    }



#### **Code**
```java

import static maes.tech.intentanim.CustomIntent.customType;
//MainActivity or any activity name
protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        //.....//
        
        //here is library
        customType(MainActivity.this,"here is string name");
}
        
*left-to-right
*right-to-left
*bottom-to-up
*up-to-bottom
*fadein-to-fadeout
*rotateout-to-rotatein
```

### [License](./LICENSE)

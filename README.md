arcgisSampleAndroidStudio
=========================


What is this?
-------------

It is a basic application that integrates the free version of ArcGIS android sdk with gradle (Tested on Android Studio)


What happened to the. So? 
-------------------------

They have been compressed to libs.jar. 

 
```java
    libs.jar files structure:
    
    lib/armeabi/ibruntimecore_java.so
    lib/armeabi-v7a/ibruntimecore_java.so
    lib/x86/ibruntimecore_java.so
```

You can use **generateNativeLib**  gradle custom task to generate *libs.jar* again.


Example
-------

![Alt text](/test.png?raw=true "Example")



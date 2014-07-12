AdMobANE Version 1.6.0 Packages
=========

##Setup for Android

Update Your Application Descriptor

You'll need to be using the AIR 3.1 SDK or higher, include the extension in your Application Descriptor XML, and update the Android Manifest Additions with additional settings.

Add the following settings in <manifest> tag.
```xml
<uses-permission android:name="android.permission.INTERNET" />
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
```

Add the following settings in <application> tag.
```xml
<meta-data android:name="com.google.android.gms.version" android:value="4452000"/>
<activity android:name="com.google.android.gms.ads.AdActivity" android:configChanges="keyboard|keyboardHidden|orientation|screenLayout|uiMode|screenSize|smallestScreenSize" />
```

<?xml version="1.0" encoding="utf-8" ?> 
<manifest xmlns:android="http://schemas.android.com/apk/res/android" android:compileSdkVersion="31" android:compileSdkVersionCodename="12" android:installLocation="auto" android:versionCode="1000000" android:versionName="1.0.0" package="aviator.predictor.programm" platformBuildVersionCode="31" platformBuildVersionName="12">
	<uses-sdk android:minSdkVersion="21" android:targetSdkVersion="31" />
	<uses-permission android:name="android.permission.BLUETOOTH" />
	<uses-feature android:glEsVersion="0x20000" android:required="true" />
	<uses-permission android:name="android.permission.INTERNET" />
	<uses-feature android:name="android.hardware.touchscreen" android:required="false" />
	<uses-feature android:name="android.software.leanback" android:required="false" />
	<supports-screens android:largeScreens="true" android:resizeable="true" />
	<application android:allowBackup="false" android:appComponentFactory="androidx.core.app.CoreComponentFactory" android:banner="@drawable/banner" android:icon="@drawable/icon" android:isGame="true" android:label="@string/app_name" android:name="aviator.predictor.programm.RunnerApplication">
		<activity android:alwaysRetainTaskState="true" android:configChanges="density|fontScale|keyboard|keyboardHidden|layoutDirection|locale|mcc|mnc|navigation|orientation|screenLayout|screenSize|smallestScreenSize|touchscreen|uiMode" android:exported="true" android:label="@string/app_name" android:launchMode="singleTask" android:name="aviator.predictor.programm.RunnerActivity" android:theme="@android:style/Theme.NoTitleBar.Fullscreen">
			<intent-filter>
				<action android:name="android.intent.action.MAIN" />
				<category android:name="android.intent.category.LAUNCHER" />
				<category android:name="android.intent.category.LEANBACK_LAUNCHER" />
			</intent-filter>
		</activity>
		<meta-data android:name="xperiaplayoptimized_content" android:resource="@string/xperiaplayoptimized_content" />
		<meta-data android:name="game_display_name" android:resource="@string/app_name" />
		<meta-data android:name="YYiCadeSupport" android:value="true" />
		<meta-data android:name="UseShaders" android:value="false" />
		<meta-data android:name="YYUse24Bit" android:value="1" />
		<meta-data android:name="OrientLandscape" android:value="0" />
		<meta-data android:name="OrientPortrait" android:value="-1" />
		<meta-data android:name="OrientLandscapeFlipped" android:value="0" />
		<meta-data android:name="OrientPortraitFlipped" android:value="0" />
		<meta-data android:name="SplashscreenTime" android:value="0" />
		<meta-data android:name="SleepTimer" android:value="4" />
		<meta-data android:name="SplashscreenFill" android:value="0" />
		<meta-data android:name="YYLaunchScreenBackgroundColour" android:value="255" />
		<meta-data android:name="IsBuiltAsYoYoRunner" android:value="Yes" />
		<meta-data android:name="YYNumExtensionClasses" android:value="0" />
		<provider android:authorities="aviator.predictor.programm.androidx-startup" android:exported="false" android:name="androidx.startup.InitializationProvider">
			<meta-data android:name="androidx.emoji2.text.EmojiCompatInitializer" android:value="androidx.startup" />
			<meta-data android:name="androidx.lifecycle.ProcessLifecycleInitializer" android:value="androidx.startup" />

# VisualStudioForMac

下载链接: https://pan.baidu.com/s/1o88kSEA 密码: fxjk

资源：
* MonoFramework-MDK-4.8.0.344.macos10.xamarin.universal.pkg
* VisualStudioForMac-Preview1-7.0.0.347.dmg
* VisualStudioforMacPreviewInstaller.dmg
* xamarin.android-7.1.0-2.pkg
* xamarin.ios-10.4.0.20.pkg
* xamarin.mac-3.0.0.290.pkg


＃Help

It was not possible to complete an automatic installation. This might be due to a problem with your network, proxy servers or an unsolvable installation conflict. At this point, you can continue the installation by manually downloading and installing the independent pieces. The list below shows each component that you need to install.

## Mono Framework

Download the [Mono Framework v4.8.0 archive](https://dl.xamarin.com/MonoFrameworkMDK/Macx86/MonoFramework-MDK-4.8.0.344.macos10.xamarin.universal.pkg) to any directory on your disk, double-click it and follow the instructions on screen. Please accept all the defaults during the installation, including the target drive.

## Java SDK

Mac OS X uses its own version of Java and in order to install it you need to [start the terminal app](run://localhost/usr/bin/open?-a&Terminal) and type the following command:

`javac -version`

After typing it you should see a Mac OS X system popup which will guide you to install the Java software.

## Android SDK

Download the [Android SDK for Mac OS X version 24.4.1](http://dl.google.com/android/android-sdk_r24.4.1-macosx.zip), open the downloaded archive and copy the contents of the folder found at its root directory (most probably named android-sdk-macosx) to the /Users/xxx/Library/Developer/Xamarin/android-sdk-macosx directory.

[Click here](run://localhost/Users/xxx/Library/Developer/Xamarin/android-sdk-macosx/tools/android?sdk) in order to start the Android SDK Manager application. In the GUI make sure the following components are installed or selected for installation:

* Android SDK Tools
* Android SDK Platform-tools
* Android SDK Build-tools
* Android API 15
* Android API 19
* Android API 21

Once all the required components are selected (you can select others as well, if you wish) start the installation.


##### If you cannot see /Users/xxx/Library/Developer/Xamarin/android-sdk-macosx in Finder please [click here](fileopen:/Users/xxx/Library/Developer/Xamarin/android-sdk-macosx?dir=1) to reveal the directory in Finder.


Download the [Android NDK for Mac OS X version r10e](http://dl.google.com/android/ndk/android-ndk-r10e-darwin-x86_64.bin), open the downloaded archive and copy the contents of its root directory (most probably named android-ndk-r10e) to the /Users/hcp/Library/Developer/Xamarin/android-ndk directory.

When the Android SDK installation is finished you might want to start the [Android Emulator Manager](run://localhost/Users/hcp/Library/Developer/Xamarin/android-sdk-macosx/tools/android?avd) and create as many emulator images as you might need for your development. This step can be performed at any time, on an as-needed basis.

## Visual Studio for Mac Preview

Download the [Visual Studio for Mac Preview v7.0.0 archive](https://dl.xamarin.com/VsMac/VisualStudioForMac-Preview1-7.0.0.347.dmg) to any directory on your disk, double-click it and then drag and drop the Visual Studio for Mac Preview icon to the Applications folder.

## Xamarin.Android

Download the [Xamarin.Android v7.1.0 archive](https://dl.xamarin.com/MonoforAndroid/Mac/xamarin.android-7.1.0-2.pkg) to any directory on your disk, double-click it and follow the instructions on screen. Please accept all the defaults during the installation, including the target drive.

## Xamarin.iOS

Download the [Xamarin.iOS v10.4.0 archive](https://dl.xamarin.com/MonoTouch/Mac/xamarin.ios-10.4.0.20.pkg) to any directory on your disk, double-click it and follow the instructions on screen. Please accept all the defaults during the installation, including the target drive.

## Xamarin.Mac

Download the [Xamarin.Mac v3.0.0 archive](https://dl.xamarin.com/XamarinforMac/Mac/xamarin.mac-3.0.0.290.pkg) to any directory on your disk, double-click it and follow the instructions on screen. Please accept all the defaults during the installation, including the target drive.

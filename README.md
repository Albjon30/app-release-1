# app-release

App Icon

-> Icon Generator https://www.appicon.co/
-> Import https://pub.dev/packages/flutter_launcher_icons 

Update App Name

#IOS
->info.plist -> <key>CFBundleDisplayName

Splash Screen

->https://docs.flutter.dev/platform-integration/android/splash-screen
#IOS
-> open ios > Runner.xcworkspace > LaunchScreen.storyboard
-> assets > launchimage > palce 3 screens from figma(1x,2x,3x)
#ANDROID
-> genrate images https://stackoverflow.com/questions/28507609/image-resolution-for-mdpi-hdpi-xhdpi-and-xxhdpi
-> android/app/src/main/res place all 4 images in to the folders
-> search for android:windowBackground change (@drwable) to @mipmap/slpash.svg

Sending IOS to APP Store
-> bundle the app on .ipa file
-> go to https://appstoreconnect.apple.com
-> create new app > BundleID (get it fromappstore developer)
-> open the new created app and get screenshots of the app
-> change App Inforamtion
-> support url (important get more info about app) place a text and use on your website
-> in xcode archive the app, if(error pod) in terminal of the app run => pod deintegrate (then) => pod install
to reinstall an rerun runner
-> remove all pods from project ![image](https://github.com/user-attachments/assets/e68016a1-cf5f-453f-b255-258841ef0fcc)


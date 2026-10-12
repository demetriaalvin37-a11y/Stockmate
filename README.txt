STOCKMATE ANDROID PROJECT
This is an Android Studio project source package, not a compiled APK yet.

HOW TO BUILD THE APK:
1. Install Android Studio on a computer.
2. Extract StockMateAndroid.zip.
3. In Android Studio choose Open, then select the extracted StockMateAndroid folder.
4. Allow Gradle sync and install any requested Android SDK (API 35).
5. From the menu choose Build > Build Bundle(s) / APK(s) > Build APK(s).
6. When finished, choose Locate. The debug APK is normally in:
   app/build/outputs/apk/debug/app-debug.apk
7. Transfer that APK to your Android phone and open it to install.
   You may need to allow installation from that file manager.

The app is a student demo prototype. Inventory data is stored locally in the app's WebView storage on that device. It does not sync between devices or use an online database.

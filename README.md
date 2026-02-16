# commandandroid
uniinstall playstore
adb shell pm uninstall -k --user 0 com.android.vending
adb shell cmd package install-existing com.android.vending

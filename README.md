# commandandroid
uniinstall playstore
adb shell pm uninstall -k --user 0 com.android.vending
 
adb shell cmd package install-existing com.android.vending


uniinstall broswer
adb shell pm uninstall -k --user 0 org.lineageos.jelly

adb shell cmd package install-existing org.lineageos.jelly

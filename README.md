# commandandroid
uniinstall playstore

adb shell pm uninstall -k --user 0 com.android.vending
 
adb shell cmd package install-existing com.android.vending

-

uniinstall broswer

adb shell pm uninstall -k --user 0 org.lineageos.jelly

adb shell cmd package install-existing org.lineageos.jelly


adb shell pm uninstall -k --user 0 org.lineageos.audiofx
adb shell pm uninstall -k --user 0 com.android.inputmethod.latin
adb shell pm uninstall -k --user 0 com.android.calculator2
adb shell pm uninstall -k --user 0 com.android.calendar
adb shell pm uninstall -k --user 0 org.lineageos.snap
adb shell pm uninstall -k --user 0 com.android.contacts
adb shell pm uninstall -k --user 0 com.android.email
adb shell pm uninstall -k --user 0 com.android.documentsui
adb shell pm uninstall -k --user 0 com.android.gallery3d
adb shell pm uninstall -k --user 0 com.google.android.partnersetup
adb shell pm uninstall -k --user 0 com.android.messaging
adb shell pm uninstall -k --user 0 org.lineageos.eleven
adb shell pm uninstall -k --user 0 com.android.dialer
adb shell pm uninstall -k --user 0 com.google.android.tts
adb shell pm uninstall -k --user 0 org.lineageos.trebuchet


adb shell cmd package install-existing org.lineageos.audiofx
adb shell cmd package install-existing com.android.inputmethod.latin
adb shell cmd package install-existing com.android.calculator2
adb shell cmd package install-existing com.android.calendar
adb shell cmd package install-existing org.lineageos.snap
adb shell cmd package install-existing com.android.contacts
adb shell cmd package install-existing com.android.email
adb shell cmd package install-existing com.android.documentsui
adb shell cmd package install-existing com.android.gallery3d
adb shell cmd package install-existing com.google.android.partnersetup
adb shell cmd package install-existing com.android.messaging
adb shell cmd package install-existing org.lineageos.eleven
adb shell cmd package install-existing com.android.dialer
adb shell cmd package install-existing com.google.android.tts
adb shell cmd package install-existing org.lineageos.trebuchet

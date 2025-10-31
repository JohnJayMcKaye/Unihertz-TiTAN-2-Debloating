Install ADB and activate USB-Debuging

Uninstall with

adb shell pm uninstall --user 0 com.google.android.apps.youtube.music 
adb shell pm uninstall --user 0 com.google.android.youtube 
adb shell pm uninstall --user 0 com.google.android.overlay.gmsconfig.personalsafety
adb shell pm uninstall --user 0 com.google.android.keep
adb shell pm uninstall --user 0 com.google.android.apps.adm
adb shell pm uninstall --user 0 com.google.android.apps.tachyon
adb shell pm uninstall --user 0 com.google.android.feedback
adb shell pm uninstall --user 0 com.google.android.adservices.api
adb shell pm uninstall --user 0 com.google.android.calendar
adb shell pm uninstall --user 0 com.google.android.gms.supervision
adb shell pm uninstall --user 0 com.google.android.gms.location.history
adb shell pm uninstall --user 0 com.google.android.videos
adb shell pm uninstall --user 0 com.android.vending
adb shell pm uninstall --user 0 com.google.android.gm
adb shell pm uninstall --user 0 com.google.android.apps.photos
adb shell pm uninstall --user 0 com.google.android.apps.nbu.files
adb shell pm uninstall --user 0 com.google.android.apps.docs
adb shell pm uninstall --user 0 com.android.chrome
adb shell pm uninstall --user 0 com.agui.studentmodel


adb shell pm uninstall --user 0 com.agui.game #for testing

Reinstall with

adb shell cmd package install-existing com.google.android.apps.youtube.music 
adb shell cmd package install-existing com.google.android.youtube 
adb shell cmd package install-existing com.google.android.overlay.gmsconfig.personalsafety
adb shell cmd package install-existing com.google.android.keep
adb shell cmd package install-existing com.google.android.apps.adm
adb shell cmd package install-existing com.google.android.apps.tachyon
adb shell cmd package install-existing com.google.android.feedback
adb shell cmd package install-existing com.google.android.adservices.api
adb shell cmd package install-existing com.google.android.calendar
adb shell cmd package install-existing com.google.android.gms.supervision
adb shell cmd package install-existing com.google.android.gms.location.history
adb shell cmd package install-existing com.google.android.videos
adb shell cmd package install-existing com.android.vending
adb shell cmd package install-existing com.google.android.gm
adb shell cmd package install-existing com.google.android.apps.photos
adb shell cmd package install-existing com.google.android.apps.nbu.files
adb shell cmd package install-existing com.google.android.apps.docs
adb shell cmd package install-existing com.android.chrome
adb shell cmd package install-existing com.agui.studentmodel
adb shell cmd package install-existing com.agui.game



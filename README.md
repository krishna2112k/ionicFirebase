ionic cordova plugin remove cordova-plugin-firebase
<br/>
ionic cordova plugin add https://github.com/dpa99c/cordova-plugin-firebase#GH-1057-April-05-android-build-issue
<br/>
ionic cordova plugin add cordova-plugin-android-adapter
<br/>
ionic cordova plugin add cordova-plugin-androidx-adapter
<br/>
ionic cordova platform rm android
<br/>
ionic cordova platform add android@8.0.0
<br/>
This has solved my issues for today, most likely because it uses an older version of the firebase plugin


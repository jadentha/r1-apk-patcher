# r1-apk-patcher
tool to patch a clean rabbit apk into a working one

how to run:
1. set important stuff in index.js (top of the file)
2. run `npm i` in the project directory
3. finally run `node index.js`
4. done

to run the apk you need to execute this command first (adb): `adb shell pm grant tech.rabbit.r1launcher.r1 android.permission.WRITE_SECURE_SETTINGS` or in termux `pm grant tech.rabbit.r1launcher.r1 android.permission.WRITE_SECURE_SETTINGS`

the patcher won't work (atleast for now) with the newest apk version because of the activity where you need to choose cellular or wifi. This can be worked around if you install an older apk first, do the setup, and then update to the latest version.
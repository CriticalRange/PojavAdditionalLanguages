## Adding additional language to PojavLauncher

### Getting the files

* In order to get the files please turn on "desktop site" on your browser (location depends on the browser you are using)

For example: for Chrome, click the 3 dots on top-right and slide down to find it.

* After enabling "desktop site", click to "Code" and in the opened menu click to "Download ZIP".

It should take seconds to install if you have a decent internet speed (because it's almost 1MB)

* Now open your favourite file explorer and browse into ```/sdcard/Downloads``` (NOTE: This isn't an SD card location, internal storage on Android is named like this) (Also, in some explorers you might just need to click "Internal Storage") 

You should be able to find ```PojavAdditionalLanguages-main.zip``` file

* Hold it and select "extract" (again, depends on the explorer)

After the extraction completes, you should have the strings

### Now it's time for APKEditor!

* You can download it from [here](https://s1.rexdl.com/android/app/APK-Editor-Pro-1.10.0-20210718-Mod-Light-Arm64-v8a-www.ReXdl.com.apk)

> How reliable is the APK ?

Very reliable. If you don't believe me you can [virustotal](https://virustotal.com) it.

After you install it via your file explorer (which redirects to package installer) now you can open it.

## Importing the strings to PojavLauncher via APKEditor

* Open APKEditor

* Select "Select Apk from App"

* Find PojavLauncher in the app list

* Click it, select "Full Edit (RESOURCE RE-BUILD)

then "All Files"

* Select "Files" from bottom bar and wait for it to load

* After it loads, go to ```res```

slide down and select "values"

slide a bit more and hold "strings.xml"

Click "Replace"

In the pop-up menu go to ```Downloads``` 

then ```PojavAdditionalLanguages-main``` 

after that ```PojavAdditionalLanguages-main``` again

then select the language folder you want to use, i will go for "UpsideDown"

after that ```values```

And finally select ```strings.xml```

It should say ```successful```

If your device is in English language do the same thing for values-en folder (as I said in [README.md](/README.md), this configuration does **not** change your device language, it only changes PojavLauncher's language)

### If your device is not in English:

* But if you are using your device as ,for example, Finnish then do these:

* Go to [this link](https://www.science.co.il/language/Locale-codes.php) and find your language's language code

* After you find it go back to APKEditor, (you should still be in values folder, press back once) go to folder that has the name (values-your language code) (for example: values-fi)

* Then hold the ```strings.xml``` file and select ```replace```

* In the pop-up menu, go back using the ```..``` and select ```values-en```

* Select the ```strings.xml``` for the final time and no more replacing needed

* Finally, click to "Build" that is on top-right corner and wait

After it says success press "Install" and install the app

You should see the changes right away!

# CONGRATULATIONS!

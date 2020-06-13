## Building 2BA revamped
THIS ONLY WORKS IN LINX! (maybe mac, I dont know) I don't plan on making a windows version. you can use WsL (Linux subsystem for windows) if you are on windows...
oh oops, its is Windows Subsystem for Linux, I forgot microsoft thinks backwords :D .

you will have to provide your own system img luckly I have a download link for them ;)

[Android File host](https://www.androidfilehost.com/?w=files&flid=312816)

# downlowing instructions

```
git clone https://github.com/ANDROID2468/2BA_revamped_make.git

cd 2BA_revamped_make
```
place system.img into 2BA_revamped_make folder

## Building instructions 

run this commmand:
```
./make.sh 
```
or 
(for adb on boot)
```
./make.sh dev
```

# stuff 

```

## open KnockON settings menu using ADB

To run, type this in terminal/cmd:
```
adb shell am start -n com.android.settings/com.android.settings.Settings'$\'KnockONSettingsActivity
```
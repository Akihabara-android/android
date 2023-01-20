**English｜[中文](https://github.com/Akihabara-open/android/blob/Tulip/README_CN.md)**
# Akihabara

### To sync
Make sure you have become an official Akihabara maintainer before sync   
If you are interested in becoming an official maintainer of Akihabara, please apply in the [charter](https://github.com/Akihabara-open/charter)!   
please use credential.helper to sync
```
repo init -u https://github.com/Akihabara-open/android.git -b Tulip
```
Then to sync up:
```
repo sync
```

### To Build
---------------

```
. build/envsetup.sh
lunch akihabara_$device-userdebug
mka bacon
```

**[English](https://github.com/Akihabara-open/android/blob/Tulip/README.md)｜中文**
# Akihabara

### 同步源码
在同步前请确保你已经成为Akihabara的官方维护者  
如果您有意向成为我们的官方维护者，请前往[charter](https://github.com/Akihabara-open/charter)仓库进行申请！  
请使用credential.helper来进行同步源码
```
repo init -u https://github.com/Akihabara-open/android.git -b Tulip
repo sync
```

### 开始编译
```
. build/envsetup.sh
lunch akihabara_$device-userdebug
mka bacon
```
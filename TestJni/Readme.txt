========================================================================================
Time : 2016-08-25-13-50
Branch : l18321G_git
commit 8c3f81f054c8fe0379f58e7f01ae7b2f4014093a
Author: zhangjian <zhangj@szroco.com>
Date:   Thu Aug 25 13:49:39 2016 +0800

    Test: Jni
Mod:  device/mediatek/common/device.mk
Mod:  device/mediatek/common/sepolicy/device.te
Mod:  device/mediatek/common/sepolicy/file_contexts
Mod:  device/mediatek/common/sepolicy/system_server.te
Mod:  device/mediatek/mt6580/device.mk
Add:  external/freg/Android.mk
Add:  external/freg/freg.c
Mod:  external/sepolicy/service_contexts
Mod:  frameworks/base/Android.mk
Add:  frameworks/base/core/java/android/os/IFregService.aidl
Add:  frameworks/base/services/core/java/com/android/server/FregService.java
Mod:  frameworks/base/services/core/jni/Android.mk
Add:  frameworks/base/services/core/jni/com_android_server_FregService.cpp
Mod:  frameworks/base/services/core/jni/onload.cpp
Mod:  frameworks/base/services/java/com/android/server/SystemServer.java
Add:  hardware/libhardware/include/hardware/freg.h
Mod:  hardware/libhardware/modules/Android.mk
Add:  hardware/libhardware/modules/freg/Android.mk
Add:  hardware/libhardware/modules/freg/freg.cpp
Mod:  kernel-3.10/arch/arm/Kconfig
Mod:  kernel-3.10/drivers/Makefile
Add:  kernel-3.10/drivers/freg/Kconfig
Add:  kernel-3.10/drivers/freg/Makefile
Add:  kernel-3.10/drivers/freg/freg.c
Add:  kernel-3.10/drivers/freg/freg.h
Add:  packages/apps/Freg/Android.mk
Add:  packages/apps/Freg/AndroidManifest.xml
Add:  packages/apps/Freg/res/drawable/icon.png
Add:  packages/apps/Freg/res/layout/main.xml
Add:  packages/apps/Freg/res/values/strings.xml
Add:  packages/apps/Freg/src/shy/luo/freg/Freg.java
Mod:  system/core/rootdir/ueventd.rc

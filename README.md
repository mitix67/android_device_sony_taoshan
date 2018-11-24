Copyright 2015 - The CyanogenMod Project  
Copyright 2017-18 - The LineageOS Project  

Sony Xperia L
==============

The Sony Xperia L (codenamed _"Taoshan"_) is a mid-range smartphone from Sony Mobile.

It was announced in March 2013.

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | 1.0GHz Dual-Core MSM8230
GPU     | Adreno 305
Memory  | 1GB RAM
Shipped Android Version | 4.1.2
Storage | 8GB
Battery | 1750 mAh
Display | 4.3" 854 x 480 px
Camera  | 8MPx, LED Flash

![Sony Xperia L](http://cdn2.gsmarena.com/vv/pics/sony/sony-xperia-l-01.jpg "Sony Xperia L in black")

This branch is for building LineageOS 16.0 (or Android Pie 9.0 AOSP based) ROMS.

How to build:
Initialize repo:

    repo init -u git://github.com/LineageOS/android.git -b lineage-16.0
    curl --create-dirs -L -o .repo/local_manifests/manifest_sony_taoshan.xml -O -L https://gist.githubusercontent.com/mitix67/04601063b8db019a6fd77846ebc17fad/raw/782eba4fe0dbe8e0be39418860bd9ff857487b86/manifest_sony_taoshan.xml
    repo sync

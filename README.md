# Unoffcial CrDroid OTA update #

> Fork from [CrDroid](https://github.com/crdroidandroid/android_vendor_crDroidOTA)

![crDroid-Custom-ROM-Logo](https://user-images.githubusercontent.com/93985232/170225142-a35db9ff-1427-4256-859c-14b255502c50.png)

> You can find all updates, news and instructions in my [telegram channel](https://t.me/microRozetka_hub)

## Creating json ##

We put create json.sh to the home folder with your source code. Example: ~/android/crdroidx.x

Then make the file executable:
```
chmod +x createjson.sh
```
After that, run it:
```
./createjson.sh
```

Get the devicename output.json, mission accomplished!

## Automatic uploading using a script

If you decide to use automatic loading, you will need to run the script `auto_createjson_x.x.sh` using source.

Example: `source auto_createjson_8.x.sh`

You will also need to change the row data:

[The first line](https://github.com/microRozetka/micro-files/blob/c2bd37441ed500d8a9286b9ef3d1547a2af256d7/auto_createjson_9.x.sh#L3) | [Second line](https://github.com/microRozetka/micro-files/blob/c2bd37441ed500d8a9286b9ef3d1547a2af256d7/auto_createjson_9.x.sh#L4) | [The third line](https://github.com/microRozetka/micro-files/blob/c2bd37441ed500d8a9286b9ef3d1547a2af256d7/auto_createjson_9.x.sh#L75)

The description of each line is present in the script.

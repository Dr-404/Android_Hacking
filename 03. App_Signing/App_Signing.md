# Application Signing 



## Decompile Application 

`apktool d test.apk`

## Patching with Smali code

## Creating Key Store

## Zipalign Application 
```bash
zipalign -v 4 ./app.apk app_mod.apk
```
## Signing
```bash
apksigner sign -ks keystoreLocation --ks-key-alias KeyAliasName ./app_mod.apk
```

Exmaple Command


```bash
apksigner sign -ks ~/android-app-hack.keystore --ks-key-alias D47K ./spacepeng_mod.apk
```
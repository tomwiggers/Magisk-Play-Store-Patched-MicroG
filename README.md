# Play Store Patched MicroG

This is a patched version of the Google Play store.

_AS OF NOW THIS REPO ONLY CONTAINS THE ARM64 VERSION AND DOES NOT VERIFY ANYTHING. SO DO NOT FLASH IT IF YOU DO NOT HAVE AN ARM64 CPU._

## Current version

`13.8.16-all [PR] 235060107`


## Credits

Credits for the Patched Play Store go to SHADOW53: https://shadow53.com/android/no-gapps/setup-guide

At least, that is where I got it from, this Magisk module is based on the patched Play Store zip from there.


## How to install?

Download this git repo, and zip the folders. You cannot download this repo as zip and flash that zip because then the folder structure is incorrect. The zip contents must look like this:
```
ZIP
---> META-INF
---> system
---> module.prop
---> readme.md
```

If download this repo as zip from Github it will be as follows (incorrect and Magisk will throw an error):
```
ZIP
---> Magisk-Play-Store-Patched-MicroG-master
     ---> META-INF
     ---> system
     ---> module.prop
     ---> README.md
```

When you have the zip, oopy it to your phone, and in Magisk manager go to Modules -> tap on the + symbol and select the zip.
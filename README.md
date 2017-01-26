AOSP-CAF with OMS for Oneplus2
===========

To initialize your local repository using the AOSP-CAF trees, use a 
command like this:
````bash
repo init -u git://github.com/aosp-oneplus2/manifest.git -b n-mr1
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
source build/envsetup.sh
lunch aosp_oneplus2
make otapackage -jxx
```

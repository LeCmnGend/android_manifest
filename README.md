-----------------------------------------------------------------------------

<p align="center">
 <img src="https://github.com/SuperiorOS/manifest/blob/eleven/superior.png" > 
</p>

-----------------------------------------------------------------------------
Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**CrDroidOS**](https://github.com/crdroidandroid)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**Pixys OS**](https://github.com/PixysOS)
 * [**Syberia OS**](https://github.com/syberia-project)
 * [**Nitrogen OS**](https://github.com/nitrogen-project)

-----------------------------------------------------------------------------

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u https://github.com/LeCmnGend/android_manifest.git -b super-R --depth=1 --git-lfs
```

Then to sync up:-
================

```bash
    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

Start the build:-
=================

```bash
  . build/envsetup.sh
  lunch superior_<devicecodename>-userdebug
  make bacon -jx (where x is number of process)
```
-----------------------------------------------------------------------------

Some Links:-
============
* [**Telegram Public Chat**](https://t.me/superioros)
* [**Telegram Channel**](https://t.me/superior_os)
* [**Crowdin**](https://translations.superioros.org)
----------------------------------------------------------------------------

Download Stats
==============

[![Download Superior](https://img.shields.io/sourceforge/dd/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)

[![Download Superior](https://img.shields.io/sourceforge/dw/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)

[![Download Superior](https://img.shields.io/sourceforge/dm/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)

[![Download Superior](https://img.shields.io/sourceforge/dt/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)
---------------------------------------------------------------------------------

# JAVA OS #
<p align="center">
<a href="https://t.me/realme8indonesia"><img src="https://img.shields.io/badge/Telegram-Chat-blue?style=popout-square"></a>
</p>

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/JavaneseOS/manifest -b 11

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch java_$device-userdebug

# Build the code
$ mka bacon -j$(nproc --all)
```

---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**POSP**](https://github.com/PotatoProject)
 * [**LegionOS**](https://github.com/Project-LegionOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**BiancaProject**](https://github.com/BiancaProject)

---------------------------------------------------------------------------------------

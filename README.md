# VoidUI Andromeda - Beta - Mondrian (Poco F5 Pro Edition) #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/VoidUI-Andromeda/manifest -b aosp-13

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

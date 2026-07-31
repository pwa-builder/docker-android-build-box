# Repo is archived

PWABuilder no longer uses this fork of the Android Build Box. Instead, PWABuilder uses its own [custom Docker container](https://github.com/pwa-builder/PWABuilder/blob/19c2b03e9fe7007558675f512ea5f83e34f56386/apps/pwabuilder-google-play/Dockerfile). Thus, we're archiving this repo as it's no longer in use.

# Docker TWA Android Build Box

A docker container with the latest Android build tools / SDK installed. Used as a base image for https://github.com/pwa-builder/CloudAPK


## Build

```
docker buildx build --target minimal-plus -t android-build-box .  
```


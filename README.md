# Docker TWA Android Build Box

A docker container with the latest Android build tools / SDK installed. Used as a base image for https://github.com/pwa-builder/CloudAPK


## Build

```
docker buildx build --target minimal-plus -t android-build-box .  
```


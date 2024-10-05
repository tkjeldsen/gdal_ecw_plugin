# ECW plugin for ubuntu gdal

Create a deb package and copy the build artifact to the host system

```
docker buildx build -f Dockerfile.ubuntu2204 --target=artifact --output type=local,dest=$(pwd) .
```

## Ubuntu 22.04

The plugin `gdal_ECW_JP2ECW.so` is located in `/usr/lib/gdalplugins`.

## Ubuntu 24.04

The plugin `gdal_ECW_JP2ECW.so` is located in `/usr/lib/x86_64-linux-gnu/`gdalplugins.

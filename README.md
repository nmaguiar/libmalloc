# libmalloc

Binaries Linux builds of the libtcmalloc, libjemalloc and the libmimalloc libraries.

## Download

First you will need to choose the appropriate tar.gz to download. List of ditributions and corresponding tar.gz suffix to use:

| Linux distribution | Architecture | Suffix tar.gz | Download URL |
|---|---|---|---|
| Alpine 3.x | x64 | alpine-x64 | [libjemalloc-5.3.0-alpine-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-alpine-x64.tar.gz)<br /> [libtcmalloc-4.6.0-alpine-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.6.0-alpine-x64.tar.gz)<br /> [libmimalloc-2.2-alpine-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-alpine-x64.tar.gz) |
| Alpine 3.x | aarch64 | alpine-aarch64 | [libjemalloc-5.3.0-alpine-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-alpine-aarch64.tar.gz)<br />[libtcmalloc-4.6.0-alpine-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.6.0-alpine-aarch64.tar.gz)<br /> [libmimalloc-2.2-alpine-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-alpine-aarch64.tar.gz) |
| RHEL 7.x | x64 | redhat7-x64 | [libjemalloc-5.3.0-redhat7-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-redhat7-x64.tar.gz) |
| RHEL 8.x | x64 | redhat8-x64 | [libjemalloc-5.3.0-redhat8-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-redhat8-x64.tar.gz)<br /> [libtcmalloc-4.7.0-redhat8-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.7.0-redhat8-x64.tar.gz)<br /> [libmimalloc-2.2-redhat8-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-redhat8-x64.tar.gz) |
| RHEL 8.x | aarch64 | redhat8-aarch64 | [libjemalloc-5.3.0-redhat8-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-redhat8-aarch64.tar.gz)<br /> [libtcmalloc-4.6.0-redhat8-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.6.0-redhat8-aarch64.tar.gz)<br /> [libmimalloc-2.2-redhat8-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-redhat8-aarch64.tar.gz) |
| RHEL 9.x | x64 | redhat9-x64 | [libjemalloc-5.3.0-redhat9-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-redhat9-x64.tar.gz)<br /> [libtcmalloc-4.7.0-redhat9-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.7.0-redhat9-x64.tar.gz)<br /> [libmimalloc-2.2-redhat9-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-redhat9-x64.tar.gz) |
| RHEL 9.x | aarch64 | redhat9-aarch64 | [libjemalloc-5.3.0-redhat9-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-redhat9-aarch64.tar.gz)<br /> [libtcmalloc-4.7.0-redhat9-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.7.0-redhat9-aarch64.tar.gz)<br /> [libmimalloc-2.2-redhat9-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-redhat9-aarch64.tar.gz) |
| Oracle 8.x | x64 | oracle8-x64 | [libjemalloc-5.3.0-oracle8-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-oracle8-x64.tar.gz)<br /> [libtcmalloc-4.7.0-oracle8-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.7.0-oracle8-x64.tar.gz)<br /> [libmimalloc-2.2-oracle8-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-oracle8-x64.tar.gz) |
| Oracle 8.x | aarch64 | oracle8-aarch64 | [libjemalloc-5.3.0-oracle8-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-oracle8-aarch64.tar.gz)<br /> [libtcmalloc-4.6.0-oracle8-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.6.0-oracle8-aarch64.tar.gz)<br /> [libmimalloc-2.2-oracle8-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-oracle8-aarch64.tar.gz) |
| Oracle 9.x | x64 | redhat9-x64 | [libjemalloc-5.3.0-redhat9-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-redhat9-x64.tar.gz)<br /> [libtcmalloc-4.7.0-redhat9-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.7.0-redhat9-x64.tar.gz)<br /> [libmimalloc-2.2-redhat9-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-redhat9-x64.tar.gz) |
| Oracle 9.x | aarch64 | redhat9-aarch64 | [libjemalloc-5.3.0-redhat9-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-redhat9-aarch64.tar.gz)<br /> [libtcmalloc-4.7.0-redhat9-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.7.0-redhat9-aarch64.tar.gz)<br /> [libmimalloc-2.2-redhat9-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-redhat9-aarch64.tar.gz) |
| Ubuntu | x64 | debian-x64 | [libjemalloc-5.3.0-debian-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-debian-x64.tar.gz)<br /> [libtcmalloc-4.7.0-debian-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.7.0-debian-x64.tar.gz)<br /> [libmimalloc-2.2-debian-x64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-debian-x64.tar.gz) |
| Ubuntu | aarch64 | debian-aarch64 | [libjemalloc-5.3.0-debian-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libjemalloc-5.3.0-debian-focal-aarch64.tar.gz)<br /> [libtcmalloc-4.7.0-debian-focal-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libtcmalloc-4.7.0-debian-focal-aarch64.tar.gz)<br /> [libmimalloc-2.2-debian-aarch64.tar.gz](https://github.com/nmaguiar/libmalloc/releases/download/0.2.0/libmimalloc-2.2-debian-aarch64.tar.gz)|

## Usage

To use it with a target application:

1. Download the package that fits your Linux distribution and processor.
2. Place the library you want to use on a Linux folder accessible by your application.
3. Set the environment variable LD_PRELOAD: ```LD_PRELOAD=/path/to/a/folder/libmylib.so.1.2.3```
4. Start your target application.

## Checking

To check if the library is being used:

1. Get the target application PID.
2. Execute ```grep libmylib.so.1.2.3 /proc/[PID]/maps```.
3. Verify if there are any lines with libmylib.so.1.2.3 to make sure it's loaded.

# libmalloc

Binaries Linux builds of the libtcmalloc and the libjemalloc libraries.

## Download

First you will need to choose the appropriate tar.gz to download. List of ditributions and corresponding tar.gz suffix to use:

| Linux distribution | Architecture | Suffix tar.gz |
|---|---|---|
| Alpine 3.x | x64 | alpine-x64 |
| Alpine 3.x | aarch64 | alpine-aarch64 |
| RHEL 8.x | x64 | redhat8-x64 | 
| RHEL 8.x | aarch64 | redhat8-aarch64 |
| RHEL 9.x | x64 | redhat9-x64 |
| RHEL 9.x | aarch64 | redhat9-aarch64 |
| Oracle 8.x | x64 | redhat8-x64 |
| Oracle 8.x | aarch64 | redhat8-aarch64 |
| Oracle 9.x | x64 | redhat9-x64 |
| Oracle 9.x | aarch64 | redhat9-aarch64 |
| Ubuntu >= Focal | x64 | debian-x64 |
| Ubuntu >= Focal | aarch64 | debian-aarch64 |

## Usage

To use it with a target application:

1. Download the package that fits your Linux distribution and processor.
2. Place the library you want to use on a Linux folder accessible by your application.
3. Set the environment variable LD_PRELOAD: ```LD_PRELOAD=/path/to/a/folder/libmylib.so.1.2.3```
4. Start your target application.

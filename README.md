# Pixel Experience #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/pe-sado/manifest -b fourteen

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Build the code
$ ./build.sh $DEVICE $PACKAGE(updatepackage or otapackage)
```
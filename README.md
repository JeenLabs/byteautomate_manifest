### ByteAutomate ###

# Initialize Local Repository #
```bash
repo init -u git@github.com:JeenLabs/byteautomate_manifest.git -b v1.0
```

# Or Initialize Shallow Clone #
```bash
repo init --depth=1 -u git@github.com:JeenLabs/byteautomate_manifest.git -b v1.0
```

# Syncing Repository # 
```bash
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle
```

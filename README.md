# local_manifests for rosemary

## How to install
```bash
git clone https://github.com/ctrhyz/local_manifests .repo/local_manifests
```
## Sync
```bash
repo sync -c --no-clone-bundle --optimized-fetch --prune --force-sync -j$(nproc --all)
```
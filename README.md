# How to use

```bash
mkdir -p .repo/local_manifests
git clone https://github.com/zatvio/ossi_manifest.git .repo/local_manifests
repo sync -j$(nproc --all)
```

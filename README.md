# RudySource Scoop Bucket

[![CI](https://github.com/RudySource/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/RudySource/scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/RudySource/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/RudySource/scoop-bucket/actions/workflows/excavator.yml)

Official Scoop manifests for [Dirgo](https://github.com/RudySource/Dirgo).

## Install

```powershell
scoop bucket add rudysource https://github.com/RudySource/scoop-bucket
scoop install rudysource/dirgo
```

Upgrade later with `scoop update dirgo`.

Dirgo releases are downloaded directly from GitHub and verified against the
SHA-256 checksum recorded in the manifest.

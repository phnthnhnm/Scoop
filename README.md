# Scoop Bucket

[![Tests](https://github.com/phnthnhnm/Scoop/actions/workflows/ci.yml/badge.svg)](https://github.com/phnthnhnm/Scoop/actions/workflows/ci.yml) [![Excavator](https://github.com/phnthnhnm/Scoop/actions/workflows/excavator.yml/badge.svg)](https://github.com/phnthnhnm/Scoop/actions/workflows/excavator.yml)

My personal [Scoop](https://scoop.sh) bucket.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add <bucketname> https://github.com/phnthnhnm/Scoop
scoop install <bucketname>/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.

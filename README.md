# scoop-bucket

[![Tests](https://github.com/heewq/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/heewq/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/heewq/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/heewq/scoop-bucket/actions/workflows/excavator.yml)

Personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## Usage

```pwsh
scoop bucket add heewq https://github.com/heewq/scoop-bucket
scoop install heewq/kero
```

## Apps

| App | Description |
| --- | --- |
| [kero](bucket/kero.json) | [Kero](https://kero.sh/), a terminal for coding agents |

Manifests are kept up to date by [Excavator](.github/workflows/excavator.yml), which runs every 4 hours.

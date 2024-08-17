# scoop-box bucket for Scoop

[![Tests](https://github.com/DenisionSoft/scoop-box/actions/workflows/ci.yml/badge.svg)](https://github.com/DenisionSoft/scoop-box/actions/workflows/ci.yml) [![Excavator](https://github.com/DenisionSoft/scoop-box/actions/workflows/excavator.yml/badge.svg)](https://github.com/DenisionSoft/scoop-box/actions/workflows/excavator.yml)

scoop-box bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

It contains some little apps unavailable in other buckets or package managers, and specific versions of apps for easy installation. Could also host some of my apps here in the future...

## Apps

You can check the apps included [here](https://github.com/DenisionSoft/scoop-box/tree/master/bucket).

| Name  | Description |
|-------|-------------|
| powermode | CLI tool for changing Windows Power Mode usually found in Settings |
| roundedtb-canary | A continuation of RoundedTB, a Windows taskbar customizer |
| snp | VS Code code snippet generator |
| temurin8u312 | JRE 8 version 8u312b07, the last supported by Forge for Minecraft 1.16.5 |

## How do I install these manifests?

```pwsh
scoop bucket add scoop-box https://github.com/DenisionSoft/scoop-box
scoop install scoop-box/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.

<div align="center">

# scoop-bucket

**A Scoop bucket for ChordSketch.**

![License: MIT](https://img.shields.io/badge/license-MIT-0f7b6c)
![Platform: Windows 64-bit](https://img.shields.io/badge/platform-Windows%2064--bit-0f7b6c)

[What you can install](#what-you-can-install) · [Install](#install) · [Update and remove](#update-and-remove) · [License](#license)

</div>

This bucket installs [ChordSketch](https://github.com/koedame/chordsketch), a ChordPro parser and renderer, as a command-line tool on Windows. The software itself lives in that repository; this one only holds the Scoop manifest.

## What you can install

| Name | What you get |
|---|---|
| `chordsketch` | The `chordsketch.exe` command-line tool, prebuilt. Windows, 64-bit |

## Install

```powershell
scoop bucket add koedame https://github.com/koedame/scoop-bucket
scoop install koedame/chordsketch
```

Naming the bucket (`koedame/chordsketch`) picks this manifest even if another bucket has one with the same name.

## Update and remove

```powershell
scoop update
scoop update chordsketch
scoop uninstall chordsketch
```

The manifest is updated after each release of ChordSketch, so `scoop update` follows the releases.

## Security

To report a problem with a manifest in this repository (a wrong download URL or checksum), see [SECURITY.md](SECURITY.md). Problems in ChordSketch itself belong in [its repository](https://github.com/koedame/chordsketch).

## Trademarks

Scoop and Windows are trademarks of their respective owners. This bucket is not affiliated with or endorsed by them.

## Contributing

This repository does not accept outside contributions: pull requests are not reviewed or merged and may be closed without a reply. Bug reports and questions are welcome as [issues](https://github.com/koedame/scoop-bucket/issues), without any promise of an answer. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

The MIT License in [LICENSE](LICENSE) applies to the manifest files in this repository.
It does not apply to the software those manifests install. Each application is distributed under its own license, which is stated in its own repository and in the `license` field of its manifest.

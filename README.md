# pandoc

[中文版本](./README.cn.md)

Universal markup converter

![pandoc](https://repo.x-cmd.io/pandoc.svg)

## Install

```sh
x install pandoc
```

## Code insight

Total: **120,388** lines of code across **603** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Haskell | 100,377 | 12,702 | 9,657 | 365 |
| Xml | 4,491 | 0 | 2 | 47 |
| Lua | 3,236 | 181 | 208 | 48 |
| Yaml | 2,537 | 161 | 53 | 130 |
| Html | 2,243 | 58 | 54 | 13 |

## OpenSSF Scorecard

Overall score: **5.6 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **Code-Review** (0/10) — Found 0/30 approved changesets -- score normalized to 0
- **SAST** (0/10) — no SAST tool detected

## Source

- **Upstream**: <https://github.com/jgm/pandoc>
- **Homepage**: <https://pandoc.org>
- **License**: GPL-2.0

## Release

- **Latest**: `3.11` (2026-08-29)
- **Last commit**: 2026-09-10
- **Assets in release**: 11

## Popularity

- **Stars**: 46,225 · **Forks**: 3,966 · **Open issues**: 8,358 · **Contributors**: 583

## Totals (cumulative)

- **Releases**: 159 · **Merged PRs**: 1806 · **Open PRs**: 80 · **Closed issues**: 7402 · **Open issues**: 956 · **Commits**: 19337

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 2 | 6 | 5 | 19 | 11 | 264 |
| last60d | 2026-07-12 | 3 | 15 | 5 | 32 | 16 | 329 |
| 90d | 2026-06-12 | 3 | 25 | 6 | 54 | 21 | 388 |
| last180d | 2026-03-14 | 6 | 41 | 7 | 129 | 40 | 621 |
| 360d | 2025-09-15 | 11 | 101 | 12 | 272 | 75 | 1038 |
| last720d | 2024-09-20 | 21 | 219 | 21 | 630 | 123 | 1637 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [pandoc-3.11-1-amd64.deb](https://github.com/jgm/pandoc/releases/download/3.11/pandoc-3.11-1-amd64.deb) | 32.8 MiB | `other` |
| [pandoc-3.11-1-arm64.deb](https://github.com/jgm/pandoc/releases/download/3.11/pandoc-3.11-1-arm64.deb) | 35.2 MiB | `other` |
| [pandoc-3.11-arm64-macOS.pkg](https://github.com/jgm/pandoc/releases/download/3.11/pandoc-3.11-arm64-macOS.pkg) | 39.8 MiB | `native/darwin/arm64` |
| [pandoc-3.11-arm64-macOS.zip](https://github.com/jgm/pandoc/releases/download/3.11/pandoc-3.11-arm64-macOS.zip) | 39.9 MiB | `native/darwin/arm64` |
| [pandoc-3.11-linux-amd64.tar.gz](https://github.com/jgm/pandoc/releases/download/3.11/pandoc-3.11-linux-amd64.tar.gz) | 33.3 MiB | `native/linux/x64` |
| [pandoc-3.11-linux-arm64.tar.gz](https://github.com/jgm/pandoc/releases/download/3.11/pandoc-3.11-linux-arm64.tar.gz) | 35.7 MiB | `native/linux/arm64` |
| [pandoc-3.11-windows-x86_64.msi](https://github.com/jgm/pandoc/releases/download/3.11/pandoc-3.11-windows-x86_64.msi) | 39.6 MiB | `native/win/x64` |
| [pandoc-3.11-windows-x86_64.zip](https://github.com/jgm/pandoc/releases/download/3.11/pandoc-3.11-windows-x86_64.zip) | 39.8 MiB | `native/win/x64` |
| [pandoc-3.11-x86_64-macOS.pkg](https://github.com/jgm/pandoc/releases/download/3.11/pandoc-3.11-x86_64-macOS.pkg) | 24.9 MiB | `native/darwin/x64` |
| [pandoc-3.11-x86_64-macOS.zip](https://github.com/jgm/pandoc/releases/download/3.11/pandoc-3.11-x86_64-macOS.zip) | 24.9 MiB | `native/darwin/x64` |
| [pandoc-3.11.wasm.zip](https://github.com/jgm/pandoc/releases/download/3.11/pandoc-3.11.wasm.zip) | 15.7 MiB | `other` |

## Distribution status

Reported by **299** distros on [repology.org](https://repology.org/project/pandoc). **17** are ✅ on the latest upstream release, **129** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `3.11` | ✅ latest |
| Debian 14 | `3.10.2` | ⚠️ outdated |
| Debian 13 | `3.1.11.1` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `3.7.0.2` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `3.1.3` | ⚠️ outdated |
| Arch | `3.10.2` | ⚠️ outdated |
| Homebrew | `HEAD` | 🔄 rolling |
| Fedora rawhide | `3.7.0.2` | ⚠️ outdated |
| Nix unstable | `3.7.0.2` | 🪦 legacy |
| Void | `3.6` | ⚠️ outdated |
| openSUSE Tumbleweed | `3.10` | ⚠️ outdated |

## Improve this data

Install metadata for pandoc lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `pandoc` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/pandoc.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T22:09:24Z._

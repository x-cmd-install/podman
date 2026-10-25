# podman

[中文版本](./README.cn.md)

Podman: A tool for managing OCI containers and pods.

[![x-cmd/install — podman Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/podman.svg)](https://x-cmd.com/install/podman)

## Install

```sh
x install podman
```

## Code insight

Total: **1,988,960** lines of code across **7905** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 1,671,157 | 304,506 | 207,343 | 7571 |
| C | 179,402 | 77,677 | 16,155 | 16 |
| AssemblyGAS | 83,987 | 3,297 | 6,381 | 182 |
| Yaml | 14,635 | 106 | 345 | 44 |
| Autoconf | 7,574 | 1,078 | 3,682 | 92 |

## OpenSSF Scorecard

Overall score: **7.8 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **Branch-Protection** (4/10) — branch protection is not maximal on development and all release branches
- **Signed-Releases** (0/10) — Project has not signed or included provenance with any releases.

## Source

- **Upstream**: <https://github.com/containers/podman>
- **Homepage**: <https://podman.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v5.8.9` (2026-10-12)
- **Last commit**: 2026-10-23
- **Assets in release**: 9

## Popularity

- **Stars**: 33,117 · **Forks**: 3,420 · **Open issues**: 10,970 · **Contributors**: 949

## Totals (cumulative)

- **Releases**: 255 · **Merged PRs**: 13112 · **Open PRs**: 127 · **Closed issues**: 10108 · **Open issues**: 862 · **Commits**: 28698

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-25 | 4 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-08-26 | 7 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-07-27 | 10 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-04-28 | 17 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-10-30 | 25 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-11-04 | 45 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [podman-installer-macos-arm64.pkg](https://github.com/containers/podman/releases/download/v6.1.4/podman-installer-macos-arm64.pkg) | 72.6 MiB | `native/darwin/arm64` |
| [podman-installer-windows-amd64.msi](https://github.com/containers/podman/releases/download/v6.1.4/podman-installer-windows-amd64.msi) | 27.2 MiB | `native/win/x64` |
| [podman-installer-windows-arm64.msi](https://github.com/containers/podman/releases/download/v6.1.4/podman-installer-windows-arm64.msi) | 25.1 MiB | `native/win/arm64` |
| [podman-remote-release-darwin_arm64.zip](https://github.com/containers/podman/releases/download/v6.1.4/podman-remote-release-darwin_arm64.zip) | 24.3 MiB | `native/darwin/arm64` |
| [podman-remote-release-windows_amd64.zip](https://github.com/containers/podman/releases/download/v6.1.4/podman-remote-release-windows_amd64.zip) | 30.6 MiB | `native/win/x64` |
| [podman-remote-release-windows_arm64.zip](https://github.com/containers/podman/releases/download/v6.1.4/podman-remote-release-windows_arm64.zip) | 27.9 MiB | `native/win/arm64` |
| [podman-remote-static-linux_amd64.tar.gz](https://github.com/containers/podman/releases/download/v6.1.4/podman-remote-static-linux_amd64.tar.gz) | 22.5 MiB | `native/linux/x64` |
| [podman-remote-static-linux_arm64.tar.gz](https://github.com/containers/podman/releases/download/v6.1.4/podman-remote-static-linux_arm64.tar.gz) | 20.6 MiB | `native/linux/arm64` |
| [shasums](https://github.com/containers/podman/releases/download/v6.1.4/shasums) | 830 B | `other` |

## Distribution status

Reported by **459** distros on [repology.org](https://repology.org/project/podman). **45** are ✅ on the latest upstream release, **268** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `5.8.6` | ⚠️ outdated |
| Debian 14 | `5.8.6` | ⚠️ outdated |
| Debian 13 | `5.4.2` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `5.7.0` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `4.9.3` | ⚠️ outdated |
| Arch | `6.1.4` | ✅ latest |
| Homebrew | `HEAD` | 🔄 rolling |
| Fedora rawhide | `6.1.4` | ✅ latest |
| Nix unstable | `5.8.9` | ⚠️ outdated |
| Void | `6.1.4` | ✅ latest |
| Alpine edge | `6.1.4` | ✅ latest |
| openSUSE Tumbleweed | `6.1.2` | ⚠️ outdated |

## Improve this data

Install metadata for podman lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `podman` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/podman.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261025.yml` · 2026-10-25T05:14:54Z._

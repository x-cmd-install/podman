# podman

[中文版本](./README.cn.md)

Podman: A tool for managing OCI containers and pods.

[![x-cmd/install — podman Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/podman.svg)](https://x-cmd.com/install/podman)

## Install

```sh
x install podman
```

## Code insight

Total: **2,026,018** lines of code across **7967** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 1,692,192 | 310,315 | 209,634 | 7630 |
| C | 180,383 | 78,302 | 16,031 | 16 |
| AssemblyGAS | 84,046 | 3,301 | 6,400 | 184 |
| Yaml | 29,467 | 138 | 582 | 45 |
| Autoconf | 7,576 | 1,026 | 3,630 | 92 |

## OpenSSF Scorecard

Overall score: **7.7 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **Branch-Protection** (4/10) — branch protection is not maximal on development and all release branches
- **Signed-Releases** (0/10) — Project has not signed or included provenance with any releases.

## Source

- **Upstream**: <https://github.com/containers/podman>
- **Homepage**: <https://podman.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v6.2.0` (2026-11-10)
- **Last commit**: 2026-11-13
- **Assets in release**: 9

## Popularity

- **Stars**: 33,271 · **Forks**: 3,456 · **Open issues**: 11,055 · **Contributors**: 972

## Totals (cumulative)

- **Releases**: 258 · **Merged PRs**: 13225 · **Open PRs**: 129 · **Closed issues**: 10170 · **Open issues**: 885 · **Commits**: 28924

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-15 | 3 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-09-15 | 9 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-08-16 | 10 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-05-18 | 20 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-11-19 | 25 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-11-24 | 45 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [podman-installer-macos-arm64.pkg](https://github.com/containers/podman/releases/download/v6.2.0/podman-installer-macos-arm64.pkg) | 73.2 MiB | `native/darwin/arm64` |
| [podman-installer-windows-amd64.msi](https://github.com/containers/podman/releases/download/v6.2.0/podman-installer-windows-amd64.msi) | 27.8 MiB | `native/win/x64` |
| [podman-installer-windows-arm64.msi](https://github.com/containers/podman/releases/download/v6.2.0/podman-installer-windows-arm64.msi) | 25.6 MiB | `native/win/arm64` |
| [podman-remote-release-darwin_arm64.zip](https://github.com/containers/podman/releases/download/v6.2.0/podman-remote-release-darwin_arm64.zip) | 24.9 MiB | `native/darwin/arm64` |
| [podman-remote-release-windows_amd64.zip](https://github.com/containers/podman/releases/download/v6.2.0/podman-remote-release-windows_amd64.zip) | 31.2 MiB | `native/win/x64` |
| [podman-remote-release-windows_arm64.zip](https://github.com/containers/podman/releases/download/v6.2.0/podman-remote-release-windows_arm64.zip) | 28.5 MiB | `native/win/arm64` |
| [podman-remote-static-linux_amd64.tar.gz](https://github.com/containers/podman/releases/download/v6.2.0/podman-remote-static-linux_amd64.tar.gz) | 23.1 MiB | `native/linux/x64` |
| [podman-remote-static-linux_arm64.tar.gz](https://github.com/containers/podman/releases/download/v6.2.0/podman-remote-static-linux_arm64.tar.gz) | 21.2 MiB | `native/linux/arm64` |
| [shasums](https://github.com/containers/podman/releases/download/v6.2.0/shasums) | 830 B | `other` |

## Distribution status

Reported by **463** distros on [repology.org](https://repology.org/project/podman). **19** are ✅ on the latest upstream release, **301** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `5.8.6` | ⚠️ outdated |
| Debian 14 | `5.8.6` | ⚠️ outdated |
| Debian 13 | `5.4.2` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `5.7.0` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `4.9.3` | ⚠️ outdated |
| Arch | `6.2.0` | ✅ latest |
| Homebrew | `6.2.0` | ✅ latest |
| Fedora rawhide | `6.2.0~rc1` | ⚠️ outdated |
| Nix unstable | `6.1.4` | ⚠️ outdated |
| Void | `6.1.4` | ⚠️ outdated |
| Alpine edge | `6.1.4` | ⚠️ outdated |
| openSUSE Tumbleweed | `6.1.4` | ⚠️ outdated |

## Improve this data

Install metadata for podman lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `podman` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/podman.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261114.yml` · 2026-11-14T07:37:43Z._

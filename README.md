# podman

[中文版本](./README.cn.md)

Podman: A tool for managing OCI containers and pods.

[![x-cmd/install — podman Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/podman.svg)](https://x-cmd.com/install/podman)

## Install

```sh
x install podman
```

## Code insight

Total: **1,990,422** lines of code across **7911** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 1,672,552 | 304,859 | 207,517 | 7577 |
| C | 179,402 | 77,677 | 16,155 | 16 |
| AssemblyGAS | 83,987 | 3,297 | 6,381 | 182 |
| Yaml | 14,635 | 106 | 345 | 44 |
| Autoconf | 7,591 | 1,078 | 3,685 | 92 |

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

- **Latest**: `v6.2.0-rc1` (2026-10-12)
- **Last commit**: 2026-10-29
- **Assets in release**: 9

## Popularity

- **Stars**: 33,152 · **Forks**: 3,431 · **Open issues**: 10,982 · **Contributors**: 954

## Totals (cumulative)

- **Releases**: 256 · **Merged PRs**: 13143 · **Open PRs**: 116 · **Closed issues**: 10122 · **Open issues**: 860 · **Commits**: 28758

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-30 | 3 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-08-31 | 8 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-08-01 | 10 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-05-03 | 18 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-11-04 | 25 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-11-09 | 45 | 0 | 0 | 0 | 0 | 0 |

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

Reported by **463** distros on [repology.org](https://repology.org/project/podman). **46** are ✅ on the latest upstream release, **271** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `5.8.6` | ⚠️ outdated |
| Debian 14 | `5.8.6` | ⚠️ outdated |
| Debian 13 | `5.4.2` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `5.7.0` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `4.9.3` | ⚠️ outdated |
| Arch | `6.1.4` | ✅ latest |
| Homebrew | `6.1.4` | ✅ latest |
| Fedora rawhide | `6.1.4` | ✅ latest |
| Nix unstable | `6.1.4` | ✅ latest |
| Void | `6.1.4` | ✅ latest |
| Alpine edge | `6.1.4` | ✅ latest |
| openSUSE Tumbleweed | `6.1.2` | ⚠️ outdated |

## Improve this data

Install metadata for podman lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `podman` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/podman.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261030.yml` · 2026-10-30T06:27:17Z._

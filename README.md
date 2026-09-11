# podman

[中文版本](./README.cn.md)

Podman: A tool for managing OCI containers and pods.

![podman](https://repo.x-cmd.io/podman.svg)

## Install

```sh
x install podman
```

## Code insight

Total: **1,940,163** lines of code across **7633** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 1,642,728 | 294,262 | 201,437 | 7322 |
| C | 179,381 | 77,677 | 16,153 | 16 |
| AssemblyGAS | 64,122 | 2,804 | 5,648 | 159 |
| Yaml | 14,606 | 106 | 345 | 44 |
| Autoconf | 7,555 | 1,074 | 3,676 | 92 |

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

- **Latest**: `v6.1.1` (2026-09-02)
- **Last commit**: 2026-09-11
- **Assets in release**: 9

## Popularity

- **Stars**: 32,841 · **Forks**: 3,371 · **Open issues**: 10,899 · **Contributors**: 912

## Totals (cumulative)

- **Releases**: 249 · **Merged PRs**: 12940 · **Open PRs**: 184 · **Closed issues**: 9992 · **Open issues**: 907 · **Commits**: 28352

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 3 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-13 | 5 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-13 | 9 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-15 | 12 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-16 | 20 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-21 | 44 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [podman-installer-macos-arm64.pkg](https://github.com/containers/podman/releases/download/v6.1.1/podman-installer-macos-arm64.pkg) | 72.8 MiB | `native/darwin/arm64` |
| [podman-installer-windows-amd64.msi](https://github.com/containers/podman/releases/download/v6.1.1/podman-installer-windows-amd64.msi) | 27.5 MiB | `native/win/x64` |
| [podman-installer-windows-arm64.msi](https://github.com/containers/podman/releases/download/v6.1.1/podman-installer-windows-arm64.msi) | 25.3 MiB | `native/win/arm64` |
| [podman-remote-release-darwin_arm64.zip](https://github.com/containers/podman/releases/download/v6.1.1/podman-remote-release-darwin_arm64.zip) | 25.2 MiB | `native/darwin/arm64` |
| [podman-remote-release-windows_amd64.zip](https://github.com/containers/podman/releases/download/v6.1.1/podman-remote-release-windows_amd64.zip) | 30.8 MiB | `native/win/x64` |
| [podman-remote-release-windows_arm64.zip](https://github.com/containers/podman/releases/download/v6.1.1/podman-remote-release-windows_arm64.zip) | 28.1 MiB | `native/win/arm64` |
| [podman-remote-static-linux_amd64.tar.gz](https://github.com/containers/podman/releases/download/v6.1.1/podman-remote-static-linux_amd64.tar.gz) | 23.3 MiB | `native/linux/x64` |
| [podman-remote-static-linux_arm64.tar.gz](https://github.com/containers/podman/releases/download/v6.1.1/podman-remote-static-linux_arm64.tar.gz) | 21.4 MiB | `native/linux/arm64` |
| [shasums](https://github.com/containers/podman/releases/download/v6.1.1/shasums) | 830 B | `other` |

## Distribution status

Reported by **465** distros on [repology.org](https://repology.org/project/podman). **39** are ✅ on the latest upstream release, **276** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `5.8.6` | ⚠️ outdated |
| Debian 14 | `5.8.6` | ⚠️ outdated |
| Debian 13 | `5.4.2` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `5.7.0` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `4.9.3` | ⚠️ outdated |
| Arch | `6.1.1` | ✅ latest |
| Homebrew | `HEAD` | 🔄 rolling |
| Fedora rawhide | `6.1.1` | ✅ latest |
| Nix unstable | `5.8.6` | ⚠️ outdated |
| Void | `5.8.3` | ⚠️ outdated |
| Alpine edge | `6.1.1` | ✅ latest |
| openSUSE Tumbleweed | `6.0.2` | ⚠️ outdated |

## Improve this data

Install metadata for podman lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `podman` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/podman.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T05:33:28Z._

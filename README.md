# podman

[中文版本](./README.cn.md)

Podman: A tool for managing OCI containers and pods.

![podman](https://repo.x-cmd.io/podman.svg)

## Install

```sh
x install podman
```

## Code insight

Total: **1,942,865** lines of code across **7646** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 1,645,190 | 294,878 | 201,849 | 7335 |
| C | 179,381 | 77,677 | 16,153 | 16 |
| AssemblyGAS | 64,122 | 2,804 | 5,648 | 159 |
| Yaml | 14,608 | 106 | 345 | 44 |
| Autoconf | 7,549 | 1,074 | 3,670 | 92 |

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

- **Latest**: `v5.8.7` (2026-09-16)
- **Last commit**: 2026-09-17
- **Assets in release**: 9

## Popularity

- **Stars**: 32,889 · **Forks**: 3,380 · **Open issues**: 10,912 · **Contributors**: 921

## Totals (cumulative)

- **Releases**: 251 · **Merged PRs**: 12969 · **Open PRs**: 154 · **Closed issues**: 10034 · **Open issues**: 878 · **Commits**: 28405

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-19 | 3 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-20 | 7 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-20 | 11 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-22 | 14 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-23 | 22 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-28 | 45 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [podman-installer-macos-arm64.pkg](https://github.com/containers/podman/releases/download/v6.1.2/podman-installer-macos-arm64.pkg) | 72.9 MiB | `native/darwin/arm64` |
| [podman-installer-windows-amd64.msi](https://github.com/containers/podman/releases/download/v6.1.2/podman-installer-windows-amd64.msi) | 27.5 MiB | `native/win/x64` |
| [podman-installer-windows-arm64.msi](https://github.com/containers/podman/releases/download/v6.1.2/podman-installer-windows-arm64.msi) | 25.3 MiB | `native/win/arm64` |
| [podman-remote-release-darwin_arm64.zip](https://github.com/containers/podman/releases/download/v6.1.2/podman-remote-release-darwin_arm64.zip) | 25.3 MiB | `native/darwin/arm64` |
| [podman-remote-release-windows_amd64.zip](https://github.com/containers/podman/releases/download/v6.1.2/podman-remote-release-windows_amd64.zip) | 30.9 MiB | `native/win/x64` |
| [podman-remote-release-windows_arm64.zip](https://github.com/containers/podman/releases/download/v6.1.2/podman-remote-release-windows_arm64.zip) | 28.1 MiB | `native/win/arm64` |
| [podman-remote-static-linux_amd64.tar.gz](https://github.com/containers/podman/releases/download/v6.1.2/podman-remote-static-linux_amd64.tar.gz) | 23.4 MiB | `native/linux/x64` |
| [podman-remote-static-linux_arm64.tar.gz](https://github.com/containers/podman/releases/download/v6.1.2/podman-remote-static-linux_arm64.tar.gz) | 21.4 MiB | `native/linux/arm64` |
| [shasums](https://github.com/containers/podman/releases/download/v6.1.2/shasums) | 830 B | `other` |

## Improve this data

Install metadata for podman lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `podman` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/podman.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260918.yml` · 2026-09-18T05:51:12Z._

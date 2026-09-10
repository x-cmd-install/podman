# podman

[English version](./README.md)

Podman: A tool for managing OCI containers and pods.

![podman](https://repo.x-cmd.io/podman.svg?lang=zh)

## 安装

```sh
x install podman
```

## 代码规模

合计: **1,939,480** 行代码（覆盖前 5 种语言、共 **7632** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 1,642,045 | 294,212 | 201,281 | 7321 |
| C | 179,381 | 77,677 | 16,153 | 16 |
| AssemblyGAS | 64,122 | 2,804 | 5,648 | 159 |
| Yaml | 14,606 | 106 | 345 | 44 |
| Autoconf | 7,555 | 1,074 | 3,676 | 92 |

## OpenSSF Scorecard 评分

总评分: **7.8 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Branch-Protection** (4/10) — branch protection is not maximal on development and all release branches
- **Signed-Releases** (0/10) — Project has not signed or included provenance with any releases.

## 源代码

- **上游仓库**: <https://github.com/containers/podman>
- **官网**: <https://podman.io>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v6.1.1` (2026-09-02)
- **最近提交**: 2026-09-10
- **Release 含资产**: 9 个

## 流行度

- **Star**: 32,839 · **Fork**: 3,370 · **开放 issue**: 10,899 · **贡献者**: 912

## 累计统计

- **发布数**: 249 · **已合并 PR**: 12939 · **开放 PR**: 184 · **已关闭 issue**: 9992 · **开放 issue**: 907 · **提交数**: 28350

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 3 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-12 | 5 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-12 | 11 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-14 | 12 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-15 | 20 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-20 | 44 | 0 | 0 | 0 | 0 | 0 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [podman-installer-macos-arm64.pkg](https://github.com/containers/podman/releases/download/v6.1.1/podman-installer-macos-arm64.pkg) | 72.8 MiB | `native/darwin/arm64` |
| [podman-installer-windows-amd64.msi](https://github.com/containers/podman/releases/download/v6.1.1/podman-installer-windows-amd64.msi) | 27.5 MiB | `native/win/x64` |
| [podman-installer-windows-arm64.msi](https://github.com/containers/podman/releases/download/v6.1.1/podman-installer-windows-arm64.msi) | 25.3 MiB | `native/win/arm64` |
| [podman-remote-release-darwin_arm64.zip](https://github.com/containers/podman/releases/download/v6.1.1/podman-remote-release-darwin_arm64.zip) | 25.2 MiB | `native/darwin/arm64` |
| [podman-remote-release-windows_amd64.zip](https://github.com/containers/podman/releases/download/v6.1.1/podman-remote-release-windows_amd64.zip) | 30.8 MiB | `native/win/x64` |
| [podman-remote-release-windows_arm64.zip](https://github.com/containers/podman/releases/download/v6.1.1/podman-remote-release-windows_arm64.zip) | 28.1 MiB | `native/win/arm64` |
| [podman-remote-static-linux_amd64.tar.gz](https://github.com/containers/podman/releases/download/v6.1.1/podman-remote-static-linux_amd64.tar.gz) | 23.3 MiB | `native/linux/x64` |
| [podman-remote-static-linux_arm64.tar.gz](https://github.com/containers/podman/releases/download/v6.1.1/podman-remote-static-linux_arm64.tar.gz) | 21.4 MiB | `native/linux/arm64` |
| [shasums](https://github.com/containers/podman/releases/download/v6.1.1/shasums) | 830 B | `other` |

## 发行版状态

在 [repology.org](https://repology.org/project/podman) 上共有 **465** 个发行版报告此项目。**39** 个 ✅ 已是最新上游版本，**276** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
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

## 改进这些数据

podman 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `podman` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/podman.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T21:37:35Z._

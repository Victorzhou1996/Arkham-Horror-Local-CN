# Windows / Linux 独立完整包

## 最新版：2026-10-15 / v20261015.1

- [Windows 完整 ZIP](https://media.githubusercontent.com/media/Victorzhou1996/Arkham-Horror-Local-CN/Server/server/packages/v20261015.1/ArkhamHorrorLocal-Windows-v20261015.1.zip)（1,845,502,971字节） · [SHA-256](v20261015.1/ArkhamHorrorLocal-Windows-v20261015.1.zip.sha256)
- [Linux amd64 完整 tar.gz](https://media.githubusercontent.com/media/Victorzhou1996/Arkham-Horror-Local-CN/Server/server/packages/v20261015.1/ArkhamHorror-Server-Linux-amd64-v20261015.1.tar.gz)（1,844,634,101字节） · [SHA-256](v20261015.1/ArkhamHorror-Server-Linux-amd64-v20261015.1.tar.gz.sha256)
- [对应源码 tar.gz](https://media.githubusercontent.com/media/Victorzhou1996/Arkham-Horror-Local-CN/Server/server/packages/v20261015.1/ArkhamHorror-Sources-v20261015.1.tar.gz) · [SHA-256](v20261015.1/ArkhamHorror-Sources-v20261015.1.tar.gz.sha256) · [源码清单](v20261015.1/SOURCE.json)
- [更新与升级说明](../RELEASE-20261015.md) · [验证范围](v20261015.1/VERIFICATION.json) · **[Mac 重编译交接](../../docs/MAC-REBUILD-20261015.md)**

本次为 Windows/Linux 与对应源码的发布，Mac 待原生重编译。游戏版本 `2026.10.15.1-shared-ui`，后端仍为10月9日固定版本；共享设置/导航、收藏、存档导出和创伤选择中文已更新。完整卡图、汉化、新旧UI和Build均保留。安装/升级遵循包内文档，先备份、停服，再解压到新目录，不覆盖用户数据。

Git LFS 下载：`git lfs pull --include='server/packages/v20261015.1/*' --exclude=''`。GitHub Download ZIP不等于完整包。Linux校验：`python3 server/packaging/verify-self-hosted-package.py server/packages/v20261015.1/PACKAGE.json`。`server/source/`、`server/release/`仍为历史快照，最新版源码以本节版本化归档为准。

## 旧版本与提交历史

当前目录仅保留 `v20261015.1`。四个旧版本包目录已在2026-10-19的整理提交中移除，Git提交历史仍然保留；如需追溯旧包，请切换到整理前的历史提交。
本次没有重新编译或打包，最新目录中的 Linux、Windows、源码归档及校验文件均未改变。

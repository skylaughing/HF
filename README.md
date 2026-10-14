# HF 航发论文资料

## 论文下载

**[点击这里打开论文下载页面（GitHub Releases）](https://github.com/skylaughing/HF/releases/tag/papers-257-326-20261013)**

已上传：起步采集清单第 257–326 行对应的 2026-10-13 采集快照，包含 1,095 篇已校验 PDF、27,636 条候选题录、主题覆盖和采集进度。候选题录尚未全部人工复核。

- 26 个压缩包分卷，总计约 8.97 GB；每份不超过 350 MB。
- 4 个辅助文件：`README.txt`、`restore_archive.py`、`transfer_manifest.json`、`SHA256SUMS.txt`。
- 全部 30 个附件已经上传，远端大小和 SHA-256 校验通过。

## 下载与还原

1. 登录有本私有仓库访问权限的 GitHub 账号，点击上方下载链接。
2. 展开页面下方 **Assets**；如列表未完整显示，点击 **Show all assets**。
3. 将 `.zip.001` 至 `.zip.026` 的全部 26 个分卷及 4 个辅助文件下载到同一文件夹。
4. 在该文件夹打开终端，运行下面适用于本机的命令（需要 Python 3.8 或更新版本，无额外依赖）。

Windows：

```powershell
py -3 restore_archive.py
```

Linux / macOS：

```bash
python3 restore_archive.py
```

脚本会校验各分卷并还原完整 ZIP，之后正常解压即可。合并和解压合计还需约 18 GB 空闲空间。

**论文文件位于 Release 的 Assets 附件区。仓库的 Code 文件列表和自动生成的 Source code 压缩包不包含这些论文。**

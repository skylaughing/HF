# HF 航发论文资料

## 当前版本：2,000 篇初筛集

**[点击这里下载 2,000 篇新版论文（GitHub Release）](https://github.com/skylaughing/HF/releases/tag/curated-2000-257-326-20261015)**

本版为 2026-10-15 整理的 2,000 个独立 PDF，范围是“起步采集清单”第 257–326 行，覆盖 70 个主题的候选内容证据。包含文献清单、主题覆盖表、逐篇主题证据、薄弱主题复核表和文件校验清单。

本版是可复核初筛集，尚未完成逐篇全文专家评审；11 个主题的候选证据不足 10 篇，已在覆盖表中标出。

- 制造装配与修理：345 篇。
- 试验测量与工程验证：425 篇。
- 仿真设计与优化：1,053 篇。
- 健康监测与诊断：177 篇。

## 下载与还原

1. 登录有本私有仓库访问权限的 GitHub 账号，打开上方下载页面。
2. 展开页面下方 **Assets**，必要时点击 **Show all assets**。
3. 如只想先看清单，下载 `review_materials_2000.zip`（不含 PDF）。
4. 下载完整论文时，将 `hf_papers_2000_257-326_20261015.zip.001` 至 `.029` 共 **29 个分卷**，以及 `restore_archive.py` 和 `transfer_manifest.json` 放到同一个独立文件夹。建议同时下载 `README.txt` 和 `SHA256SUMS.txt`。
5. 在该文件夹打开终端并运行下面适用于本机的命令，需要 Python 3.8 或更高版本，无额外依赖。

Windows：

```powershell
py -3 restore_archive.py
```

Linux / macOS：

```bash
python3 restore_archive.py
```

脚本校验各分卷与整体 SHA-256，合并还原 ZIP，之后正常解压即可。分卷不能单独解压，也不要与旧版分卷混在一起。

完整 ZIP 约 9.82 GB，每份分卷最多 350 MB。下载分卷后，合并和解压还需约 20 GB 空闲空间；保留分卷、ZIP 与解压目录时合计约 30 GB。

**论文位于 Release 的 Assets 附件区。Code 文件列表和 GitHub 自动生成的 Source code 压缩包不包含这些论文。**

## 历史版本

[2026-10-13 原始采集快照：1,095 篇 PDF、26 个分卷](https://github.com/skylaughing/HF/releases/tag/papers-257-326-20261013)。旧版继续保留，与当前 2,000 篇初筛版分开存放。

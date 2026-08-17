# 📷 JPG-RAW_OrphanCleaner

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-brightgreen)](https://github.com/KILLSTARSX/JPG-RAW_OrphanCleaner)
[![Latest Release](https://img.shields.io/github/v/release/KILLSTARSX/JPG-RAW_OrphanCleaner)](https://github.com/KILLSTARSX/JPG-RAW_OrphanCleaner/releases/latest)
[![Size](https://img.shields.io/badge/size-16.2%20MB-brightgreen)](https://github.com/KILLSTARSX/JPG-RAW_OrphanCleaner/releases/latest)

> **一张照片的大小，装下了一整套智能照片整理工具**  
> 轻，却前所未有的强。

> **中文**：自动清理 JPG + RAW 双格式中的孤立文件，支持 15+ 相机品牌，移入回收站可恢复。  
> **English**：Automatically find and delete orphaned JPG/RAW files, supports 15+ camera brands, moves to Recycle Bin.

---

## 📖 目录 / Table of Contents

- [功能亮点 / Features](#-功能亮点--features)
- [快速开始 / Quick Start](#-快速开始--quick-start)
- [支持的相机品牌 / Supported Cameras](#-支持的相机品牌与-raw-格式--supported-camera-brands--raw-formats)
- [安全说明 / Safety Notes](#-安全说明--safety-notes)
- [更新日志 / Changelog](#-更新日志--changelog)
- [作者 / Author](#-作者--author)

---

## ✨ 功能亮点 / Features

| 中文 | English |
| :--- | :--- |
| 📦 **极致轻量**：16.2 MB —— 大小和一张 RAW 照片相当，功能却堪比一套完整的照片管理工具 | 📦 **Ultra-Light**：16.2 MB – comparable to a single RAW photo, yet packed with full photo management capabilities |
| 🧠 **智能识别**：自动检测文件夹内的 RAW 格式，支持 15+ 相机品牌 | 🧠 **Smart Detection**：Auto-detects RAW format in folder, supports 15+ brands |
| 📂 **递归扫描**：支持扫描子文件夹（可选层级），跨文件夹配对 | 📂 **Recursive Scan**：Scans subfolders with configurable depth, cross-folder pairing |
| 🖼️ **缩略图预览**：JPG 显示缩略图，RAW 显示后缀占位框 | 🖼️ **Thumbnail Preview**：JPG shows thumbnails, RAW shows suffix placeholders |
| 📷 **EXIF 信息显示**：单击缩略图查看 EXIF，支持简略/详细模式切换 | 📷 **EXIF Display**：Click thumbnail to view EXIF, compact/detailed mode toggle |
| 🗑️ **安全删除**：所有文件移入 Windows 回收站，可恢复 | 🗑️ **Safe Deletion**：All files moved to Windows Recycle Bin, fully recoverable |
| ⚡ **多核并行**：扫描与缩略图生成利用多核 CPU，流畅不卡顿 | ⚡ **Multi-core Parallel**：Scanning & thumbnail generation utilize multi-core CPU |
| ⚙️ **配置记忆**：自动记住上次使用的文件夹、格式、扫描层级等设置 | ⚙️ **Settings Memory**：Remembers last folder, format, scan scope, etc. |
| 🌐 **语言切换**：中英文实时切换，无需重启 | 🌐 **Language Switch**：Real-time Chinese/English toggle, no restart needed |

---

## 🚀 快速开始 / Quick Start

### 下载安装 / Download & Install

1. 前往 **[Releases 页面](https://github.com/KILLSTARSX/JPG-RAW_OrphanCleaner/releases/latest)** 下载最新版本
2. 双击运行，无需安装任何额外软件（适用于 Windows 10 / 11）
1. Go to **[Releases page](https://github.com/KILLSTARSX/JPG-RAW_OrphanCleaner/releases/latest)** to download the latest version
2. Double-click to run – no additional software required (Windows 10 / 11)

### 三步上手 / Three Steps

| 步骤 | 中文 | English |
| :--- | :--- | :--- |
| ① | 点击"浏览…"选择照片文件夹 → 自动开始扫描 | Click "Browse…" to select folder → scanning starts automatically |
| ② | 在文件列表和预览区确认要删除的文件 | Review files in list and preview area |
| ③ | 点击"确认删除"→ 弹窗中点"是"→ 完成 | Click "Confirm Deletion" → click "Yes" → done |

> 📖 详细使用说明请参考压缩包内的 `使用说明书.txt` / For detailed instructions, see `使用说明书.txt` in the package.

---

## 📸 支持的相机品牌与 RAW 格式 / Supported Camera Brands & RAW Formats

| 品牌 / Brand | RAW 后缀 / RAW Suffix(es) |
| :--- | :--- |
| 松下 Panasonic | .RW2 |
| 佳能 Canon | .CR3 / .CR2 / .CRW |
| 尼康 Nikon | .NEF / .NRW |
| 索尼 Sony | .ARW / .SR2 / .SRF |
| 富士 Fujifilm | .RAF |
| 奥林巴斯 OLYMPUS | .ORF |
| 宾得 Pentax | .PEF |
| 适马 Sigma | .X3F |
| 三星 Samsung | .SRW |
| 理光 Ricoh | .DNG |
| 徕卡 Leica | .DNG |
| 哈苏 Hasselblad | .3FR |
| 飞思 Phase One | .IIQ |
| 玛米亚 Mamiya | .MEF |
| 利图 Leaf | .MOS |

---

## ⚠️ 安全说明 / Safety Notes

| 中文 | English |
| :--- | :--- |
| 所有删除操作均移入 **Windows 回收站**，可从回收站还原 | All deletions go to **Windows Recycle Bin** – restorable at any time |
| **不存在任何永久删除调用**，绝不永久删除文件 | **No permanent deletion calls** – files are never permanently deleted |
| 格式不符时强制二次确认，即使取消勾选也不会跳过 | Force re‑confirmation on format mismatch, even if checkbox is unchecked |
| 单个文件失败不中断流程，失败原因明确列出 | Individual file failure won't interrupt the process; reasons are clearly listed |

---

## 📝 更新日志 / Changelog

**v4.0**
- **新增**：回收站删除可恢复（确认弹窗明确提示）
- **新增**：EXIF 九字段对齐显示（相机厂商、型号、光圈、快门、ISO、焦距、拍摄日期、分辨率、镜头）
- **新增**：简略 EXIF 模式（一行紧凑显示：相机 | f值 | 快门 | ISO | 焦距 | 分辨率）
- **新增**：双击 EXIF 区域或右键菜单复制 EXIF 信息
- **新增**：中英文语言切换（右上角下拉菜单，实时切换，无需重启）
- **新增**：单击缩略图/列表行显示 EXIF
- **新增**：双击缩略图跳转资源管理器定位文件
- **新增**：预览区滚动自动回到顶部（切换文件夹后）
- **修复**：RAW 文件 EXIF 解析（内嵌 TIFF 解析，缺失字段显示 "--"）
- **优化**：缩略图缓存、多核并行处理，提升扫描与加载速度
- **优化**：软件体积缩减 40%（26.7 MB → 16.2 MB），内存占用降低，启动更快

**v3.6**
- **新增**：状态条固定（不再随滚动移动）
- **新增**：卡片等比缩放（保持图片比例不变形）
- **新增**：模式切换不丢图（切换删除方式后缩略图保留）
- **新增**：EXIF 懒加载（按需加载，减少启动耗时）
- **新增**：RAW EXIF 支持（内嵌 TIFF 解析）

**v3.5**
- **新增**：EXIF 信息显示（单击列表行或缩略图查看）
- **新增**：缩略图缓存与多核并行（大幅提升加载速度）
- **修复**：预览区滚轮卡顿
- **修复**：快速拖动滑块缩略图层叠
- **修复**：上传后文件名变为 default 的问题

**v3.3**
- **新增**：关于窗口加大
- **移除**：手动选择按钮与锁定逻辑

**v3.2**
- **新增**：自动识别显示修正
- **新增**：强制删除
- **新增**：滑块吸附

**v3.1**
- **新增**：网格预览
- **新增**：缩略图三档大小
- **新增**：自动识别锁定

**v3.0**
- **新增**：自动识别
- **新增**：格式不符保护
- **新增**：配置记忆

**v2.0**
- **新增**：多 RAW 格式支持
- **新增**：递归扫描

**v1.0**
- **新增**：基础 RAW / JPG 筛选删除
---

## 👨‍💻 作者 / Author

- **KILL-STAR SX**
- GitHub: [KILLSTARSX](https://github.com/KILLSTARSX)
- 哔哩哔哩 / Bilibili: [KILL-STAR_SX](https://space.bilibili.com/381623593)

---

## 📄 许可证 / License

本项目采用 **MIT License** 开源协议。  
This project is licensed under the **MIT License**.

---

## ⭐ 如果觉得有用，欢迎点个 Star！

[![Star History](https://img.shields.io/github/stars/KILLSTARSX/JPG-RAW_OrphanCleaner?style=social)](https://github.com/KILLSTARSX/JPG-RAW_OrphanCleaner/stargazers)
[![Fork](https://img.shields.io/github/forks/KILLSTARSX/JPG-RAW_OrphanCleaner?style=social)](https://github.com/KILLSTARSX/JPG-RAW_OrphanCleaner/forks)

# 📷 JPG-RAW_孤立文件清理器 (JPG-RAW_OrphanCleaner)
相机照片筛选工具：自动清理 JPG+RAW 双格式中的孤立文件，支持 15+ 相机厂商品牌，移入回收站可恢复 / Automatically find and delete orphaned JPG/RAW files, supports 15+ camera brands, moves to Recycle Bin.

## ✨ 功能亮点

- 🧠 **智能识别**：自动检测文件夹内的 RAW 格式，支持 **15+ 相机品牌**（松下、佳能、尼康、索尼、富士等）
- 📂 **递归扫描**：支持扫描子文件夹（可选层级），跨文件夹配对相同基础名的文件
- 🖼️ **缩略图预览**：JPG 显示缩略图，RAW 显示后缀占位框，支持大小调节
- 🗑️ **安全删除**：所有文件移入 **Windows 回收站**，可随时还原，绝不永久删除
- ⚙️ **配置记忆**：自动记住上次使用的文件夹、格式、扫描层级等设置
- 🖱️ **便捷操作**：双击列表文件可定位到资源管理器，单击表头可排序
- 🛡️ **格式保护**：检测到 RAW 格式与所选品牌不符时，自动提示并阻止误删

---

## 🚀 快速开始

### 下载安装

1. 前往 **[Releases 页面](https://github.com/KILLSTARSX/JPG-RAW_OrphanCleaner/releases/latest)** 下载最新版本软件
2. 双击运行，无需安装任何额外软件（适用于 Windows 10 / 11）

### 基本使用

1. 点击 **"浏览…"** 选择照片文件夹 → 程序自动开始扫描
2. 查看文件列表和预览区，确认孤立文件
3. 选择删除方式（只删 JPG / 只删 RAW / 全部删除）
4. 点击 **"确认删除"**，文件移入回收站

> 📖 详细使用说明请参考压缩包内的 `使用说明书.txt`

---

## 📸 支持的相机品牌与 RAW 格式

| 品牌 | RAW 后缀 |
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
| 理光 Ricoh / 徕卡 Leica | .DNG |
| 哈苏 Hasselblad | .3FR |
| 飞思 Phase One | .IIQ |
| 玛米亚 Mamiya | .MEF |
| 利图 Leaf | .MOS |

---

## ⚠️ 安全说明

- 本工具**只使用 Windows 回收站 API**（`send2trash` / `SHFileOperation + FOF_ALLOWUNDO`）
- **不存在任何永久删除操作**，所有文件均可从回收站还原
- 删除过程中单个文件失败不会中断整体流程，失败原因会明确列出

---

📝 更新日志
v3.3：关于窗口加大、移除手动选择按钮与锁定

v3.2：自动识别显示修正、强制删除、滑块吸附

v3.1：网格预览、缩略图三档、自动识别锁定

v3.0：自动识别、格式不符保护、配置记忆

v2.0：多 RAW 格式支持、递归扫描

v1.0：基础 RAW / JPG 筛选删除


⭐ 如果觉得有用，欢迎点个 Star！

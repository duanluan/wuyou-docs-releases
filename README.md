# 无尤文档

本地优先的跨平台文档与笔记软件，支持块编辑、表格、图片、代码块、搜索、导入导出和多平台桌面安装。

[下载最新版](https://github.com/duanluan/wuyou-docs-releases/releases/latest) · [AUR 安装](https://aur.archlinux.org/packages/wuyou-docs-bin) · [查看发布记录](https://github.com/duanluan/wuyou-docs-releases/releases) · [提交反馈](https://github.com/duanluan/wuyou-docs-releases/issues)

## 主要功能

无尤文档适合用来整理个人知识库、项目资料、技术文档、会议记录、学习笔记和图文资料。它以本地工作区为基础，尽量让文档管理、内容编辑和资料迁移都保持直接、清晰。

### 本地工作区与文档管理

- 本地优先：选择电脑上的本地目录作为工作区，文档数据优先保存在本机。
- 多工作区：支持创建、打开和切换工作区，适合把个人、工作、项目资料分开管理。
- 文档树：支持创建文档和文件夹，并可重命名、删除、展开收起和拖拽排序。
- 桌面体验：提供窗口状态恢复、保存状态提示、侧边栏宽度调整和标题栏交互优化。

### 块编辑与排版

- 块级编辑：支持段落、标题、Todo、引用、分割线、链接、图片、代码块等内容块。
- 快捷输入：支持斜杠菜单和常见 Markdown 快捷输入，减少频繁切换鼠标和键盘。
- 内容整理：支持内容块拖拽移动，方便调整文档结构和整理长文档。
- 页宽设置：支持默认、较宽、全宽三档页面宽度，适配阅读、编辑和大屏场景。

### 表格、图片与代码

- 表格块：支持表格编辑、单元格内容输入、横向滚动、列宽调整和行高自适应。
- 表格内容：表格单元格中可以插入图片、代码块等内容，适合整理结构化资料。
- 图片编辑：支持图片插入、查看、保存、多图排版、拖拽重排和图片描述输入。
- 代码块：支持语法高亮、语言选择、复制、软换行和高度调整。
- Mermaid：支持 Mermaid 代码块图形预览，并可在图形和源码之间切换。

### 思维导图、搜索与导入导出

- 思维导图：支持可视化思维导图块、节点编辑、拖拽、搜索、概要、缩略图导航、属性面板和导出。
- 搜索替换：支持工作区搜索、文档内搜索和替换，搜索结果会高亮显示并可点击定位。
- 导入导出：支持 Markdown、HTML 导入导出，也支持导出包含本地资源的 Markdown 资源包。
- 多语言界面：支持简体中文、繁体中文、英语、日语、德语、法语、俄语、西班牙语、意大利语、波兰语和葡萄牙语等界面语言。
- 应用内更新：支持在设置中检查更新，Windows、macOS 和 Linux 用户都可以获取新版本提示。

## 下载最新版

请优先从 [Latest Release](https://github.com/duanluan/wuyou-docs-releases/releases/latest) 下载与你的系统匹配的安装包。

| 系统 | 推荐下载 | 说明 |
| --- | --- | --- |
| Windows x64 | `wuyou-docs_版本号_x64-setup.exe` | 推荐普通用户使用 |
| Windows x64 | `wuyou-docs_版本号_x64_zh-CN.msi` | 适合需要 MSI 安装包的用户 |
| macOS Apple Silicon | `wuyou-docs_版本号_aarch64.dmg` | 适用于 M 系列芯片 Mac |
| macOS Intel | `wuyou-docs_版本号_x64.dmg` | 适用于 Intel 芯片 Mac |
| Linux x86_64 | `wuyou-docs_版本号_amd64.AppImage` | 推荐普通 Linux 用户使用 |
| Linux x86_64 | `wuyou-docs_版本号_amd64.deb` / `wuyou-docs-版本号-1.x86_64.rpm` | 适用于 deb/rpm 系发行版 |
| Arch Linux / Manjaro | [`wuyou-docs-bin`](https://aur.archlinux.org/packages/wuyou-docs-bin) | 推荐通过 AUR 安装，例如 `paru -S wuyou-docs-bin` 或 `yay -S wuyou-docs-bin` |
| Linux arm64 | `wuyou-docs_版本号_aarch64.AppImage` | 适用于 arm64 Linux |
| Linux arm64 | `wuyou-docs_版本号_arm64.deb` / `wuyou-docs-版本号-1.aarch64.rpm` | 适用于 arm64 deb/rpm 系发行版 |

`latest.json` 和 `.app.tar.gz` 文件用于应用内更新，普通用户通常不需要手动下载。

## 更新方式

- 应用内更新：在设置中检查更新，并按提示安装新版本。
- AUR 安装：Arch Linux / Manjaro 用户可通过 `paru -Syu wuyou-docs-bin` 或 `yay -Syu wuyou-docs-bin` 更新。
- pacman 本地安装：通过系统包管理器更新，或下载新版安装包后使用 `pacman -U` 覆盖安装。
- 手动安装：从 [Releases](https://github.com/duanluan/wuyou-docs-releases/releases) 下载新版安装包后覆盖安装。

## 反馈问题

如果遇到 Bug、安装问题或有功能建议，请在 [Issues](https://github.com/duanluan/wuyou-docs-releases/issues) 提交反馈。

提交前请尽量附上：

- 应用版本
- 操作系统与版本
- 安装方式
- 复现步骤
- 截图或日志

## 仓库用途

这个仓库用于发布无尤文档安装包、版本说明，以及收集 Bug 反馈与功能建议。

# 🏠 御坂小屋

> 一个记录技术踩坑与实践的 Linux / 嵌入式 / 网络笔记站。

[![Hexo](https://img.shields.io/badge/Hexo-7.3.0-0e83cd?logo=hexo)](https://hexo.io/)
[![Theme Butterfly](https://img.shields.io/badge/Theme-Butterfly-ff69b4)](https://github.com/jerryc127/hexo-theme-butterfly)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-222?logo=github)](https://zoeget.github.io/ZoeWu)

---

## 📖 关于本站

**御坂小屋**是我的个人技术博客，专注于 **Linux 系统管理**、**计算机网络** 与 **嵌入式开发** 三大方向，也会记录一些开发工具、博客部署和真实排坑过程。

文章全部来源于实际项目与工作学习中的真实记录。命令、配置、脚本和硬件驱动都尽量保持可复现、可验证，方便以后自己回看，也希望能帮到遇到同样问题的人。

站点使用 [Hexo](https://hexo.io/) 静态博客框架搭建，搭配 [Butterfly](https://github.com/jerryc127/hexo-theme-butterfly) 主题，部署在 GitHub Pages 上。

## 📂 内容分类

- **Linux 运维**：常用命令、软件包管理、进程管理、计划任务、日志管理、系统调优、远程控制等。
- **数据通信 / 网络**：NAT、TCP 三次握手与四次挥手、eNSP 模拟器问题处理等。
- **嵌入式开发**：1.8 寸 TFT 屏幕驱动、HAL 库、ST7735、SPI 显示相关内容。
- **博客与工具**：Hexo 写作流程、Git 提交报错、Hexo 部署报错、Codex 快捷方式脚本、OpenSpec 部署等。
- ……持续更新中

## 🗂️ 文章索引

### Linux 运维

- **Linux常用命令**：Linux 基础命令、文件目录、文本处理和系统管理速查。
- **Linux内核优化**：Linux 内核参数优化记录。
- **rpm 应用程序的安装与管理**：RPM 软件包安装、查询、卸载与管理。
- **YUM**：YUM 软件包管理基础操作。
- **VIM编辑器**：VIM 常用模式、编辑命令和基础用法。
- **nmcli 网络管理**：使用 `nmcli` 管理网络连接和网卡配置。
- **远程控制**：Linux 远程连接和远程管理笔记。
- **进程管理**：`ps`、`top`、后台任务、`kill`、`killall`、`pkill` 等进程管理命令。
- **进程优先级**：Linux 进程优先级相关操作。
- **计划任务**：定时任务和计划任务配置。
- **日志管理**：Linux 日志管理基础记录。
- **系统调优**：系统调优相关配置和命令。
- **开机破解密码：系统启动过程和启动目标**：系统启动流程、启动目标和密码恢复相关内容。

### 数据通信 / 网络

- **NAT 网络地址转换**：NAT 基础概念和应用场景。
- **TCP协议三次握手与四次挥手**：TCP 位码、常用端口、三次握手和四次挥手过程。
- **Ensp模拟器中交换机无法启动，命令行界面只显示The device is running的解决办法**：eNSP 交换机启动异常排查。

### 嵌入式开发

- **1.8寸TFT屏幕驱动 HAL库 （ST7735）**：ST7735 屏幕硬件连接、SPI 初始化、驱动函数、颜色格式、常见问题和完整源码。

### 博客搭建 / Git / 工具

- **HEXO写作流程**：Hexo 新建文章、Front-matter、图片资源、本地预览、生成部署和源码备份流程。
- **Git提交报错Author identity unknown解决办法**：配置 `user.name` 和 `user.email` 解决 Git 提交身份未知问题。
- **Hexo部署报错detected dubious ownership解决办法**：通过 `safe.directory` 或重建 `.deploy_git` 解决 Hexo 部署时的 Git 安全目录问题。
- **Codex更新桌面快捷方式PowerShell脚本**：为 Microsoft Store 版 Codex 重新创建桌面快捷方式的 PowerShell 脚本。
- **OpenSpec部署**：OpenSpec 安装、初始化、验证、目录结构和实践建议。

## ✍️ 写作风格

- **实战驱动**——不写空泛复述，优先记录自己验证过的操作、命令、配置和脚本。
- **结构清晰**——每篇文章用 `##` / `###` 分级展开，表格归纳端口、选项、引脚和步骤，方便速查。
- **真实排坑**——遇到过的 Bug 和解决过程完整记录，尽量保留问题原因、解决命令和验证方式。

## 🧱 站点构建

| 层 | 技术 |
|----|------|
| 框架 | [Hexo](https://hexo.io/) v7.3.0 |
| 主题 | [Butterfly](https://github.com/jerryc127/hexo-theme-butterfly) v5.5.1 |
| 部署 | GitHub Pages + hexo-deployer-git |
| 搜索 | hexo-generator-search 本地搜索 |
| 图片管理 | hexo-filter-image + post_asset_folder |
| 语法高亮 | highlight.js |

## 🚀 常用命令

```bash
hexo clean
hexo g
hexo s
hexo d
```

## 📄 许可

本博客文章采用 **CC BY-NC 4.0** 许可协议。转载请注明出处，禁止商用。

---

**御坂小屋** —— 记录技术，分享经验。

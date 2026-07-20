# Sony ZV-E1 Master

An official-documentation-first Codex skill for the Sony **ZV-E1 camera body**. It uses the local Sony Help Guide for stable operational questions and rechecks Sony's official web sources for information that may change.

## What It Covers

- Menu paths, shooting modes, autofocus, subject recognition, exposure, Log/LUT, audio, and streaming
- Product Showcase, Background Defocus, Cinematic Vlog, Auto Framing, and Framing Stabilizer
- Memory cards, lenses, batteries, USB-PD, Wi-Fi/Bluetooth, USB/HDMI, and phone or computer connections
- Specifications, defaults, warning messages, troubleshooting, and the 4K 120p upgrade license

Answers retain exact English menu labels for searchability and include relevant prerequisites, limitations, and official sources.

## Installation

Place this directory in Codex's global skills directory:

```bash
git clone https://github.com/JamieBai10/sony-zve1-master.git \
  ~/.codex/skills/sony-zve1-master
```

Alternatively, copy `SKILL.md`, `references/`, and `agents/` from this repository to that location. Restart Codex or start a new task for the skill to be discovered.

## Official Manual Setup

This repository **does not include Sony's PDF manuals**. Obtain them from Sony's official support site and, by default, store them here:

```text
~/Downloads/sony zve1 manual/
├── manual.pdf       # 566-page Help Guide
└── 50508171M.pdf    # Startup Guide
```

If you use a different location, update the two local paths in [`references/sources.md`](references/sources.md). The same file includes hashes for confirming the source copies.

## Usage

Explicit invocation works in any task:

```text
Use $sony-zve1-master: How do I configure Product Showcase on the ZV-E1?
```

You can also ask a ZV-E1 body question directly; the skill can be matched automatically. For example:

- “How do I enable USB streaming on the ZV-E1? Include the exact menu path and restrictions.”
- “What must be in place before recording 4K 120p?”
- “What USB-PD specification does Sony recommend for charging?”
- “Why is this menu item disabled? Troubleshoot it using official documentation only.”

## Sources and Freshness

- Operations, menus, safety, specifications, and troubleshooting: search the local Help Guide first.
- Firmware, downloads, product alerts, compatibility, warranty, Creators' App/Cloud, and licensing: check Sony's official web pages in the same answer.
- For lenses, microphones, mount adapters, and third-party accessories, consult the exact accessory's official documentation too. This skill does not infer compatibility from a matching mount or connector alone.

See [`references/sources.md`](references/sources.md) for the full source registry, topic map, and official URLs.

## Contributions and Scope

Contributions that improve workflows or documentation are welcome. Do not commit Sony manuals, copyrighted full-text material, or unsupported claims. This skill focuses on the **ZV-E1 camera body** and does not present unverified information as fact.

---

## 中文版

面向 Sony **ZV-E1 机身**的 Codex skill。它要求回答以 Sony 官方资料为依据：本地 Help Guide 用于稳定的操作与设置问题；可能更新的项目则在回答时复核 Sony 官方网页。

### 能解决什么问题

- 菜单路径、拍摄模式、自动对焦、主体识别、曝光、Log/LUT、音频与串流
- Product Showcase、背景虚化、Cinematic Vlog、Auto Framing、Framing Stabilizer
- 存储卡、镜头、电池、USB-PD、Wi-Fi/蓝牙、USB/HDMI、手机与电脑连接
- 规格、默认值、警告信息、故障排除和 4K 120p 升级许可证

回答会保留可检索的英文菜单名称，并在适用时给出前提条件、限制和官方出处。

### 安装

将此目录放到 Codex 的全局 skills 目录：

```bash
git clone https://github.com/JamieBai10/sony-zve1-master.git \
  ~/.codex/skills/sony-zve1-master
```

或将本仓库的 `SKILL.md`、`references/` 和 `agents/` 目录复制到同一位置。重启 Codex 或新建任务后即可发现该 skill。

### 配置官方手册

此仓库**不包含 Sony 的 PDF 原件**。请自行从 Sony 官方支持页取得资料，并默认放在：

```text
~/Downloads/sony zve1 manual/
├── manual.pdf       # 566 页 Help Guide
└── 50508171M.pdf    # Startup Guide
```

若放在其他位置，请修改 [`references/sources.md`](references/sources.md) 中的两个本地路径。文件哈希也写在该索引内，便于确认你使用的是同一份资料。

### 使用方法

可在任意任务中明确调用：

```text
使用 $sony-zve1-master：怎样设置 ZV-E1 的 Product Showcase？
```

也可直接提出 ZV-E1 机身相关问题，skill 会根据触发描述自动匹配。示例：

- “ZV-E1 怎么开启 USB 串流？请给我准确菜单路径和限制。”
- “拍 4K 120p 前需要满足什么条件？”
- “用 PD 充电时官方推荐什么规格？”
- “为什么某个菜单是灰色的？请仅按官方手册排查。”

### 资料与时效性

- 操作、菜单、安全、规格和故障排除：优先检索本地 Help Guide。
- 固件、下载、产品警示、兼容性、保修、Creators' App/Cloud 与许可证：在回答当次复核 Sony 官方网页。
- 对镜头、麦克风、转接环或第三方配件的问题，需再查该配件的官方资料；不会仅根据接口或卡口推断兼容性。

完整来源、主题索引和官方链接见 [`references/sources.md`](references/sources.md)。

### 贡献与边界

欢迎补充工作流或改善文档，但不要将 Sony 手册原件、受版权保护的全文内容或非官方结论提交到仓库。此 skill 聚焦 ZV-E1 **机身**；它不会将未获官方确认的信息表述为事实。

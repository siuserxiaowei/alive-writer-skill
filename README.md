# Alive Writer Skill — 活人感写作技能

<!-- SIUSER-REPO-GUIDE:START -->
## Repository Guide

### What This Repository Does

活人感写作 Skill：把 AI 写作、文案改写和内容人味化流程沉淀成技能。

English summary: Humanized writing skill for AI writing, copy editing, and more natural content workflows.

### Online Entry Points

- GitHub repository: https://github.com/siuserxiaowei/alive-writer-skill
- Live / GitHub Pages: not configured for this repository
- Default branch: `main`
- Primary language: `not specified`

### How To Read / Learn This Repository

1. 先读本 README，确认项目目标、在线入口和本地运行方式。
2. 优先查看 `SKILL.md`、`README.md` 和示例脚本，理解这个 skill 解决什么问题。
3. 如果要修改内容，先小范围改动，再运行本 README 中的验证命令。

### Clone This Repository

```bash
git clone https://github.com/siuserxiaowei/alive-writer-skill.git
cd alive-writer-skill
```

### Run Or View Locally

这个仓库没有检测到固定本地运行命令。通常可以直接阅读 README、源码、数据文件或线上页面；如需运行，请先查看仓库内的脚本和配置文件。

### Repository Map

| Path | Purpose |
| --- | --- |
| `README.md` | 项目入口说明，先读这里。 |
| `LICENSE` | 项目文件。 |
| `alive-writer/` | 项目目录。 |
| `articles/` | 项目目录。 |

### Maintenance Notes

- Keep this README in sync when the project purpose, live link, or run commands change.
- Prefer small, focused commits when changing code, data, or generated pages.
- Run the relevant build or validation command before publishing changes.
- If this is a generated/static archive, update the source data first, then regenerate the public files.

### Privacy And Safety

- Do not commit API keys, tokens, passwords, cookies, private URLs, or internal account data.
- Keep private source material out of public GitHub Pages output unless it has been explicitly cleared for publication.
- When in doubt, run a quick secret scan such as `rg -n "token|secret|password|access_key|authorization"` before pushing.
<!-- SIUSER-REPO-GUIDE:END -->

<!-- SIUSER-SEO-INTRO:START -->

## 项目介绍 / Project Introduction

**中文介绍**：活人感写作 Skill，用于把 AI 文本改得更自然、更有人味，适合公众号、小红书、推特和长文内容。

**English**: A human-sounding writing skill that makes AI-generated text more natural for articles, Xiaohongshu, X/Twitter, and long-form content.

**SEO 关键词 / SEO Keywords**: AI writing, humanized writing, copywriting, content creation, 活人感写作

<!-- SIUSER-SEO-INTRO:END -->

基于 176 篇「数字生命卡兹克」公众号原文逆向工程的写作 DNA 技能。

## 这是什么

Alive Writer 是一个 AI Agent Skill，通过分析超过 60 万字的公众号原文，提炼出一套可复用的写作风格系统。安装后，AI 可以用这种风格撰写公众号长文——带有强烈的「活人感」、口语化叙事、亲身实验式报道和文化升维。

## 核心特点

- **18 条写作 DNA**：从 176 篇文章中高频提取的风格规则
- **5 种文章原型**：调查实验、产品体验、现象解读、工具分享、方法论
- **三轮质检系统**：硬性扫描 → 风格校验 → 活人感终审
- **丰富的示例库**：全部从原文中提取的真实范例
- **完整的方法论**：选题、节奏、创意案例的系统方法

## 风格一句话

> 「一个见过世面但没有架子的朋友，正在认真跟你聊一件他刚亲手碰过的事。」

## 安装方式

### Claude Code
```bash
# 将 alive-writer 目录复制到 skills 目录
cp -r alive-writer ~/.claude/skills/
```

### 其他平台
将 `alive-writer/SKILL.md` 的内容作为自定义指令/系统提示词使用。

## 文件结构

```
alive-writer-skill/
├── README.md
├── LICENSE
├── alive-writer/
│   ├── SKILL.md                          # 核心技能文件
│   └── references/
│       ├── style_examples.md             # 风格示例库（176篇原文提取）
│       ├── content_methodology.md        # 内容方法论
│       └── topic_taxonomy.md             # 主题分类图谱
└── articles/                             # 20篇代表性原文
    ├── 01-淘宝上卖9块9的DeepSeek.md
    ├── 02-亲手给AI投毒之后.md
    ├── ...
    └── 20-Vibe_Coding的未来.md
```

## 致谢

本项目的灵感和方法论参考了 KKKKhazix 老师的开源 Skill 项目：

> **[KKKKhazix/khazix-skills](https://github.com/KKKKhazix/khazix-skills)** — 数字生命卡兹克开源的 AI Skills 合集

在此基础上，我们基于 176 篇公众号原文进行了独立的逆向工程分析，重新构建了风格系统、示例库和方法论框架。感谢 KKKKhazix 老师的开源精神和优质内容。

## 声明

本 Skill 由 [siuserxiaowei](https://github.com/siuserxiaowei) 与 Claude 基于公开发布的公众号文章进行风格分析后共同创建。所有引用的文章原文版权归原作者「数字生命卡兹克」所有。本项目仅供学习和研究使用。

## License

MIT

<!-- SIUSER-CONTACT:START -->

## 联系我 / Contact

想交流 AI 工具、内容自动化、SEO、私域增长或项目合作，可以扫码加我微信。

For collaboration on AI tools, content automation, SEO, private-domain growth, or product experiments, scan the WeChat QR code below.

<img src="https://raw.githubusercontent.com/siuserxiaowei/siuserxiaowei/main/assets/contact/wechat-qrcode.jpg" width="180" alt="WeChat QR code / 微信二维码" />

**关键词 / Keywords**: AI writing, humanized writing, copywriting, content creation, AI tools, AI automation, GitHub Pages, SEO

<!-- SIUSER-CONTACT:END -->

# Alive Writer Skill — 活人感写作技能

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

## 声明

本 Skill 由 [siuserxiaowei](https://github.com/siuserxiaowei) 与 Claude 基于公开发布的公众号文章进行风格分析后共同创建。所有引用的文章原文版权归原作者「数字生命卡兹克」所有。本项目仅供学习和研究使用。

## License

MIT

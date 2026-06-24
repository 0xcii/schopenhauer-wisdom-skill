# 人生的智慧 — Schopenhauer Wisdom Skill

> **叔本华《人生的智慧》核心体系** — 由 AI Agent 从全书 276 页中提取、整理、结构化为可调用的技能。

[![ClawHub](https://img.shields.io/badge/ClawHub-available-brightgreen)](https://clawhub.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Hermes Agent](https://img.shields.io/badge/Hermes%20Agent-compatible-blue)](https://hermes-agent.nousresearch.com)

---

## 这是什么

一个可加载到 AI Agent 的哲学技能包。加载后，Agent 可以：

- 调用叔本华的幸福三分法回答人生问题
- 用「人的自身 / 财产 / 表象」的框架帮你做决策
- 输出实用格言对抗焦虑、恐惧、嫉妒和内耗
- 合参你的命盘/处境，给出哲学层面的建议

>

## 安装

### 从 ClawHub 安装（推荐）

```bash
hermes skills install 人生的智慧
```

### 手动安装

```bash
git clone https://github.com/0xcii/schopenhauer-wisdom-skill.git
cp -r schopenhauer-wisdom-skill ~/.hermes/skills/philosophy/schopenhauer-wisdom/
```

## 使用

```bash
# CLI 加载
hermes -s 人生的智慧

# 会话中加载
/skill 人生的智慧

# 直接对话
加载 人生的智慧
```

### 示例对话

**你：** 我很焦虑，怕没钱。

**Agent：** 叔本华说——财富是抵御不幸的城墙，不是寻欢作乐的许可证。你把城墙当成了宫殿，所以永远不够。

**你：** 别人比我做得好，我嫉妒。

**Agent：** 叔本华说——人与人之间在第一项的差别是大自然定下来的。幸福在于你是什么，不是别人认为你是什么。

**你：** 我的 Agent 比他强，但我不想比了。

**Agent：** 叔本华说——不要比较。多想想处境比你更糟的人。幸福是健康 ×（自身内在价值 ÷ 欲望范围）。

## 技能内容

| 层次 | 内容 |
|:----:|:-----|
| 第一层 | 人生幸福的三大分类（自身 / 财产 / 表象） |
| 第二层 | 人的自身 — 愉快心情、健康、智力、品格 |
| 第三层 | 财富观 — 城墙理论、海水比喻 |
| 第四层 | 对待他人看法的态度 |
| 第五层 | 实用格言 30 条（认识自己、活在现在、控制想象、保持距离等） |
| 核心公式 | 幸福 = 健康 ×（自身内在价值 / 欲望范围） |

## 目录结构

```
schopenhauer-wisdom/
├── SKILL.md       # 主技能文件（五层核心体系）
├── README.md      # 本文档
├── LICENSE        # MIT 许可证
└── .gitignore
```

## 内容来源

- 叔本华《人生的智慧》（Aphorismen zur Lebensweisheit），1850 年
- 上海人民出版社，2005 年，译者序及全书 276 页
- 原载《附录与补遗》（Parerga und Paralipomena）

## 关于本技能

本技能由 [0xcii](https://x.com/0xcii) 基于原文整理，由 Hermes Agent 提取结构化。

**社交链接：**

| 平台 | 链接 |
|:----|:----|
| 🐦 X (Twitter) | [@0xcii](https://x.com/0xcii) |
| 📺 YouTube | [0xcii](https://youtube.com/@0xcii) |
| 💬 Telegram | [0xcii 频道](https://t.me/blockrun_ai) |
| 🤖 Hermes Agent | [hermes-agent.nousresearch.com](https://hermes-agent.nousresearch.com) |
| 📖 ClawHub | [clawhub.ai](https://clawhub.ai) |
| 🛒 CodeX 折扣 | [gamsgo.com/partner/JwUY7](https://www.gamsgo.com/partner/JwUY7) |

## 许可证

MIT — 自由使用、修改、分发。

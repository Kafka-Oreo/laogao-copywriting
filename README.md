# 老高文案写作引擎 (Laogao Copywriting)

一个把"复杂讲成好故事"的口语化写作方法引擎，基于 **老高与小茉** 真实口播文稿（《地球的一生》《三体》《海有多深》）蒸馏而成。适用于把任何选题改写成高留存、有悬念、口语化的自媒体文案——口播视频、科普图文、奇闻故事、财经投研。

> English: Laogao Copywriting Engine — a copywriting method distilled from the real narratives of "Laogao & Xiaomo", designed to turn any complex topic into compelling, suspenseful, conversational storytelling for short-video/listenable media.

## 这是什么 / What is this

不是复制老高这个人，而是复制他 **"把复杂讲成好故事"的写作操作系统**。专治自媒体文案三大病：

- 🔴 **开场没人看** → 钩子工程（反常识断言前置，3 秒留人）
- 🔴 **讲得太干巴** → 通俗类比引擎（抽象概念→桌面级日常物）+ 可视化叙事主轴
- 🔴 **结尾没记忆点** → 观点收束，落回"与我有关"

## 四大写作引擎 / Four Writing Engines

| 引擎 | 作用 | 一句话 |
|------|------|--------|
| 🪝 **钩子工程** | 开场三秒留人 | 反常识断言前置，绝不暖场 |
| 🎞 **叙事主轴** | 让观众有进度感 | 时间轴/空间轴/逻辑推演轴，六段式结构 |
| 🔁 **通俗类比引擎** | 把抽象变画面 | 宇宙级概念 → 桌面级日常物 |
| 🎙 **表达DNA** | 口语化即兴感 | "对不对？""你知道吗？"自问自答 + 互动张力 |

### 结构六段式 / Six-Part Structure

`悬念开场 → 主轴设定 → 层层递进 → 秘闻插叙 → 高潮收束 → 观点落地`

## 安装 / Installation

- **扣子 (Coze)**：下载 Release 中的 `laogao-copywriting-coze.zip` → 我的技能 → 创建技能 → 上传技能 → 选择 ZIP
- **支持 Skills 协议的平台** (Claude Code / Codex / Cursor 等 55+)：
  ```bash
  npx skills add Kafka-Oreo/laogao-copywriting
  ```
- **或直接克隆仓库**：把 `SKILL.md` 及 `references/` 作为技能文件导入

详细见 [INSTALL.md](INSTALL.md)

## 触发方式 / How to trigger

当你说 **"像老高那样写" "老高风格" "学老高写文案" "把XX讲成故事" "口播文案" "悬念开场"** 时，该引擎自动激活。

## 目录 / Structure

```
laogao-copywriting/
├── SKILL.md                    # 方法引擎主体（含回答工作流+四引擎+决策规则）
├── README.md
├── INSTALL.md                  # 3 种安装方式
├── LICENSE                     # MIT
├── icon.jpg
└── references/
    └── research/
        └── 01-copywriting-method.md   # 完整提炼表（每招附原文出处）
```

## 免责声明 / Disclaimer

本引擎提炼自三段公开口播文稿，代表老高的**叙事主流风格**；用于财经/投研类内容时，**表达可参考、事实须自行核实**，本引擎不生成/校验任何金融数据。非投资建议。

---

> 本 Skill 由 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 生成
> 商业使用请遵守 MIT 协议并保留署名。
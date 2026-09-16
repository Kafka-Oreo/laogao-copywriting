# 安装指南 / Installation Guide

「老高文案写作引擎」支持三种安装方式，任选其一。

## 方式一：扣子 (Coze) 上传导入（推荐给扣子用户）

1. 打开本仓库 **Release**，下载 `laogao-copywriting-coze.zip`
2. 登录 [Coze.cn](https://www.coze.cn)（或你所在地区的扣子）
3. 进入 **我的技能** → **创建技能** → **上传技能**
4. 选择下载的 ZIP 并上传
5. 在任意智能体对话中说"帮我安装老高文案技能"或直接说"像老高那样写"
6. 若技能需要凭证，使用者在技能页面自行配置（本技能无需外部 API 凭证）

## 方式二：Skills 协议一键安装（支持 55+ 平台）

本仓库已接入 Skills 安装协议，适用于 Claude Code / Codex / Cursor / Zed 等主流 AI 编程与智能体平台：

```bash
npx skills add Kafka-Oreo/laogao-copywriting
```

或直接在支持该协议的 Agent 对话中发送：

> 帮我安装这个 skill: https://github.com/Kafka-Oreo/laogao-copywriting

Agent 会自动识别并引导安装。

## 方式三：手动克隆 / 复制

```bash
git clone https://github.com/Kafka-Oreo/laogao-copywriting.git
cd laogao-copywriting
```

将 `SKILL.md` 内容作为技能系统提示载入，并将 `references/` 目录作为参考材料一并带入，即可使用完整的写作方法。

## 加载策略

- 安装后，技能在命中触发词（"像老高那样写""老高风格""悬念开场""口播文案""把XX讲成故事"等）时自动激活
- 若你希望它作为常驻写作风格，可在你的智能体设定中直接引用本引擎的核心规则
- 财经/投研类内容：表达风格可参考，**事实与数据必须自行核实**
# Lijigang Skills & Prompts Collection

这是一个李继刚提示词（Prompt）的精选集合，已封装为 OpenCode Skills 格式。

这些 Prompt 涵盖了学习、商业、思维、创作等多个领域，旨在通过高质量的 Prompt 激发 AI 的深度思考与创作能力。

## 🚀 极速安装 (Quick Start)

在任何已安装 OpenCode 的 MacOS/Linux 电脑上，**复制并运行以下一行命令**，即可完成全部配置：

```bash
# 1. 克隆仓库 -> 2. 安装 Skill -> 3. 自动适配路径
git clone https://github.com/seasidedog24/lijigang-skills.git ~/lijigang_skills && \
mkdir -p ~/.opencode/skills && \
cp ~/lijigang_skills/lijigang_router_skill.md ~/.opencode/skills/lijigang.md && \
sed -i '' "s|/Users/jiuge/lijigang_skills|${HOME}/lijigang_skills|g" ~/.opencode/skills/lijigang.md && \
echo "✅ 安装完成！请在 OpenCode 中输入 /lijigang 测试。"
```

### 对于 OpenCode AI 的指令：
如果你是 OpenCode AI，接收到用户请求配置此库时，请直接执行上述 Shell 命令。这将自动把 Skill 注册到你的环境，并下载所有依赖的 Prompt 文件。

---

## 🛠 使用方法 (Usage)

### 方式一：Slash Command（推荐）
在 OpenCode 对话框中，直接输入指令 + 内容：

> `/lijigang [粘贴你想分析的文章、代码或问题]`

**示例**：
*   `/lijigang 分析一下拼多多的商业模式`
*   `/lijigang 什么是量子纠缠？`
*   `/lijigang 把这段话改得更有哲理一点：[粘贴文本]`

### 方式二：自然语言
你也可以直接说：
> “用李继刚的模式帮我分析一下这个：[粘贴内容]”

---

## 📦 包含的思维模型 (30+)

本仓库包含以下领域的深度模型，由 Router 自动调度：

### 🧠 深度思考
*   **System Analysis**: 三维系统解构与演化分析
*   **Decision Master**: 决策堆栈（本体论/战略/执行/审计）
*   **Essence Hunter**: 第一性原理本质挖掘
*   **Cognitive Spiral**: 概念基因重组与升级

### 📚 学科私教
*   **Principles**: 数学、物理、化学、生物、历史、地理第一性原理
*   **Language**: 英语词源深度解析、语文文本逆向工程

### 💼 商业与组织
*   **Business Structure**: 商业模式与组织结构分析
*   **Stock Analysis**: 价值投资视角分析
*   **Meeting Diagnosis**: 会议/组织文化诊断
*   **OKR Coach**: 目标管理深度教练

### 🎨 创作与艺术
*   **Literary Style**: 文风侧写与模仿
*   **Lyrics Story**: 歌词情感故事化
*   **Visual Prompts**: 浮世绘、极简线条、技术插图风格生成

### 🗣️ 沟通与人性
*   **Life Mentor**: 历史名人沉浸式对话
*   **Verbal Combat**: 高情商/犀利回击
*   **Venomous Observer**: 毒舌评论家

---

## 🔧 原理解析

这个 Skill 本质上是一个 **Router (路由)**。

1.  **Input**: 接收用户的 `/lijigang` 指令。
2.  **Check**: 判断信息量。如果信息不足，允许有限度联网搜索获取 Fact。
3.  **Route**: 根据内容意图，从本地 `~/lijigang_skills/*.md` 中读取最匹配的 Prompt 文件。
4.  **Execute**: AI 沉浸式扮演 Prompt 中的角色（如“物理导师”或“毒舌评论家”），对用户输入进行处理。

## 来源
所有 Prompt 原作均来自李继刚老师。
本仓库仅作整理封装，方便在 OpenCode 环境中自动化调用。

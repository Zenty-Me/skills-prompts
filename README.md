# Skills & Prompts

AI 提示词与技能集合，用于辅助 AI 协同开发、文档处理等场景。

## 项目结构

```
skills-prompts/
├── prompts/          # 提示词模板
│   ├── AI协同开发架构师与提示词工程专家.md
│   └── OCR 与排版专家.md
└── skills/           # 技能定义
    └── karpathy-guidelines/
        └── SKILL.md
```

## 内容说明

### Prompts（提示词）

- **AI协同开发架构师与提示词工程专家** — 专注于软件项目全生命周期的 AI 协同开发，生成开发级提示词指导 AI 编码助手准确实现功能。
- **OCR 与排版专家** — 将图片中的非结构化视觉信息精准转化为结构化 Markdown 文档，支持数学公式 LaTeX 转换。

### Skills（技能）

- **Karpathy Guidelines** — 基于 Andrej Karpathy 观察总结的 LLM 编码行为准则，减少常见编码错误。

## 使用方式

将 `prompts/` 目录下的 Markdown 文件内容直接作为系统提示词或对话开头使用，适用于 Claude、ChatGPT 等 AI 助手。

`skills/` 目录下的技能文件可配合支持 Skill 加载的 AI 工具（如 Claude Code）使用。

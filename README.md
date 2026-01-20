# 🤖 Awesome Agent Skills

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

> 一个精选的 AI Agent 技能库。这里不仅有 Prompt，更有能够赋予 Agent 处理复杂任务能力的结构化技能（Skills）、工作流与工具组合。

---

## 🌟 什么是 Agent Skill?

Agent Skill 是一组结构化的指令、逻辑模式和工具定义，旨在扩展 AI Agent 的能力边界。与简单的对话 Prompt 不同，Skill 侧重于：
- **逻辑推理**：解决复杂问题的思维链条。
- **工具协同**：如何高效、准确地调用外部工具。
- **自我进化**：能够根据环境反馈调整执行策略。

---

## 📑 技能索引 (Skills Index)

### 🛠️ 核心能力 (Core Capabilities)
- [Humanizer-zh (人性化重写)](skills/humanizer-zh/) - 去除 AI 生成文本的痕迹，使其听起来更自然、更像人类。
- [PPT Generator Pro (PPT 生成)](skills/ppt/) - 基于 AI 自动生成高质量 PPT 图片和视频。
<!-- 待添加核心能力 -->

### 🧠 进阶工作流 (Advanced Workflows)
<!-- 待添加更多工作流 -->

---

## 🚀 如何使用 (Quick Start)

1. **探索技能**：在 `skills/` 目录中寻找你需要的技能。
2. **理解定义**：阅读每个技能文件夹下的 `SKILL.md`，了解其核心逻辑和工具要求。
3. **集成应用**：将指令集和工具定义集成到你的 Agent 配置文件（如 `.prompt` 或系统指令）中。

---

## 🤝 贡献指南 (Contributing)

我们欢迎社区提交更多高质量技能！
1. **参考模版**：使用 `templates/SKILL_TEMPLATE.md` 作为起点。
2. **规范提交**：确保技能包含核心指令、流程图 (Mermaid) 和至少一个示例。
3. **提交 PR**：在 `README.md` 中添加您的技能链接。

---

## 📜 开源协议 (License)

本项目采用 [MIT License](LICENSE)。

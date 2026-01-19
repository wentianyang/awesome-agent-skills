# Design: Project Structure & Standards

## Repository Structure
本项目遵循标准的 "Awesome List" 结构，并针对 Agent Skills 进行了微调。

```
awesome-agent-skills/
├── skills/                 # Skills 源代码
│   ├── <skill-name>/       # 独立的 Skill 包
│   │   ├── SKILL.md        #主要定义文件
│   │   └── ...             # 工具、资源、脚本
├── templates/              # 新 Skill 的模板
├── openspec/               # 项目管理 & Specs
└── README.md               # 入口 & 索引
```

## Skill Definition Standard
每个 Skill **必须**包含一个 `SKILL.md` 文件。
- **格式**：Markdown 格式，包含结构化章节（指令、工具、示例）。
- **可移植性**：Skills 应尽可能与平台无关，或明确遵循特定的 Agent 框架（例如创建 `.prompt` 文件或 OpenSpec 标准）。

## Documentation Standards
- **相对路径**：`README.md` 和其他文档中的所有链接 **必须** 是相对路径（例如 `skills/web-search/` 而不是 `file:///c:/...`）。
- **验证**：只能链接到仓库中实际存在的 Skills。

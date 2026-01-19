# Documentation Requirements

## ADDED Requirements

### Requirement: Relative Links in Documentation
`README.md` 和其他文档文件中的所有链接 **必须 (MUST)** 是相对路径，以确在不同环境下的可移植性。禁止使用绝对路径（例如 `file:///c:/...`）。

#### Scenario: 用户从 README 导航到 Skills
- **Given** (已知) 用户正在 GitHub 或本地克隆中查看 `README.md`
- **When** (当) 用户点击 "Skills Index" 中的 skill 链接时
- **Then** (则) 链接应正确导航到 `skills/` 内部对应的 skill 目录，且无错误。

### Requirement: Skill Existence Verification
`README.md` 索引中列出的任何 Skill **必须 (MUST)** 在 `skills/` 目录中存在。

#### Scenario: 用户检查列出的 Skills
- **Given** (已知) `README.md` 列出了一个名为 "Creative Writing" 的 Skill
- **When** (当) 系统验证链接时
- **Then** (则) 目录 `skills/creative-writing` 必须存在。

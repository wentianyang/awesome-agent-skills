# Change: Initialize Awesome Agent Skills

## Why
目前项目尚未初始化，文档中存在错误（如绝对路径、失效链接），且缺乏对 "Skills" 的明确定义。我们需要建立项目结构，定义什么是 Skill，并确保 README 准确无误，使其成为高质量的资源。

## What Changes
- **初始化项目**：更新 `openspec/project.md` 以包含真实的项目背景。
- **定义 Skills**：在提案和文档中正式定义 "Skills"（指令 + 工具 + 逻辑）。
- **修复文档**：
    - 移除 `README.md` 中的绝对文件路径。
    - 移除对不存在 Skill 的引用。
    - 说明如何使用相对路径。
- **标准**：通过新的 Spec 强制要求使用相对路径并验证 Skill 是否存在。

## Impact
- **受影响的 specs**：`documentation` (新增能力)。
- **受影响的代码**：`README.md`, `openspec/project.md`。

# Change: Add Gitignore

## Why
项目目前缺少 `.gitignore` 文件，这可能导致不必要的文件（如 `node_modules`, `.DS_Store`, 临时文件等）被提交到仓库中。添加此文件是标准开发实践，有助于保持仓库整洁。

## What Changes
- **Add File**: 在根目录创建 `.gitignore` 文件，包含常见的忽略规则。
- **Update Spec**: 在文档规范中添加对 `.gitignore` 存在性的要求。

## Impact
- **Affected specs**: `documentation` (MODIFIED).
- **Affected code**: `.gitignore`.

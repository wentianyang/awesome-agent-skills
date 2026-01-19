# Change: Remove Example Skills

## Why
用户指出 `Web Search` 和 `File Management` 并非真实的 Skills，要求将其删除。这可能是因为它们仅作为占位符或示例存在，不符合项目对高质量、真实可用 Skills 的标准。

## What Changes
- **Remove Skills**: 删除 `skills/web-search` 和 `skills/file-management` 目录。
- **Update Documentation**: 从 `README.md` 的索引中移除这两个 Skills 的条目。

## Impact
- **Affected specs**: 无 (尚未为这些 Skill 创建 Spec)。
- **Affected code**: `skills/` 目录，`README.md`。

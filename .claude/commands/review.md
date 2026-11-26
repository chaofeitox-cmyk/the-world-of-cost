---
description: 审查当前改动，输出问题清单
---

请审查当前分支相对 main 的改动（`git diff main...HEAD`，无 main 时用 `git diff`）：

1. 找出 bug、边界情况与安全问题；
2. 检查是否符合 `.claude/rules/` 中的规则；
3. 用表格输出：文件 | 行号 | 问题 | 严重程度 | 建议。

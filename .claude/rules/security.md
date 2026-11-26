# 安全规则 (Security)

- 绝不提交 secrets：API key、token、密码、`.env`、私钥等。
- 个人 / 私密配置放在 `CLAUDE.local.md` 或 `.claude/settings.local.json`（已在 .gitignore 中）。
- 读取 `.env` 等敏感文件前先确认必要性。
- 外部输入一律视为不可信，做校验与转义。
- 删除文件、改写历史等不可逆操作前先确认。

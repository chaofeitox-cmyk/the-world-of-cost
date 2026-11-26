# Git 工作流 (Git Workflow)

- 不直接提交到 main；在 feature branch 上开发。
- Commit message 使用 Conventional Commits：
  `feat:` / `fix:` / `docs:` / `refactor:` / `test:` / `chore:`
- 每个 commit 只做一件事，保持小而可回滚。
- 未经明确要求，不创建 Pull Request，不 force push。
- 云端 session 中，改动必须 commit 并 push，否则 container 回收后会丢失。

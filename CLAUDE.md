# CLAUDE.md

本文件是 Claude Code 的项目级说明（project memory），会在每个 session 开始时自动加载。
本地模式与 GitHub 云端模式都会读取它（前提：已 commit + push）。

## 项目概览 (Project Overview)

- 项目名称：the-world-of-cost
- 一句话描述：TODO - 用一句话说明这个项目解决什么问题
- 目标用户：TODO
- 当前阶段：TODO（例如 idea / MVP / production）

## 技术栈 (Tech Stack)

- Language：TODO
- Framework：TODO
- Package manager：TODO
- Database / Storage：TODO

## 常用命令 (Common Commands)

```bash
# install   TODO
# dev       TODO
# test      TODO
# lint      TODO
# build     TODO
```

## 目录结构 (Project Structure)

```
.
├── CLAUDE.md            # 本文件：项目总说明
├── .claude/
│   ├── settings.json    # 团队共享的权限 / hooks 配置
│   ├── rules/           # 分主题的规则文件（按需加载）
│   ├── commands/        # 自定义 slash commands
│   └── agents/          # 自定义 subagents
└── TODO                 # 源码目录
```

## 沟通偏好 (Communication)

- 回答以中文为主，技术关键词保留 English。
- 回答简洁、结构化，多用表格；必要时给出简短总结。
- 需求不清晰时，先用选项式（1、2、3）提问澄清，再动手。
- 决策类问题给出：Options / Pros / Cons / Recommendation。

## 工作规则 (Working Rules)

详细规则见 `.claude/rules/`：

- @.claude/rules/code-style.md
- @.claude/rules/git-workflow.md
- @.claude/rules/security.md

## 注意事项 (Gotchas)

- TODO：记录踩过的坑、特殊约定、不要修改的文件等。

# CLAUDE.md

本仓库用于写一本书，不是软件项目。每个 Claude Code session 开始时都会自动读取本文件。

## 这本书 (The Book)

- 暂定书名：The World of Cost（中文书名待定）
- 类型：非虚构 · 科普 / 大众读物
- 语言：中文（专业术语首次出现时可附英文）
- 目标读者：TODO（例如：对经济和生活好奇的普通读者）
- 核心问题：TODO（这本书想让读者看懂什么？）
- 当前阶段：只有想法 -> 下一步是一起确定主题、读者和大纲

## 关于作者 (About the Author)

- 作者是本仓库唯一的用户，也是这本书的唯一作者。
- 作者不熟悉 Git。所有 Git 操作由 Claude 负责，见 @.claude/rules/git-workflow.md。
- 与作者交流时用中文，语言要通俗，避免技术术语；如果必须提到某个技术术语，要顺便解释一句。
- 作者的想法不清楚时，用选项（1、2、3）提问，确认后再写。
- 涉及方向性决定（例如书名、结构、风格）时，给出：选项 / 优点 / 缺点 / 推荐。

## 文件结构 (Files)

```
.
├── CLAUDE.md              # 本文件：这本书的总说明
├── README.md              # 仓库首页简介
├── notes/
│   ├── progress.md        # 写作进度与下一步（每次 session 必读、必更新）
│   └── ideas.md           # 灵感、素材、待查资料
├── book/
│   ├── outline.md         # 全书大纲
│   └── chNN-标题.md       # 正文，一章一个文件，例如 ch01-一杯咖啡的成本.md
└── .claude/
    ├── rules/             # 写作风格、结构、Git 规则
    ├── commands/          # 快捷命令，例如 /save、/review-chapter
    └── agents/            # 专门的助手，例如 editor（审稿编辑）
```

## 工作方式 (How We Work)

1. 每次开始：先读 `notes/progress.md`，告诉作者上次做到哪里、建议的下一步是什么。
2. 写作时遵守：@.claude/rules/writing-style.md 和 @.claude/rules/book-structure.md
3. 每次结束，或完成一段有意义的工作后：更新 `notes/progress.md`，然后保存（commit + push）。
4. 云端 session 不会记住上一次对话，`notes/progress.md` 就是这本书的“记忆”，一定要及时更新。

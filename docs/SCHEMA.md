# Hermes-Wiki Schema

本文件夹采用 Zettelkasten 知识管理方法，配合 LLM 和 Obsidian 使用。

## 目录结构

```
Hermes-Wiki/
├── SCHEMA.md          # 本文件，定义规范
├── index.md           # 知识库首页/入口
├── log.md             # 操作日志，记录每次变更
├── raw/               # 原始资料（不修改）
│   ├── articles/      # 文章
│   ├── papers/        # 论文
│   ├── transcripts/   # 文字稿
│   └── assets/        # 图片等资源
├── concepts/          # 概念页面
├── entities/          # 实体页面
├── comparisons/       # 对比分析
├── queries/           # 问题与解答
├── moc/               # MOC (Map of Content) 主题地图
└── drafts/            # 草稿
```

## 命名规范

### 概念页面 (concepts/)
- 文件名：`lowercase-with-hyphens.md`
- 示例：`machine-learning.md`、`retrieval-augmented-generation.md`

### 实体页面 (entities/)
- 文件名：`Entity-Name.md`
- 示例：`Claude-Model.md`、`Obsidian-Software.md`

### MOC 页面 (moc/)
- 文件名：`moc-topic-name.md`
- 示例：`moc-ai-agents.md`、`moc-knowledge-management.md`

## 链接规范

使用双向链接：
- 链接到概念：`[[concept-name]]`
- 链接到实体：`[[Entity-Name]]`
- 链接到 MOC：`[[moc-topic-name]]`

## 标签规范

- 概念标签：`#concept`
- 实体标签：`#entity`
- MOC 标签：`#moc`
- 领域标签：`#domain/ai`、`#domain/coding` 等

## 更新日志

- 2026-05-05: 初始化 Hermes-Wiki

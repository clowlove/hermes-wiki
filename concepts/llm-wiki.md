---
tags:
  - concept
  - ai
  - knowledge-management
created: 2026-05-05
---

# LLM Wiki

## 定义

LLM Wiki 是将大型语言模型与 Wiki 系统结合的知识管理方案。

## 核心思想

让 AI 帮助你：
1. **读取** - 原始资料存入 raw/
2. **理解** - AI 分析内容
3. **拆分** - 自动生成概念页、实体页
4. **链接** - 创建双链关系
5. **可视化** - Obsidian 中查看知识网络

## 工作流

```raw/ → Hermes 读取 → 自动拆分 → Obsidian 可视化```

## 工具栈

| 组件 | 工具 |
|------|------|
| Agent | Hermes |
| 本地笔记 | Obsidian |
| 同步 | Git |
| 部署 | GitHub Pages |

## 相关

- [[concept-zettelkasten|Zettelkasten]]
- [[concept-hermes-agent|Hermes Agent]]

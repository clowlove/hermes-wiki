---
tags:
  - moc
  - hermes
created: 2026-05-05
---

# Hermes Agent MOC

## 概述

本 MOC 整理 Hermes Agent 相关的核心概念和配置方法。

## 核心概念

- [[concept-hermes-agent|Hermes Agent]] - AI Agent 框架
- [[concept-llm-wiki|LLM Wiki]] - LLM 知识管理方法
- [[concept-zettelkasten|Zettelkasten]] - 卡片盒笔记法

## 配置指南

### 环境变量

- `WIKI_PATH` - 指向 ~/Hermes-Wiki
- `HERMES_PROMPT` - Agent 系统提示词

### 工作流程

1. 放入原始资料到 `raw/` 目录
2. Hermes 读取并分析
3. 自动创建概念页、实体页
4. Obsidian 中查看双链知识网络

## 相关资源

- [Hermes GitHub](https://github.com/clowlove/hermes-wiki)
- [Obsidian 官网](https://obsidian.md/)

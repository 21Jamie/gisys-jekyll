# GISYS

Obsidian Notes Published with Jekyll + Netlify

## 访问网站

https://gisys.netlify.app

## 发布新笔记

### 方式 1：在 `_posts` 目录添加

文件格式：`YYYY-MM-DD-title.md`

```markdown
---
layout: post
title: "笔记标题"
date: 2026-02-05
---

你的笔记内容...
```

### 方式 2：在 `content` 目录添加

直接添加 `.md` 文件，文章会被自动索引。

## 工作流

1. 在 Obsidian 中编辑笔记
2. Obsidian Git → Commit → Push
3. Netlify 自动构建并发布

## 本地预览

需要 Ruby + Jekyll 环境：

```bash
bundle install
bundle exec jekyll serve
```

访问 http://localhost:4000

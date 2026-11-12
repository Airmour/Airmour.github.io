# Airmour 的博客

基于 Hugo + Stack，部署到 GitHub Pages。

## 写文章

在 `content/post/` 下新建 Markdown 文件，例如 `my-first-post.md`：

```markdown
---
title: "文章标题"
date: 2026-11-12T10:00:00+08:00
draft: false
categories: ["技术"]
tags: ["Android", "Kotlin"]
---

正文从这里开始。
```

提交并推送到 `main` 或 `master` 后，GitHub Actions 会构建并发布网站。

## 首次发布

1. 在 GitHub 仓库打开 **Settings → Pages**。
2. 将 **Build and deployment → Source** 设为 **GitHub Actions**。
3. 推送本地提交后，在 **Actions** 中查看 `Build and deploy` 工作流。

博客地址：<https://airmour.github.io/>。

Stack 主题通过 Hugo Modules 引入。v4 需要 Hugo 0.157.0 或更新版本；本仓库的 Actions 工作流已配置 Hugo 0.167.0。

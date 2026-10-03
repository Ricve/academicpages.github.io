---
permalink: /zh/markdown/
title: "指南"
author_profile: true
lang: zh
ref: guide
---

中英文用同一套模板，靠每篇内容开头的两个字段配对：

* `lang`：`en` 或 `zh`。没写时按英文处理。
* `ref`：同一篇内容的编号。语言按钮用它找到另一种语言。

顶栏文字在 `_data/navigation.yml`。每一项有英文的 `title` / `url`，以及中文的 `title_zh` / `url_zh`。

已经有中文页的位置：

| 内容 | 英文 | 中文 |
|---|---|---|
| 首页 | `/en/` | `/` |
| 简历 | `/cv/` | `/zh/cv/` |
| 论文列表 | `/publications/` | `/zh/publications/` |
| 报告列表 | `/talks/` | `/zh/talks/` |
| 教学列表 | `/teaching/` | `/zh/teaching/` |
| 作品列表 | `/portfolio/` | `/zh/portfolio/` |
| 博客列表 | `/year-archive/` | `/zh/year-archive/` |

列表页只显示当前语言的条目，所以中文论文列表现在是空的。给某篇英文稿补中文时，复制一份到同一目录，改 `lang: zh`、保持同一个 `ref`，并把 permalink 放到 `/zh/` 下。

主题自带的界面词（例如 Published、Tags）仍是英文。英文版的文件说明在 [Guide](/markdown/)。

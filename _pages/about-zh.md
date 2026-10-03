---
permalink: /
title: "关于"
excerpt: "中文首页"
author_profile: true
lang: zh
ref: home
redirect_from:
  - /zh/
---

这是站点的中文首页。顶栏里的「EN」会回到英文首页；英文页上的「中文」会回到这里。

侧栏姓名、简介和所在地写在 `_config.yml` 的 `author.name_zh`、`author.bio_zh`、`author.location_zh`。改完配置后需要重启本地服务。

论文、报告、教学、作品和博客目前还是英文示例。某一篇要提供中文版时，在同一目录再加一个 Markdown，写上相同的 `ref` 和 `lang: zh`，permalink 放在 `/zh/` 下面。例如英文论文是：

```yaml
lang: en
ref: paper-1
permalink: /publication/2026-10-03-my-paper
```

对应中文稿：

```yaml
lang: zh
ref: paper-1
permalink: /zh/publication/2026-10-03-my-paper
collection: publications
```

列表页只会显示当前语言的条目。没有对应译文时，语言按钮会回到该语言的首页。

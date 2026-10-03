---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
lang: en
ref: publications
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% include collection-archive.html collection="publications" reversed="true" %}

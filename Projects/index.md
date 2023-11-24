---
title: Projects
layout: post
---

Projects I've worked on or am working on.

{% for proj in site.categories.Projects %}

### [{{ proj.title }}]({{proj.url}})

{{proj.excerpt}}

{% endfor %}


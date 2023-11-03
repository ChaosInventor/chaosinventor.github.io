---
layout: home
---

This is where I put the technical stuff I've written. Have a look at all these
categories, and maybe read something:

{% for cat in site.categories %}

## {{ cat[0] }}

    {% for post in cat[1] %}

- [ {{ post.title }} ]( {{post.url }} )

    {% endfor %}

{% endfor %}

Or look at the chronology of posts:

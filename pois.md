---
layout: page
title: Λιμάνια
permalink: /pois/

---

![](/assets/images/start-page.png)

<ul>
  {% for p in site.pois %}
    <li>
      <a href="{{ p.url | relative_url}}">{{ p.title }}</a>
    </li>
  {% endfor %}
</ul>

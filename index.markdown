---
layout: default
title: Home
---

# Welcome to XOXDSEC

**Cybersecurity • Write-ups • DFIR • AppSec**

Welcome to my personal cybersecurity blog — where I document research, labs, and technical knowledge across:

- Threat Hunting
- DFIR
- AppSec
- CTF write-ups 
- Articles

---

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="color:gray;">({{ post.date | date: "%Y-%m-%d" }})</span>
    </li>
  {% endfor %}
</ul>

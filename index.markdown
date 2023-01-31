---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Asama
---

I am a full stack web developer who loves finding solutions to complex problems. If you need help on a project, reach out to me at asama.qureshi@gmail.com.

# Past Projects

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{post.date | date: '%Y-%m-%d'}} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
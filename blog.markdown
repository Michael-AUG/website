---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Blog
permalink: /blog/
---
# Recent blog posts and sermons are displayed below

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

![Image from UoG Handbook](media/handbook.webp)
<br>*Image courtesy of University of Glasgow Archives & Special Collections: Archives DC157*

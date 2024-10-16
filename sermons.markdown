---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Sermons
permalink: /sermons/
---
# Recent sermons are displayed below
As well as letting you read my sermons, you are also (in most cases) able to listen to a recording from when it was preached 'live'. Just click on the play button above where the sermon is displayed.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br>
      {% assign excerptParts = post.excerpt | split: "<!-- excerpt-start -->" %}
      {{ excerptParts[1] | strip_newlines | remove: "</p>" | remove: "<br>" | remove: "\n" | truncatewords: 50 }}
  {% endfor %}




Scriptural quotations from after 5th November 2023, unless otherwise stated, are from the English Standard Version (Anglicised).
Scriptural quotations from before 5th November 2023, unless otherwise stated, are from the King James Bible.

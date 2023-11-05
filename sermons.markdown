---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Sermons
permalink: /sermons/
---
<script>
function redirectToPage() {
  const currentDate = new Date();
  const dayOfWeek = currentDate.getDay();

  if (dayOfWeek === 0) {
    window.location.replace('https://www.topple.scot/sabbath');
  }
}

window.onload = redirectToPage;
</script>

# Recent sermons are displayed below
As well as letting you read my sermons, you are also (in most cases) able to listen to a recording from when it was preached 'live'. Just click on the play button above where the sermon is displayed.

![Michael mid-sermon at Dumfries Free Church of Scotland](media/michaelDumfries.jpg)
<br>*Michael, mid sermon, at Dumfries Free Church of Scotland - October 2023*

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {% assign excerptParts = post.excerpt | split: "<!-- excerpt-start -->" %}
      {{ excerptParts[1] | strip_newlines | remove: "</p>" | remove: "<br>" | remove: "\n" | truncatewords: 50 }}
  {% endfor %}

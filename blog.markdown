---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Blog and Sermons
permalink: /blog/
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

# Recent blog posts and sermons are displayed below

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

![Michael mid-sermon at Wattisfield URC](media/wattisfield_crop.jpg)
<br>*Michael, mid sermon, at Wattisfield United Reformed Church*

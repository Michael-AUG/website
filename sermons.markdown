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
Most sermons have a button to let you listen to a recording of the sermon. Look for it just below the title and above the picture.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

![Michael mid-sermon at Wattisfield URC](media/wattisfield_crop.jpg)
<br>*Michael, mid sermon, at Wattisfield United Reformed Church*

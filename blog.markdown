---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Blog and Sermons
permalink: /blog/
---

<html>
<head>
<script>

<!--
function initArray()
{
this.length = initArray.arguments.length;
for (var i = 0; i < this.length; i++)
this[i+1] = initArray.arguments[i];
}

var DOWArray = new
initArray("Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday");
var today = new Date();
var day = DOWArray[today.getDay()];
if (day == "Sunday") window.location = "https://www.topple.scot/sabbath"
//-->

</script>
</head>
</html>


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

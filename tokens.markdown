---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Communion Tokens
permalink: /tokens/
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

As well as various other things, I collect communion tokens. Communion tokens were used in most Scottish Churches (and churches in other countries around the world) to ensure that only the members were able to attend communion services and take the bread and wine.

Traditionally Communion season (which was celebrated quarterly) was preceded by a visit from your Elder. The Elder would distribute your token which you would then present on the Sunday for admission to the Lord's Table.

You can view my Communion tokens below:

{% include image-gallery.html folder="/media/tokens" %}

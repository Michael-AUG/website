---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Sermons
permalink: /sermons/
---
<script src="https://www.tbsonlinebible.com/verselinker.min.js" defer></script>
<script>
function redirectToPage() {
  const currentDate = new Date();
    const dayOfWeek = currentDate.getDay(); // 0 = Sunday, 1 = Monday, ..., 6 = Saturday

      if (dayOfWeek === 0) {
          // Redirect to the desired page on Sundays
              window.location.replace('/sabbath'); // Replace '/path/to/sunday-page' with the actual URL of your Sunday page
                }
                }

                // Call the function when the page loads
                window.onload = redirectToPage;
                </script>
# Recent sermons are displayed below

Sermons preached in APC Churches can be heard here (or further below)
<iframe tabindex="-1" width="1" height="540" src="https://embed.sermonaudio.com/browser/broadcaster/apc/speaker/michael%20topple/?sort=newest&page_size=25" style="min-width: 100%; max-width: 100%; " allow="autoplay" frameborder="0" scrolling="no"></iframe>

For sermons not preached in APCs, please see the list below: 
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br>
  {% endfor %}

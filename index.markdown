---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
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

![UoG_Undergrad_Banner](media/banner.webp)

<script src="https://www.biblegateway.com/votd/votd.write.callback.js"></script>
<script src="https://www.biblegateway.com/votd/get/?format=json&version=KJV&callback=BG.votdWriteCallback"></script>
<!-- alternative for no javascript -->
<noscript>
<iframe framespacing="0" frameborder="no" src="https://www.biblegateway.com/votd/get/?format=html&version=KJV">View Verse of the Day</iframe>
</noscript><br> 
<html>
    <label id="lblGreetings"></label>

![Michael at the University of Glasgow, overlooking the Kelvingrove](/media/ToppleKelvingrove.jpg)

<script>
    var myDate = new Date();
    var hrs = myDate.getHours();

    var greet;

    if (hrs < 12)
        greet = 'Good morning, or madainn mhath';
    else if (hrs >= 12 && hrs <= 17)
        greet = 'Good afternoon, or feasgar math';
    else if (hrs >= 17 && hrs <= 24)
        greet = 'Good evening, or feasgar math';

    document.getElementById('lblGreetings').innerHTML =
        '<b>' + greet + '!</b>';
</script>
</html>

My name is Michael and I live just south of Glasgow with my wife, Jackie, hail from Essex, and study Divinity at the University of Glasgow. I have been a preacher since 2018, and have been married to Jackie since 2021.

In my studies I have a particular interest in Reformation Theology, Church History, Presbyterian Practice, the role of the Church in 21st century Scotland and what Neurodiversity means to Christianity. My academic writing can be viewed on [my Academia page](https://glasgow.academia.edu/MichaelRJTopple).

I am a Fellow or Member of various Antiquarian and Theological Societies, and in my spare time enjoy [amateur radio](https://gm5aug.topple.scot), and driving my classic and vintage cars.

The title of this blog comes from the New Testament book 1 Timothy, chapter 4 verse 12, where the writer tells Timothy to let nobody look down on him because of his νεότητος (pronounced neo-tay-tos), or 'youth', because God has called him regardless of his age. I find this passage of Scripture an inspiration that has given me cause to pause and reflect on my personal sense of call to ministry - even though this ministry has not taken the form I once believed God wished it to. 

This website is where I upload my sermons, and occasional blog posts. The sermons are those preached at the various Churches I visit, while the blog posts are those written especially for the website.

In presenting this website I do not pretend to claim any special insight or intellect, but pray that as God inspired Timothy so too the words of my lips may be His words to our generation.

God bless,
*Michael*

![Moses at the Burning Bush](media/Moses.jpg)
*Illustration by Elizabeth Wang, R-60038-CW-V2, ‘Moses and the Burning Bush’, copyright © Radiant Light 2006, www.radiantlight.org.uk*

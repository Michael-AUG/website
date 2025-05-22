---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---
![Oban High Free Church](/media/pano.jpg)

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

> I have taken vows before You; <br>
>  to my God I will be true. <br>
> Sacrifices of thanksgiving <br>
>  I will gladly give to You. <br>
*Psalm 56. 12 (Sing Psalms)*

<script src="https://www.biblegateway.com/votd/votd.write.callback.js"></script>
<script src="https://www.biblegateway.com/votd/get/?format=json&version=NKJV&callback=BG.votdWriteCallback"></script>
<!-- alternative for no javascript -->
<noscript>
<iframe framespacing="0" frameborder="no" src="https://www.biblegateway.com/votd/get/?format=html&version=NKJV">View Verse of the Day</iframe>
</noscript><br> 

<html>
    <label id="lblGreetings"></label>

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

Welcome to my website, the purpose of which is to share my sermons with those who are interested in hearing them. It is my privilege to be a Christian, and a Deacon in [Dowanvale Free Church of Scotland](https://www.dowanvale.org). My paid employment is working as the Church Administrator at Dowanvale, while my wife Jacqueline volunteers as the Church Treasurer. Alongside my work I have studied part time with the [Edinburgh Theological Seminary](https://www.ets.ac.uk), having previously read for my BD (Bachelor of Divinity) degree at the [University of Glasgow](https://glasgow.ac.uk). I am not a minister of the Gospel, but preach as one who ["intend[s] the ministry" - see here](https://thewestminsterstandard.org/directory-for-the-publick-worship-of-god/#3)*. 

The name of this website is a reference to the words of Romans 10. 14:

> How then shall they call on Him in whom they have not believed? And how shall they believe in Him of whom they have not heard? And how shall they hear without a preacher? (NKJV)

Alongside my sermons, you will find a few articles I've written, and a brief introduction to one of my other hobbies: collecting Communion Tokens.

I hope that this website is a blessing to you, and that the Lord will speak to you through what you read or hear.

God bless <br>
Michael

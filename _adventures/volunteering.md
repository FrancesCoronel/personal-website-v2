---
title: "Volunteering 💖"
excerpt: "No one has ever become poor by giving. -Anne Frank"
permalink: /volunteering/
header:
  image: https://i2.wp.com/fvcproductions.files.wordpress.com/2015/12/img_2021.jpg
  teaser: https://i2.wp.com/fvcproductions.files.wordpress.com/2015/12/img_2021.jpg
comments: false
---

<div class="grid__wrapper">
    {% assign sorted_volunteering = (site.volunteering | sort: 'date') | reverse %}
    {% for post in sorted_volunteering %}
        {% include archive_item/single.html type="grid" %}
    {% endfor %}
</div>
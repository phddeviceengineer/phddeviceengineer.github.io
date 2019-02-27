---
permalink: /
title: "Things I learned as a PhD student"
excerpt: "Front page"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hopefully, we get to cover all of the awesome aspects in electrical engineering that I've got a bit of understanding ;).
![Awesome aspects in EE](/images/EE_map.PNG)

Recent Posts
------

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts limit:3 %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}

  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

<h2>Pages</h2>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

<h2>Posts</h2>
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

<h2>Code</h2>
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

{% capture written_label %}'None'{% endcapture %}



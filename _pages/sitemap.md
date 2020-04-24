---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of everything found on this site. There is an [XML version]({{ base_path }}/sitemap.xml) available as well.

<h2>Pages</h2>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

<h2>Teaching</h2>
{% for post in site.teaching %}
  {% include archive-single.html %}
{% endfor %}

<h2>Portfolio</h2>
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

<h2>Posts</h2>
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

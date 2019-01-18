---
layout: archive
permalink: hands-on-lab
title: "Hands on Lab Posts by Tags"
author_profile: true
header:
  image: "/images/danaukaolin.png"
---
{% include base_path %}
{% include group-by-array collection=site.posts fields="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive_subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}
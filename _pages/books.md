---
layout: archive
title: "Books and Book Chapters"
permalink: /books/
author_profile: true
---

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.books %}
  {% include archive-single.html %}
{% endfor %}

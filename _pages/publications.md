---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

My complete publication list is available on my <a href="https://scholar.google.com/citations?user=NgRN_6kAAAAJ&hl=en">Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

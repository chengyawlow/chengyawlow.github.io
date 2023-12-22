---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

Please find my complete publication list on <a href="https://scholar.google.com/citations?user=NgRN_6kAAAAJ&hl=en">my Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

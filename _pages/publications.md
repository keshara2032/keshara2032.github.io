---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- You can also find my articles on <a href="https://scholar.google.com/citations?user=HVANpX8AAAAJ&hl=en">my Google Scholar profile</a>. -->

{% include base_path %}

{% assign publications_by_date = site.publications | sort: 'date' | reverse %}
{% for post in publications_by_date %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <b><a href="https://scholar.google.com/citations?user=GTAWfXUAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</b>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

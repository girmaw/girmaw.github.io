---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=ZWfuPHUAAAAJ&hl=en) and on my [Microsoft Research page](https://www.microsoft.com/en-us/research/people/gtadesse/publications/).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

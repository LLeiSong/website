---
layout: archive
title: "Research Projects"
permalink: /projects/
author_profile: true
header:
  og_image: "projects/reconcile.png"
---

My research projects are fueled by a profound passion for biodiversity conservation and understanding the intricate dynamics of human-climate-wildlife relations.Through my research endeavors, I am dedicated to make contributions to the broader field of conservation and environmental management, providing valuable insights and innovative approaches to address pressing challenges in species conservation, human-wildlife interactions, and mitigating the ecological impacts of climate change and human disturbances.

Warmly welcome fellow researchers who share an interest in these areas to contact me for more information about past, ongoing and upcoming projects.

{% include base_path %}

{% assign ordered_pages = site.projects | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html %}
{% endfor %}

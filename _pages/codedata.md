---
layout: archive
title: "Code&Data"
permalink: /codedata/
author_profile: false
toc: true
---

### All code and scripts are host on [my personal GitHub](https://github.com/LLeiSong) or [SSELP group GitHub](https://github.com/SSELP).
{: .no_toc}

## Package

{% include base_path %}

{% assign ordered_pkg = site.codedata | sort:"order_number" %}

{% for post in ordered_pkg %}
  {% if post.label == "package" %}
    {% include archive-codedata.html %}
  {% endif %}
{% endfor %}

## Other code

{% assign ordered_pkg = site.codedata | sort:"order_number" %}

{% for post in ordered_pkg %}
  {% if post.label == "others" %}
    {% include archive-codedata.html %}
  {% endif %}
{% endfor %}

## Dataset

{% assign ordered_pkg = site.codedata | sort:"order_number" %}

{% for post in ordered_pkg %}
  {% if post.label == "dataset" %}
    {% include archive-codedata.html %}
  {% endif %}
{% endfor %}

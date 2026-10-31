---
layout: archive
permalink: /projects/
author_profile: true
---

Our team's research is driven by a shared commitment to biodiversity conservation and to understanding the complex dynamics among people, climate, and wildlife. Through our work, we aim to contribute to the broader fields of conservation and environmental management by developing new insights and innovative approaches to address pressing challenges in species conservation, human-wildlife interactions, and the ecological impacts of climate change and human activities.

{% include base_path %}

{% assign ordered_pages = site.projects | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-projects.html %}
{% endfor %}

## Student-led projects

### Mapping and forecasting coastal plant invasion

**Student lead:** Tianze Li (PhD student)

This project combines satellite imagery and deep learning to map and forecast *Spartina alterniflora* (now *Sporobolus alterniflorus*) invasion across China's coastal wetlands. Preliminary historical mapping uses a fine-tuned geospatial foundation model and Landsat imagery. Planned work will refine the maps and train a deep convolutional neural network to forecast subsequent spread, evaluate predictions against later observations and examine how mapping errors affect forecast reliability. The goal is to support targeted surveillance and control.

### Environmental differences and model transferability in *Sporobolus alterniflorus*

**Student lead:** Dylan Gong (Undergraduate student)

This project compares environmental conditions occupied by *Sporobolus alterniflorus* (formerly *Spartina alterniflora*) in its native and invaded ranges and examines how these differences relate to species distribution model transferability. A native-range Random Forest model and SHAP explanations quantify the contributions of climatic, tidal, soil, sediment and landscape variables across invaded regions. The hypothesis is that localized variables, such as relative tidal elevation differ more strongly between native and invaded habitats than broad-scale climate, while model transferability is strongly associated with environmental divergence.

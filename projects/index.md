---
title: Projects
nav:
  order: 2
  tooltip: Research projects and tools
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Our projects focus on integrative multimodal perception and intelligent systems, combining machine learning with heterogeneous data sources such as vision, audio, tactile sensing, and physiological signals. Applications span healthcare, assistive technologies, and real-world intelligent systems.

{% include tags.html tags="multimodal, perception, healthcare, deep learning, software, dataset" %}

{% include search-info.html %}

{% include section.html %}

## Featured Projects

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Other Projects

{% include list.html component="card" data="projects" filter="!group" style="small" %}

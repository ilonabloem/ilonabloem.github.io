---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
\* Equal author contributions

**Saturating Nonlinearities of Contrast Response in Human Visual Cortex**<br/>Vinke* LN, Bloem* IM, Ling S (2022). *Journal of Neuroscience*.<br/>[pdf](http://ilonabloem.github.io/files/papers/Vinke_etal_2022_JNeurosci.pdf) \| [data and code](https://osf.io/8g6ap/)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

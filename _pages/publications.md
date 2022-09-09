---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
\* Equal author contributions

**Saturating Nonlinearities of Contrast Response in Human Visual Cortex**<br/>Vinke* LN, Bloem* IM, Ling S (2022). *Journal of Neuroscience*.<br/>[pdf](http://ilonabloem.github.io/files/Vinke_etal_2022_JNeurosci.pdf) \| [data and code](https://osf.io/8g6ap/)

**The specificity of orientation-tuned normalization within human early visual cortex**<br/>Klímová M, Bloem IM, Ling S (2021). *Journal of Neurophysiology*.<br/>[pdf](http://ilonabloem.github.io/files/Klimova_etal_2021_JNeurophy.pdf) \| [data and code](https://osf.io/bcyp5/)

**Normalization governs attentional modulation within human visual cortex**<br/>Bloem IM, Ling S (2019). *Nature Communications*.<br/>[pdf](http://ilonabloem.github.io/files/Bloem_Ling_2019_NatCom.pdf) \| [data and code](https://osf.io/4qz37/)

**Visual memories bypass normalization**<br/>Bloem IM, Watanabe YL, Kibbe MM, Ling S (2018). *Psychological Science*.<br/>[pdf](http://ilonabloem.github.io/files/Bloem_etal_2018_PsychSc.pdf) 

**Attentional modulation interacts with orientation anisotropies in contrast perception**<br/>Bloem IM, Ling S (2017). *Journal of Vision*.<br/>[pdf](http://ilonabloem.github.io/files/Bloem_Ling_2017_JVision.pdf)

**The impact of interference on short- term memory for visual orientation**<br/>Rademaker RL, Bloem IM, De Weerd P, Sack AT (2015). *Journal of Experimental Psychology: Human Perception and Performance*.<br/>[pdf](http://ilonabloem.github.io/files/Rademaker_2015_JHPP.pdf) \| [data and code](https://osf.io/h684y/)

**Intensive tool-practice and skillfulness facilitate the extension of the human body schema beyond first order limitations**<br/>Rademaker RL, Wu D-A, Bloem IM, Sack AT (2014). *Neuropsychologia*.<br/>[pdf](http://ilonabloem.github.io/files/Rademaker_etal_2014_NeuroPsy.pdf) 

**Scrutinizing visual images: The role of gaze in mental imagery and memory**<br/>Laeng B, Bloem IM, D’Ascenzo S, & Tommasi L (2014). *Cognition*.<br/>[pdf](http://ilonabloem.github.io/files/Laeng_etal_2014_Cognition.pdf)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my publications on my [Google Scholar profile](https://scholar.google.com/citations?user=y15xf2wAAAAJ&hl=en){:target="_blank"}

*Denotes equal author contributions

**Normalization by orientation-tuned surround in V1-V3**<br/>Fang Z, Bloem IM, Olssen C, Ma WJ, Winawer J (2023). *bioRxiv*.<br/>[Link to paper](https://www.biorxiv.org/content/10.1101/2021.11.06.467486v3){:target="_blank"} \| [data and code](https://osf.io/vxjya/){:target="_blank"}

**Attention preserves the selectivity of feature-tuned normalization**<br/>Klímová M, Bloem IM, Ling S (2023). *Journal of Neurophysiology*.<br/>[Link to paper](https://doi.org/10.1152/jn.00194.2023){:target="_blank"} \| [data and code](https://osf.io/6tq8h/){:target="_blank"}

**Saturating Nonlinearities of Contrast Response in Human Visual Cortex**<br/>Vinke* LN, Bloem* IM, Ling S (2022). *Journal of Neuroscience*.<br/>[Link to paper](https://www.jneurosci.org/content/42/7/1292.abstract){:target="_blank"} \| [pdf](http://ilonabloem.github.io/files/Vinke_etal_2022_JNeurosci.pdf){:target="_blank"} \| [data and code](https://osf.io/8g6ap/){:target="_blank"}

**The specificity of orientation-tuned normalization within human early visual cortex**<br/>Klímová M, Bloem IM, Ling S (2021). *Journal of Neurophysiology*.<br/>[Link to paper](https://journals.physiology.org/doi/full/10.1152/jn.00203.2021){:target="_blank"} \| [pdf](http://ilonabloem.github.io/files/Klimova_etal_2021_JNeurophy.pdf){:target="_blank"} \| [data and code](https://osf.io/bcyp5/){:target="_blank"}

**Normalization governs attentional modulation within human visual cortex**<br/>Bloem IM, Ling S (2019). *Nature Communications*.<br/>[Link to paper](https://www.nature.com/articles/s41467-019-13597-1){:target="_blank"} \| [pdf](http://ilonabloem.github.io/files/Bloem_Ling_2019_NatCom.pdf){:target="_blank"} \| [data and code](https://osf.io/4qz37/){:target="_blank"}

**Visual memories bypass normalization**<br/>Bloem IM, Watanabe YL, Kibbe MM, Ling S (2018). *Psychological Science*.<br/>[Link to paper](https://journals.sagepub.com/doi/full/10.1177/0956797617747091){:target="_blank"} \| [pdf](http://ilonabloem.github.io/files/Bloem_etal_2018_PsychSc.pdf){:target="_blank"}

**Attentional modulation interacts with orientation anisotropies in contrast perception**<br/>Bloem IM, Ling S (2017). *Journal of Vision*.<br/>[Link to paper](https://jov.arvojournals.org/article.aspx?articleid=2653975){:target="_blank"} \| [pdf](http://ilonabloem.github.io/files/Bloem_Ling_2017_JVision.pdf){:target="_blank"}

**The impact of interference on short- term memory for visual orientation**<br/>Rademaker RL, Bloem IM, De Weerd P, Sack AT (2015). *Journal of Experimental Psychology: Human Perception and Performance*.<br/>[Link to paper](https://psycnet.apa.org/record/2015-36851-001){:target="_blank"} \| [pdf](http://ilonabloem.github.io/files/Rademaker_2015_JHPP.pdf){:target="_blank"} \| [data and code](https://osf.io/h684y/){:target="_blank"}

**Intensive tool-practice and skillfulness facilitate the extension of the human body schema beyond first order limitations**<br/>Rademaker RL, Wu D-A, Bloem IM, Sack AT (2014). *Neuropsychologia*.<br/>[Link to paper](https://www.sciencedirect.com/science/article/pii/S0028393214000232){:target="_blank"} \| [pdf](http://ilonabloem.github.io/files/Rademaker_etal_2014_NeuroPsy.pdf){:target="_blank"} 

**Scrutinizing visual images: The role of gaze in mental imagery and memory**<br/>Laeng B, Bloem IM, D’Ascenzo S, & Tommasi L (2014). *Cognition*.<br/>[Link to paper](https://www.sciencedirect.com/science/article/pii/S0010027714000043){:target="_blank"} \| [pdf](http://ilonabloem.github.io/files/Laeng_etal_2014_Cognition.pdf){:target="_blank"}


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

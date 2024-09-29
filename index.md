---
layout: default
---

<div id="bio_tab" class="tabcontent"  markdown=1>
## Patrick John Chia
I am  a founding engineer at a stealth startup in the AI x Gaming space, working on develpoing the cognitive architecture of agents using local, offline lanugage models. Previously I was at Coveo working with Dr Jacopo Tagliabue at the intersection of NLP, Information Retrieval and e-Commerce.

I completed my M.Eng at Imperial College, London and spent my final year at MIT working closely 
with Dr. Ferran Alet in the Learning and Intelligent Systems (LIS) Group.

My interests revolve around better understanding Artificial Intelligence (AI) of today, and
bridging the gap toward more human-like AI. 

I am also an active contributor to various open source initiatives ([Models](https://huggingface.co/patrickjohncyh/fashion-clip), [MLOps](https://github.com/jacopotagliabue/you-dont-need-a-bigger-boat), 
[RecList](https://github.com/jacopotagliabue/reclist)) and you can find my work at various academic and industrial CS/AI venues (ICML, ACL, TheWebConf, SIGIR, BerlinBuzzwords) too.

Last update: {{ site.time |  date: "%B %Y"  }}.
</div>


<div id="projects_tab" class="tabcontent" markdown=1>
## Projects | Research

{{  site.posts }}
</div>

<div id="publications_tab" class="tabcontent" markdown=1>
## Publications
{% for pub in site.publications %}
- {{ pub[1].author }} ({{ pub[1].year }}) [{{ pub[1].title }}]({{ pub[1].url }}), {{ pub[1].venue }}
{% endfor %}
</div>




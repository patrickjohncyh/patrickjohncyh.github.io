---
layout: default
---

<div id="bio_tab" class="tabcontent"  markdown=1>
## Patrick John Chia
I am currently an Applied Scientist @ Coveo working with Dr Jacopo Tagliabue at the intersection of NLP, 
Information Retrieval and e-Commerce.
Prior to this, I completed my M.Eng at Imperial College, London and spent my final year at MIT working closely 
with Ferran Alet (PhD) in the Learning and Intelligent Systems (LIS) Group.

My interests revolve around better understanding Artificial Intelligence (AI) of today, and
bridging the gap toward more human-like AI. This has involved research in multi-modal models such as CLIP, and 
the development of better evaluation approaches to popular ML use-cases such as Recommender Systems. 
On the flip-side, I have also ventured into AI in the _small data_ regime, combining ideas such Bayesian Lexical Learning
and Human-In-the Loop learning with dense representations.  

I am also an active contributor to various open source initiatives ([MLOps](https://github.com/jacopotagliabue/you-dont-need-a-bigger-boat), 
[RecList](https://github.com/jacopotagliabue/reclist))
and you can find my work at various academic and industrial CS/AI venues (ACL, TheWebConf, SIGIR, BerlinBuzzwords) too.

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




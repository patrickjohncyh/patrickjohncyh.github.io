---
layout: default
---

<div id="bio_tab" class="tabcontent"  markdown=1>
## Patrick John Chia
I am currently an Applied Scientist @ Coveo working with Dr Jacopo Tagliabue.
Prior to this, I completed my M.Eng at Imperial College, London and spent my final year at MIT working closely 
with Ferran Alet (PhD) in the Learning and Intelligent Systems (LIS) Group.

My interests revolve around better understanding Artificial Intelligence (AI) of today, and
bridging the gap toward more human-like AI. This has involved <GradREC, RecList> and exploring
<Lexical Learning ?>. I am also an active contributor to various open source initiatives <RecList>

You can find my work at various academic and industrial CS/AI venues (ACL, TheWebConf, SIGIR, BerlinBuzzwords).
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




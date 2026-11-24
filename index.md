---
layout: default
---

<div class="intro" markdown="1">

I am a researcher in computer science at the [University of Cagliari](https://web.unica.it/unica/en/dip_matinfo.page). My research interests<br> include formal verification, SMT solving, blockchain and smart contract security, DeFi,<br> neuro-symbolic AI, and automated reasoning.

</div>

<p class="contact">
  {%- for p in site.profiles %}
  <a href="{{ p.url }}">{{ p.title }}</a>
  {%- endfor %}
</p>

<div class="cols">
<div class="col" markdown="1">

## Projects and tools

{% include projects.html %}

<p class="more"><a href="{{ '/publications/' | relative_url }}">All publications</a></p>

</div>
<div class="col" markdown="1">

## Experience

{% include timeline.html items=site.data.experience.positions %}

## Education

{% include timeline.html items=site.data.experience.education %}

</div>
</div>

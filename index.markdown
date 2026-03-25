---
layout: default
title: M.Osawa's Website
---

{% include profile.html %}

<hr>

<h2>Research</h2>

<a href="/summary/">About my research</a>. 

<h3>Publications</h3>

See <a href="https://scholar.google.co.jp/citations?user=qKxF-dkAAAAJ" target="_blank">Google Scholar</a> for a chronological list. 

<ul class="ref-list pub-list">
  {% for paper in site.data.papers %}
    <li class="pub-item">
      {% include pub_item.html paper=paper %}
    </li>
  {% endfor %}
</ul>

<h3 style="margin-top: 1em">Discussion Papers</h3>

<ul class="ref-list">
    <li><a href="https://arxiv.org/abs/2207.05346">Origin of power laws and their spatial fractal structure for city-size distributions</a> (2024)<br> (with Tomoya Mori, Takashi Akamatsu, and Yuki Takayama)  [<a href="https://arxiv.org/pdf/2207.05346">paper</a>]</li>
    <li>Understanding regional dynamics (2025) [<a href="notes/draft/RD.pdf">paper</a>] [<a href="notes/draft/RD_slides.pdf">slides</a>]</li>
    <li><a href="https://arxiv.org/abs/2603.09539">Sampling logit equilibrium and endogenous payoff distortion</a> (2026) [<a href="notes/draft/SLD.pdf">paper</a>] [<a href="notes/draft/SLD_slides.pdf">slides</a>]</li>
    <li><a href="https://arxiv.org/abs/2011.06778">Most likely retail agglomeration patterns</a> (2025) (with Takashi Akamatsu and Yosuke Kogure)</li>
    <li><a href="https://arxiv.org/abs/2512.06402">Innovation, spillovers and economic geography</a> (2025) (with José Maria Gaspar)</li>
    <li><a href="https://arxiv.org/abs/2001.05095">Production externalities and dispersion process in a multi-region economy</a> (2021) (with José Maria Gaspar)</li>
</ul>

<hr>

{% include other.html %}
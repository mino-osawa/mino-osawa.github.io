---
layout: default
title: M.Osawa's Website
---

{% include profile.html %}

<hr>

<h2>Research</h2>

<a href="/summary/">About my research</a>. 

<h3>Featured Works</h3>

Please see <a href="https://scholar.google.co.jp/citations?user=qKxF-dkAAAAJ" target="_blank">Google Scholar</a> for a chronological list. 

<ul class="ref-list">
  {% for paper in site.data.papers %}
  {% if paper.keypub %}
    <li>
      {% if paper.url %}<a href="{{ paper.url }}" class="paper-title">{{ paper.title }}</a>{% else %}{{ paper.title }}{% endif %}. <br>
      <span class="pub-journal">{{ paper.journal }}</span>{% if paper.state %}, {{paper.state}}.{% endif %} ({{ paper.year }}) 
      {% if paper.pdf %}[<a href="{{ paper.pdf }}">paper</a>]{% endif %}{% if paper.misclinks %}{% for link in paper.misclinks %}
      [<a href="{{ link.url }}">{{ link.name }}</a>]{% endfor %}{% endif %}{% if paper.coauthors %} <br>
      (with {{ paper.coauthors | join: ', ' }}){% endif %}
    </li>
  {% endif %}
  {% endfor %}
</ul>

<h3>All Publications</h3>

Please see <a href="https://scholar.google.co.jp/citations?user=qKxF-dkAAAAJ" target="_blank">Google Scholar</a> for a chronological list. 

<ul class="ref-list">
  {% for paper in site.data.papers %}
  {% unless paper.keypub %}
    <li>
      {% if paper.url %}<a href="{{ paper.url }}" class="paper-title">{{ paper.title }}</a>{% else %}{{ paper.title }}{% endif %}. <br>
      <span class="pub-journal">{{ paper.journal }}</span>{% if paper.state %}, {{paper.state}}.{% endif %} ({{ paper.year }}) 
      {% if paper.pdf %}[<a href="{{ paper.pdf }}">paper</a>]{% endif %}{% if paper.misclinks %}{% for link in paper.misclinks %}
      [<a href="{{ link.url }}">{{ link.name }}</a>]{% endfor %}{% endif %}{% if paper.coauthors %} <br>
      (with {{ paper.coauthors | join: ', ' }}){% endif %}
    </li>
  {% endunless %}
  {% endfor %}
</ul>

<h3>Working Papers</h3>

<ul class="ref-list">
    <li><a href="https://arxiv.org/abs/2207.05346">Origin of power laws and their spatial fractal structure for city-size distributions</a> (2024) [<a href="https://arxiv.org/pdf/2207.05346">paper</a>] <br> (with Tomoya Mori, Takashi Akamatsu, and Yuki Takayama)</li>
    <li>Understanding regional dynamics (2025) [<a href="notes/draft/RD.pdf">paper</a>] [<a href="notes/draft/RD_slides.pdf">slides</a>]</li>
    <li><a href="https://arxiv.org/abs/2603.09539">Sampling logit equilibrium and endogenous payoff distortion</a> (2026) [<a href="notes/draft/SLD.pdf">paper</a>] [<a href="notes/draft/SLD_slides.pdf">slides</a>]</li>
    <li><a href="https://arxiv.org/abs/2011.06778">Most likely retail agglomeration patterns</a> (2025) (with Takashi Akamatsu and Yosuke Kogure)</li>
    <li><a href="https://arxiv.org/abs/2512.06402">Innovation, spillovers and economic geography</a> (2025) (with José Maria Gaspar)</li>
    <li><a href="https://arxiv.org/abs/2001.05095">Production externalities and dispersion process in a multi-region economy</a> (2021) (with José Maria Gaspar)</li>
</ul>

<hr>

{% include other.html %}
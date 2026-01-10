---
layout: default
title: M.Osawa's Website
---

{% include profile.html %}

<hr>

<h2>Research</h2>

<a href="/summary/">About my research</a>. 

<h3>Selected Discussion Papers</h3>

<ul class="ref-list">
    <li><a href="https://arxiv.org/abs/1912.05113">Spatial scale of agglomeration and dispersion: Number, spacing, and the spatial extent of cities</a> (2025)<br>(with Takashi Akamatsu, Tomoya Mori, and Yuki Takayama) [<a href="https://arxiv.org/pdf/1912.05113">paper</a>]
    <div class="note">Previous versions: 
    <ul class="ref-prev">
        <li><a href="https://www.rieti.go.jp/jp/publications/dp/17e125.pdf" alt="Spatial scale of agglomeration and dispersion: Theoretical foundations and empirical implications">2017a (PDF)</a>: "Spatial Scale of Agglomeration and Dispersion: Theoretical foundations and empirical implications"</li>
        <li><a href="https://mpra.ub.uni-muenchen.de/97496/1/MPRA_paper_97496.pdf" alt="Endogenous agglomeration in a many-region world">2017b (PDF)</a>: "Endogenous agglomeration in a many-region world"</li>
    </ul>
    </div>
    </li>
    <li><a href="https://arxiv.org/abs/2207.05346">Origin of power laws and their spatial fractal structure for city-size distributions</a> (2023)<br> (with Tomoya Mori, Takashi Akamatsu, and Yuki Takayama)  [<a href="https://arxiv.org/pdf/2207.05346">paper</a>]</li>
</ul>

<h3>Publications</h3>

Ordered by my preference. Please see <a href="https://scholar.google.co.jp/citations?user=qKxF-dkAAAAJ" target="_blank">Google Scholar</a> for a chronological list. 

<ul class="ref-list">
  {% for paper in site.data.papers %}
    <li>
      <a href="{{ paper.url }}" class="paper-title">{{ paper.title }}</a> <br>
      <span class="red-like">{{ paper.journal }}</span> ({{ paper.year }}) 
      {% if paper.pdf %}[<a href="{{ paper.pdf }}">paper</a>]{% endif %}
      {% if paper.coauthors %}<br>(with {{ paper.coauthors | join: ', ' }}){% endif %}
      {% if paper.previous %}
      <div class="note">
      Previous versions: 
          <ul class="ref-prev">
            {% for ver in paper.previous %}
              <li>
                <a href="{{ ver.url }}">{{ ver.year }}</a> "{{ ver.title }}"
              </li>
            {% endfor %}
          </ul>
      </div>
      {% endif %}
    </li>
  {% endfor %}
</ul>

<h3>Working Papers</h3>

<ul class="ref-list">

<li>Understanding regional dynamics (2025) [<a href="notes/draft/RD.pdf">paper</a>] [<a href="notes/draft/RD_slides.pdf">slides</a>]</li>

<li>Equilibrium distortion with dual noise (2025) [<a href="notes/draft/SLD.pdf">paper</a>] [<a href="notes/draft/SLD_slides.pdf">slides</a>]</li>

<li><a href="https://arxiv.org/abs/2011.06778">Most likely retail agglomeration patterns</a> (2025) (with Takashi Akamatsu and Yosuke Kogure)</li>

<li><a href="https://arxiv.org/abs/2512.06402">Innovation, spillovers and economic geography</a> (2025) (with José Maria Gaspar)</li>


<li><a href="https://arxiv.org/abs/2001.05095">Production externalities and dispersion process in a multi-region economy</a> (2021) (with José Maria Gaspar)</li>

<li><a href="https://arxiv.org/abs/2012.12503">Cities in a world of diminishing transport costs</a> (2021) (with Tomoya Mori)</li>
</ul>

<hr>

{% include other.html %}
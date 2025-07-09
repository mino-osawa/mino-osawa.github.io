---
layout: default
title: M.Osawa's Website
---

{% include profile.html %}

<hr>

<h2>Research</h2>

<h3>Selected Discussion Papers</h3>

<ul class="ref-list">
    <li><a href="https://arxiv.org/abs/1912.05113">Spatial scale of agglomeration and dispersion: Number, spacing, and the spatial extent of cities</a><br>(with Takashi Akamatsu, Tomoya Mori, and Yuki Takayama) [<a href="https://arxiv.org/pdf/1912.05113">PDF</a>] <span class="red-like">Updated: July 4, 2025</span>
    <div class="note">Previous versions: 
    <ul class="ref-prev">
        <li><a href="https://www.rieti.go.jp/jp/publications/summary/17120005.html" alt="Spatial scale of agglomeration and dispersion: Theoretical foundations and empirical implications">2017a</a>: "Spatial Scale of Agglomeration and Dispersion: Theoretical foundations and empirical implications"</li>
        <li><a href="https://mpra.ub.uni-muenchen.de/97496/" alt="Endogenous agglomeration in a many-region world">2017b</a>: "Endogenous agglomeration in a many-region world"</li>
    </ul>
    </div>
    </li>
    <li><a href="https://arxiv.org/abs/2207.05346">Origin of power laws and their spatial fractal structure for city-size distributions</a><br> (with Tomoya Mori, Takashi Akamatsu, and Yuki Takayama)  [<a href="https://arxiv.org/pdf/2207.05346">PDF</a>]
    </li>
</ul>

<h3>Publications</h3>

Ordered by my preference. Please see <a href="https://scholar.google.co.jp/citations?user=qKxF-dkAAAAJ" target="_blank">Google Scholar</a> for a chronological list. 

<ul class="ref-list">
  {% for paper in site.data.papers %}
    <li>
      <a href="{{ paper.url }}" class="paper-title">{{ paper.title }}</a> <br>
      <em class="red-like">{{ paper.journal }}</em> ({{ paper.year }}) 
      {% if paper.coauthors %}(with {{ paper.coauthors | join: ', ' }}){% endif %}
      {% if paper.pdf %}[<a href="{{ paper.pdf }}">PDF</a>]{% endif %}
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
<li>On sampling dynamics (WIP)</li>
<li>Understanding regional dynamics (WIP)</li>
<li><a href="https://arxiv.org/abs/2212.14475">Innovation through intra and inter-regional interaction in economic geography</a> (with José Maria Gaspar)</li>

<li><a href="https://arxiv.org/abs/2012.12503">Cities in a world of diminishing transport costs</a> (with Tomoya Mori)</li>

<li><a href="https://arxiv.org/abs/2011.06778">Stochastic stability of endogenous agglomeration patterns in an urban retail mode</a>  (with Takashi Akamatsu and Yosuke Kogure)</li>

<li><a href="https://arxiv.org/abs/2001.05095">Production externalities and dispersion process in a multi-region economy</a> (with José Maria Gaspar)</li>
</ul>

<hr>

{% include other.html %}

</ul>
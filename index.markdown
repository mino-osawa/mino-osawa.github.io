---
layout: default
title: M.Osawa's Website
---

<div id="profile">
    <div id="profile_pic-wrapper">
        <img src="/assets/img/minoru_osawa.jpg" id="profile_pic" alt="Minoru Osawa">
    </div>
    <div id="description-wrapper">
        <h1>Minoru OSAWA</h1>
        <p>Welcome! I am an assistant professor at <a href="https://www.kier.kyoto-u.ac.jp/en/">Kyoto Institute of Economic Research (KIER)</a>, Kyoto University. I explore how human behavior unfolds across space and time. Looking forward to exchanging thoughts with you.</p>
        <ul class="info">
        <li class="em">osawa&#46;<span class="Eetae3eo">[Remove]</span>minoru<span class="Hoo9Phie">[Remove]</span>.4z<span class="Tho2ail2">[Remove]</span><span class="Oome0Ma0">[Remove]</span>@kyo<span class="moeJeo1u">[Remove]</span>t&#111;&#45;&#117;.&#97;<span class="fii2Eith">[Remove]</span>c.jp</li>
        <li class="loc"><a href="https://maps.app.goo.gl/E2Qxmj5z11s1J57G9">Kyoto, Japan</a></li>
        <li class="twt"><a href="https://twitter.com/minoru_osawa">Twitter</a> / <a href="https://www.researchgate.net/profile/Minoru-Osawa">ResearchGate</a></li>
        <li class="lnks"><a href="https://scholar.google.co.jp/citations?user=qKxF-dkAAAAJ">Google Scholar</a> / <a href="https://orcid.org/0000-0001-9067-5375">ORCiD</a> /  <a href="https://researchmap.jp/minoru_osawa">researchmap</a></li>
        </ul>
    </div>
</div>

<hr>

<h2>Research</h2>

<h3>Selected Discussion Papers</h3>

<ul class="ref-list">
    <li><a href="https://arxiv.org/abs/1912.05113">Spatial scale of agglomeration and dispersion: Number, spacing, and the spatial extent of cities</a><br>(with Takashi Akamatsu, Tomoya Mori, and Yuki Takayama) [<a href="https://arxiv.org/pdf/1912.05113">PDF</a>]
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

Ordered by my preference. Please see <a href="https://orcid.org/0000-0001-9067-5375" target="_blank
">ORCiD</a> or <a href="https://scholar.google.co.jp/citations?user=qKxF-dkAAAAJ" target="_blank
">Google Scholar</a> for a chronological list. 

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
<li>On sampling dynamics</li>
<li>Understanding regional dynamics</li>
<li><a href="https://arxiv.org/abs/2212.14475">Innovation through intra and inter-regional interaction in economic geography</a> (with José Maria Gaspar)</li>

<li><a href="https://arxiv.org/abs/2012.12503">Cities in a world of diminishing transport costs</a> (with Tomoya Mori)</li>

<li><a href="https://arxiv.org/abs/2011.06778">Stochastic stability of endogenous agglomeration patterns in an urban retail mode</a>  (with Takashi Akamatsu and Yosuke Kogure)</li>

<li><a href="https://arxiv.org/abs/2001.05095">Production externalities and dispersion process in a multi-region economy</a> (with José Maria Gaspar)</li>
</ul>


<hr>

<h2>Education and Work Experiences</h2>
<ul class="ref-list">
    <li>
        <b>Apr. 2020 - Present:</b> 
        <span class="red-like">Assistant Professor</span>  (tenure-track). <br> 
        Institute of Economic Research, Kyoto University</li>
    <li>
        <b>Oct. 2016 - Mar. 2020:</b> 
        <span class="red-like">Assistant Professor</span> (termed). <br>
        Department of Civil and Environmental Engineering, <br>
        School of Engineering, Tohoku University</li>
    <li>
        <b>Apr. 2014 - Sep. 2016:</b> 
        <span class="red-like">Research Fellow (DC1)</span>. <br> 
        Japan Society for the Promotion of Science</li>
    <li>
        <b>Sep. 2016:</b> 
        <span class="red-like">Ph.D. (Information Sciences)</span>. <br>
        Department of Human-Social Information Sciences,<br> Graduate School of Information Sciences, Tohoku University.<br>
        (Thesis supervisor: <a href="http://www.plan.civil.tohoku.ac.jp/~akamatsu/Akamatsu-E.htm">Takashi Akamatsu</a>)</li>
    <li>
        <b>Mar. 2012:</b> 
        <span class="red-like">Bachelor of Engineering</span>. <br>
        Department of Civil Engineering and Architecture, <br> School of Engineering, Tohoku University</li>
    <li>
        <b>Mar. 2008:</b> 長野県松本深志高等学校 卒業</li>
</ul>


<hr>

<h2>Misc.</h2>

<ul class="ref-list">
<li>Born in 1990. He/his/him. Love dogs. Love hiking. Do some drawing & painting.</li>

<li>You can call me <b>Mino</b> if its easier.</li>

<li>Our <a href="https://www.kier.kyoto-u.ac.jp/en/workshop_category/urban-economics/">Urban Economics Workshop</a> is always looking for speakers. Please feel free to contact me if you are interested–––you are more than welcome.</li>

</ul>
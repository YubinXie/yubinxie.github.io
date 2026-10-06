---
layout: default
permalink: /
excerpt: "Yubin Xie, PhD — Staff AI Scientist at Noetik. Machine learning for spatial biology and oncology."
redirect_from:
  - /about/
  - /about.html
---

<main id="main-content" class="home">
  <section id="about" class="intro" aria-labelledby="intro-title">
    <div class="intro-copy">
      <h1 id="intro-title">Yubin Xie<span class="degree">, PhD</span></h1>
      <p>I’m a <strong>Staff AI Scientist at Noetik</strong>. I develop machine learning models for spatial biology and oncology, including virtual cell models that use sequencing and imaging data to study cells in their tissue context.</p>
      <p>I completed my PhD in the Tri-Institutional Program in Computational Biology and Medicine, working with Dana Pe’er at Memorial Sloan Kettering Cancer Center. My doctoral research focused on cancer progression and metastasis using single-cell and spatial data.</p>
      <div class="profile-links" aria-label="Contact and profiles">
        <a href="mailto:{{ site.author.email }}">Email</a>
        <a href="{{ site.author.googlescholar }}">Google Scholar</a>
        <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a>
        <a href="https://github.com/YubinXie">GitHub</a>
      </div>
    </div>
    <img class="profile-photo" src="{{ '/images/profile_yubin2.jpg' | relative_url }}" alt="Yubin Xie" width="144" height="144" fetchpriority="high">
  </section>

  <section id="publications" class="home-section" aria-labelledby="publications-title">
    <div class="section-heading">
      <h2 id="publications-title">Selected publications</h2>
      <a href="{{ site.author.googlescholar }}">Full list on Google Scholar</a>
    </div>
    <ul class="publication-list">
      {% for paper in site.publications reversed %}
      <li>
        <a class="publication-title" href="{{ paper.paperurl }}">{{ paper.title }}</a>
        <span class="publication-meta">{{ paper.venue }}, {{ paper.date | date: '%Y' }}</span>
      </li>
      {% endfor %}
    </ul>
  </section>

  <section id="activity" class="home-section" aria-labelledby="activity-title">
    <h2 id="activity-title">Presentations &amp; community</h2>
    <ul class="activity-list">
      <li><time datetime="2026-04">Apr 2026</time><span>Co-organized <a href="https://sites.google.com/view/icbinb-2026">ICBINB: Where Large Language Models Need to Improve</a> at ICLR.</span></li>
      <li><time datetime="2025-11">Nov 2025</time><span>Presented a <a href="https://www.noetik.ai/sitc-2025">SITC poster on virtual cell models and fibroblast–macrophage crosstalk</a> in the lung cancer microenvironment.</span></li>
      <li><time datetime="2025-04">Apr 2025</time><span>Presented <a href="https://www.noetik.ai/aacr-2025">OCTO-virtual cell</a> at AACR, on modeling cell and tissue spatial biology for patient stratification and target discovery.</span></li>
      <li><time datetime="2025-04">Apr 2025</time><span>Co-organized <a href="https://sites.google.com/view/icbinb-2025">ICBINB: Challenges in Applied Deep Learning</a> at ICLR.</span></li>
      <li><time datetime="2023">2023</time><span>Co-organized ICBINB: Failure Modes in the Age of Foundation Models at NeurIPS and co-edited the <a href="https://proceedings.mlr.press/v239/">workshop proceedings</a>.</span></li>
      <li><span class="activity-date">2020–2023</span><span>Co-organized the <a href="https://icml-compbio.github.io/">ICML Workshop on Computational Biology</a>.</span></li>
    </ul>
  </section>

  <p class="personal-note">Based in New York City. Outside work: vinyl, jazz, bouldering, and photography.</p>
</main>

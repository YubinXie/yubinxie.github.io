---
layout: default
permalink: /
excerpt: "Yubin Xie, PhD — Staff AI Scientist at Noetik, working at the intersection of machine learning and cancer biology."
redirect_from:
  - /about/
  - /about.html
---

<main id="main-content" class="home">
  <section class="intro" aria-labelledby="intro-title">
    <div class="intro-copy">
      <p class="intro-role">Staff AI Scientist at Noetik</p>
      <h1 id="intro-title">Yubin Xie<span class="degree">, PhD</span></h1>
      <p class="intro-statement">Building AI to<br>understand cancer.</p>
      <p class="intro-description">I work at the intersection of AI and oncology, using sequencing and imaging data to understand cancer and build models of cellular biology.</p>
      <div class="intro-actions">
        <a class="primary-link" href="#research">Explore my research</a>
        <a href="{{ site.author.googlescholar }}">Google Scholar</a>
      </div>
    </div>
    <figure class="portrait">
      <img src="{{ '/images/profile_yubin2.jpg' | relative_url }}" alt="Yubin Xie" width="420" height="480" fetchpriority="high">
      <figcaption>Based in New York City</figcaption>
    </figure>
  </section>

  <section id="research" class="home-section" aria-labelledby="research-title">
    <div class="section-heading"><h2 id="research-title">Research</h2><p>Understanding cancer through data.</p></div>
    <div class="research-content">
      <p class="section-lead">My work connects machine learning with the complexity of living systems.</p>
      <p>At Noetik, my research interests include virtual cell foundation models and AI for oncology. During my PhD in the Tri-Institutional Program in Computational Biology and Medicine, I studied cancer progression and metastasis using high-dimensional sequencing and imaging data.</p>
      <dl class="research-topics">
        <div><dt>AI for cellular biology</dt><dd>Learning representations of cells and their environments from biological data.</dd></div>
        <div><dt>Cancer progression &amp; metastasis</dt><dd>Understanding how tumors evolve, spread, and interact with the immune system.</dd></div>
        <div><dt>Single-cell &amp; spatial data</dt><dd>Connecting molecular measurements with tissue context through machine learning.</dd></div>
      </dl>
    </div>
  </section>

  <section id="publications" class="home-section" aria-labelledby="publications-title">
    <div class="section-heading"><h2 id="publications-title">Selected publications</h2><a href="{{ site.author.googlescholar }}">Full publication list on Google Scholar</a></div>
    <div class="publication-list">
      {% for paper in site.publications reversed %}
      <article class="publication">
        <p class="publication-venue">{{ paper.venue }} / {{ paper.date | date: '%Y' }}</p>
        <h3><a href="{{ paper.paperurl }}">{{ paper.title }}</a></h3>
        <a class="publication-detail" href="{{ paper.url | relative_url }}">Read abstract</a>
      </article>
      {% endfor %}
    </div>
  </section>

  <section id="updates" class="home-section" aria-labelledby="updates-title">
    <div class="section-heading"><h2 id="updates-title">Updates</h2><p>Conferences &amp; community.</p></div>
    <div class="updates-list">
      <article><time datetime="2025-04">April 2025</time><div><h3>Virtual cell foundation models at AACR</h3><p>Poster presentation on our virtual cell foundation model at AACR 2025 in Chicago.</p></div></article>
      <article><time datetime="2025-04">April 2025</time><div><h3>ICLR workshop organization</h3><p>Organizer of <a href="https://sites.google.com/view/icbinb-2025">I Can’t Believe It’s Not Better</a> at ICLR 2025 in Singapore.</p></div></article>
    </div>
  </section>

  <section id="contact" class="home-section contact-section" aria-labelledby="contact-title">
    <div class="section-heading"><h2 id="contact-title">Outside the lab</h2><p>Vinyl, jazz, bouldering, and capturing everyday moments.</p></div>
    <div class="contact-content"><h3>Let’s connect.</h3><p>Get in touch about research, machine learning, or shared interests.</p><div class="contact-links"><a href="mailto:{{ site.author.email }}">Email me</a><a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a><a href="https://github.com/YubinXie">GitHub</a></div></div>
  </section>
</main>

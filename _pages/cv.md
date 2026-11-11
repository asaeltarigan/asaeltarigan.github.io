---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
classes: cv
redirect_from:
  - /resume
---

{% include base_path %}

{% assign pubs = site.publications %}
{% assign n_journal = pubs | where: "category", "manuscripts" | size %}
{% assign n_conf = pubs | where: "category", "conferences" | size %}
{% assign n_pre = pubs | where: "category", "preprints" | size %}
{% assign n_sup = pubs | where: "category", "supervised_projects" | size %}

<div class="cv-actions">
  <a class="btn btn--primary" href="{{ base_path }}/files/cv.pdf"><i class="fas fa-download" aria-hidden="true"></i> Download CV (PDF)</a>
  <span class="cv-actions__note">Updated November 2026</span>
</div>

<div class="cv-metrics">
  <div class="cv-metrics__item"><span class="cv-metrics__n">{{ n_journal }}</span><span class="cv-metrics__l">journal articles</span></div>
  <div class="cv-metrics__item"><span class="cv-metrics__n">{{ n_conf }}</span><span class="cv-metrics__l">conference papers</span></div>
  <div class="cv-metrics__item"><span class="cv-metrics__n">{{ n_sup }}</span><span class="cv-metrics__l">capstones supervised</span></div>
  <div class="cv-metrics__item"><span class="cv-metrics__n">{{ n_pre }}</span><span class="cv-metrics__l">preprint</span></div>
</div>

<h2 class="cv-section">Featured work</h2>

<div class="cv-features">
{% for item in site.data.cv_highlights %}
  <article class="cv-feature">
    <div class="cv-feature__meta">
      <span class="cv-feature__venue">{{ item.venue }}</span>
      {% if item.status %}<span class="cv-badge">{{ item.status }}</span>{% endif %}
      <span class="cv-feature__tags">{{ item.tags }}</span>
    </div>
    <h3 class="cv-feature__title"><a href="{{ item.url | relative_url }}">{{ item.title }}</a></h3>
    <p class="cv-feature__sub">{{ item.subtitle }}</p>
    <p class="cv-feature__note">{{ item.note }}</p>
  </article>
{% endfor %}
</div>

{% include cv-timeline.html section="experience" %}
{% include cv-timeline.html section="education" %}

<h2 class="cv-section">Publications</h2>
<p class="cv-lede">Peer-reviewed work and preprints, newest first. Full records with citations and PDFs are on the <a href="{{ base_path }}/publications/">publications page</a>.</p>

{% include cv-publications.html %}

{% assign supervised = pubs | where: "category", "supervised_projects" | sort: "date" | reverse %}
{% if supervised.size > 0 %}
<h2 class="cv-section">Supervised capstone projects</h2>
<p class="cv-lede">Final-year BINUS projects I supervised; the work is the students', the supervision is mine.</p>
<details class="cv-details">
  <summary>Show all {{ supervised.size }} projects</summary>
  <ul class="cv-suplist">
  {% for post in supervised %}
    <li><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a> <span class="cv-suplist__year">{{ post.date | date: "%Y" }}</span></li>
  {% endfor %}
  </ul>
</details>
{% endif %}

<h2 class="cv-section">Skills</h2>
<ul class="cv-skills">
  <li><strong>Research and modelling</strong> Python for data processing, model development, experimentation and evaluation. PyTorch, TensorFlow, scikit-learn, NumPy, pandas, OpenCV.</li>
  <li><strong>ML systems</strong> MLOps, model deployment, automated evaluation, FastAPI, REST APIs, SQL, Docker, GitHub Actions, Linux.</li>
  <li><strong>Other</strong> Java, PHP, C, JavaScript, HTML/CSS. LLM APIs and AI coding assistants for development.</li>
  <li><strong>Languages</strong> Bahasa Indonesia (native). English, EF SET C2 (Proficient).</li>
</ul>

<h2 class="cv-section">Teaching</h2>
<ul class="cv-teachlist">
{% for post in site.teaching reversed %}
  {% assign year = post.date | date: "%Y" %}
  {% assign tname = post.title | split: "-" | last | strip %}
  <li><a href="{{ base_path }}{{ post.url }}">{{ tname }}</a> <span class="cv-teachlist__year">{{ year }}</span></li>
{% endfor %}
</ul>

<h2 class="cv-section">Service</h2>
<ul class="cv-skills">
  <li><strong>Coordinator</strong> ARISE, national machine learning competition, 2026</li>
  <li><strong>Coordinator</strong> AIPLEX (AI Prototype and Logic Exhibition), BeeFest 2025</li>
  <li><strong>Session chair</strong> ICCSCI, International Conference on Computer Science and Computational Intelligence, 2024 - 2025</li>
  <li><strong>Peer reviewer</strong> EMACS Conference, 2024 - present</li>
  <li><strong>Organising committee</strong> ICPC Asia Pacific Championship, 2024 - 2026</li>
</ul>

<h2 class="cv-section">Honours and awards</h2>
<ul class="cv-skills">
  <li><strong>Summa Cum Laude</strong> Master of Computer Science, BINUS University, 2024. <strong>Best Graduate</strong> Bachelor of Computer Science, Soegijapranata Catholic University, 2022.</li>
  <li><strong>Faculty Development Program scholarship</strong> full funding for master's studies, BINUS University.</li>
  <li><strong>Bangkit Academy 2022</strong> machine learning path (Google, GoTo, Traveloka). Led the capstone team behind Kerjamin, a freelancing platform that widens income opportunities for rural workers.</li>
</ul>

<h2 class="cv-section">Training and certifications</h2>
<ul class="cv-skills">
  <li><strong>SecOps AI-ML Pen Certified Professional</strong> 2025. Practical exam on AI and ML security, including prompt injection and RAG poisoning.</li>
  <li><strong>Microsoft AI-900</strong> 2025. Core AI and machine learning concepts and the Azure AI service stack.</li>
  <li><strong>Kominfo Digital Talent Scholarship</strong> 2021, AI track by Huawei, with the Huawei Certified ICT Associate Artificial Intelligence credential.</li>
</ul>

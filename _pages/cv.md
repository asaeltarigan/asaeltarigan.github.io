---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computer Science, Bina Nusantara University — Summa Cum Laude (GPA 3.95)
* B.S. in Computer Science, Bina Nusantara University — best graduate of the cohort

Work experience
======
* Lecturer, Artificial Intelligence Program — School of Computer Science, BINUS University
  * Designed and authored the AI program's core curriculum (5 courses authored, 2 co-authored): ML foundations, applied NLP, deep learning, MLOps, signal processing, and IoT & robotics.
  * Build and operate the production systems that run the program: ML competition platform, course quiz portals, and interactive teaching tools.
  * Research in deep learning for time-series forecasting (hybrid LSTM-GRU architectures).

Skills
======
* Python, FastAPI, SQLite
* Deep Learning: LSTM, GRU, Transformers (PyTorch)
* MLOps & self-hosting: uvicorn, systemd, cloudflared, Linux (VPS)
* Git & GitHub, LaTeX, Playwright

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

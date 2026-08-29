---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div style="margin-bottom:1.2rem;"><a class="btn btn--primary" href="{{ base_path }}/files/cv.pdf"><i class="fas fa-download" aria-hidden="true"></i> Download CV (PDF)</a></div>

{% include cv-timeline.html %}

Skills
======
* Python, SQLite, Bash
* Deep Learning: LSTM, GRU, Transformers (PyTorch)
* ML Systems & MLOps: FastAPI, uvicorn, systemd, cloudflared; self-hosted on a single VPS
* Research & Writing: LaTeX, IEEE format, academic writing

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

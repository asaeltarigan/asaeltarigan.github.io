---
permalink: /
title: "Gabriel Asael Tarigan, S.Kom., M.Kom."
seo_title: "Gabriel Asael Tarigan | Artificial Intelligence & Computer Science Lecturer"
description: "Gabriel Asael Tarigan is a computer science lecturer and researcher at BINUS University, teaching in the Artificial Intelligence (AI) Program, School of Computer Science. He works on applied machine learning, ML systems and MLOps, and designed the AI curriculum."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I started teaching before it was ever a job. Sunday school classes on the weekends, private tutoring after school, and the honest reason I kept at it is that teaching turned out to be how I learned things myself. There's no feeling like watching someone finally grow. That same feeling still runs everything I do now.

Today I'm a computer science lecturer at [BINUS University](https://www.binus.ac.id), where I serve as a [Lecturer Specialist](https://socs.binus.ac.id/artificial-intelligence/people/gabriel-asael-tarigan-s-kom-m-kom/) in the Artificial Intelligence (AI) Program, School of Computer Science. I design the program's core AI/ML curriculum and build the systems that run it: competition platforms, automated evaluation portals, interactive tools students can tinker with. I also mentor student teams and national competition squads.

Before I joined the faculty I was selected for Google & GoTo's Bangkit Academy Machine Learning Cohort in 2022, from more than 63,000 applicants, and I hold BINUS's Faculty Development Program (FDP) scholarship, which funded my master's degree in full.

<ul class="role-chips">
<li>Lecturer Specialist, AI Program, School of Computer Science</li>
<li>Curriculum author, AI Program</li>
<li>Coordinator, ARISE &amp; AIPLEX national competitions</li>
<li>Peer reviewer, EMACS Journal</li>
<li>Session chair, ICCSCI</li>
<li>CIPHER 2026 AI Hive coordinator</li>
</ul>

<h2 class="cv-section">What I'm working on</h2>

<div class="hp-grid">
{% for item in site.data.cv_highlights %}
  <article class="cv-feature">
    <div class="cv-feature__meta">
      <span class="cv-feature__venue">{{ item.venue }}</span>
      {% if item.status %}<span class="cv-badge">{{ item.status }}</span>{% endif %}
      <span class="cv-feature__tags">{{ item.tags }}</span>
    </div>
    <h3 class="cv-feature__title"><a href="{{ item.url | relative_url }}">{{ item.title }}</a></h3>
    <p class="cv-feature__note">{{ item.note }}</p>
  </article>
{% endfor %}
</div>

<p class="hp-more"><a href="{{ '/cv/' | relative_url }}">Full CV and publication list &rarr;</a></p>

<h2 class="cv-section">Things I build</h2>

<div class="hp-grid hp-grid--systems">
{% for item in site.data.home_systems %}
  <article class="hp-system">
    <div class="hp-system__tag">{{ item.tag }}</div>
    <h3 class="hp-system__name"><a href="{{ item.url | relative_url }}">{{ item.name }}</a></h3>
    <p class="hp-system__desc">{{ item.description }}</p>
    <span class="hp-system__link">{{ item.link_label }} &rarr;</span>
  </article>
{% endfor %}
</div>

<h2 class="cv-section">Research interests</h2>

<ul class="hp-interests">
<li><strong>Computer vision</strong> pose estimation, skeletal keypoints, classroom engagement</li>
<li><strong>Deep learning</strong> hybrid architectures, parallel LSTM-GRU, vision transformers</li>
<li><strong>Time-series forecasting</strong> multivariate financial and sequential signals</li>
<li><strong>ML systems</strong> deployment, monitoring, edge inference, lightweight LLMs</li>
<li><strong>Educational technology</strong> assessment platforms, intelligent tutoring</li>
</ul>

<h2 class="cv-section">Where to find the work</h2>

<p class="hp-links">
<a href="{{ '/publications/' | relative_url }}">Publications</a> &middot;
<a href="{{ '/cv/' | relative_url }}">CV</a> &middot;
<a href="{{ site.author.googlescholar }}">Google Scholar</a> &middot;
<a href="https://github.com/asaeltarigan">GitHub</a> &middot;
<a href="https://www.linkedin.com/in/gabrielasael">LinkedIn</a> &middot;
<a href="{{ site.author.medium }}">Medium</a>
</p>

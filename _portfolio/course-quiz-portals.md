---
title: "Course Quiz Portals"
excerpt: "Weekly quiz portals for ML courses: practice-mode, NIM-gated submissions with instant feedback."
collection: portfolio
chips:
  - "FastAPI"
  - "NIM-gated"
  - "auto-graded"
  - "per-course"
source: "https://github.com/asaeltarigan"
---

Weekly quiz portals for machine learning courses at BINUS.

- Practice mode, NIM-gated submissions (10-digit student IDs, unlimited retakes, best score counts)
- Questions follow the lecture order and restate data (no forced recall)
- Instant feedback and live results per class

Each course gets its own portal; all are built on the same FastAPI foundation and operated from a single VPS. Students reach a portal through a link issued for the term, and the portals carry real graded load every week.

## What is covered

- **Introduction to AI** — foundations, intelligent agents, search
- **Speech Recognition** — session quizzes plus a graded recall set
- **NLP** — text preprocessing, named entity recognition, plus a seven-game preprocessing playground
- **Machine Learning** — sessions 17 to 22: Markov decision processes, introduction to ML, linear regression, decision trees, KNN, neural networks
- **MLOps** — recall sessions covering data management and sessions 1 to 6
- **Intelligent Automation** — risks in HR
- **Exam preparation** — pre-UTS and pre-final review sets

The links are short-lived by design: each term's portals are opened to the enrolled class and closed when the term ends. If you want to see one running, ask me and I will open a demo instance.

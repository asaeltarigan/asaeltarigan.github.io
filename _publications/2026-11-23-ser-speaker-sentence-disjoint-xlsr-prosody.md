---
title: "Speaker and Sentence-Disjoint Evaluation of XLS-R with Prosody-Aware Pooling for Indonesian Speech Emotion Recognition"
collection: publications
category: preprints
status: preprint
permalink: /publication/ser-xlsr-prosody-indonesian/
excerpt: "A prosody-aware pooling mechanism inside an XLS-R 300M encoder adapted with LoRA, evaluated under leave-one-speaker-out and sentence-disjoint protocols on the Indonesian Expressive Speech Corpus."
date: 2026-11-23
venue: 'International Journal of Intelligent Engineering and Systems (IJIES), preprint'
citation: 'Nugroho, K. S.; Imani, A.; Jarin, A.; Tarigan, G. A.; Bachtiar, F. A.; Cooper, E. W.; &amp; Pardamean, B. (2026). &quot;Speaker and Sentence-Disjoint Evaluation of XLS-R with Prosody-Aware Pooling for Indonesian Speech Emotion Recognition.&quot; <i>International Journal of Intelligent Engineering and Systems (IJIES), preprint</i>.'
---

Speech emotion recognition degrades when the test speakers were never seen in training, and Indonesian-language work in this area is thin. This manuscript evaluates a prosody-aware pooling mechanism inside an XLS-R 300M encoder adapted with Low-Rank Adaptation (LoRA). The pooling combines cross-layer representation weighting with attentive statistics pooling, conditioned on three prosodic features: fundamental frequency (F0), log root mean square, and a binary voicing indicator.

Experiments used the Indonesian Expressive Speech Corpus (INESCO) — 2,399 audio files, 600 sentences, four speakers, three emotion classes — under three evaluation protocols. In the primary protocol, which combines leave-one-speaker-out with sentence-disjoint splitting, the prosody configuration reached an unweighted average recall of 0.7783 ± 0.1025 against 0.6242 ± 0.1473 for the mean-pooling baseline, an improvement of 0.1541 (15.41 percentage points).

Two limits are stated plainly in the paper: the individual contributions of each component were not ablated, so the gain cannot yet be attributed to the prosodic features alone, and four speakers is a small base for claims about cross-speaker generalization.


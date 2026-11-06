---
title: "Fake Review Detection on E-Commerce Platforms Using a Hybrid Anomaly Detection Approach: Combining Autoencoder and Isolation Forest"
collection: publications
category: preprints
status: preprint
permalink: /publication/fake-review-detection-ecommerce/
excerpt: "E-commerce shop now days tend to have fake review buyers on their rating section, leading to misbelieved ratings that shouldn’t be accurate."
date: 2026-06-29
venue: 'Research Square (preprint)'
paperurl: 'https://doi.org/10.21203/rs.3.rs-10162747/v1'
citation: 'Laychi, S.; Karuntu, S. P. A.; Sihombing, D. H.; Sutoyo, R.; &amp; Tarigan, G. A. (2026). &quot;Fake Review Detection on E-Commerce Platforms Using a Hybrid Anomaly Detection Approach: Combining Autoencoder and Isolation Forest.&quot; <i>Research Square (preprint)</i>.'
---

E-commerce shop now days tend to have fake review buyers on their rating section, leading to misbelieved ratings that shouldn’t be accurate. Review detector currently use with conventional supervised learning algorithms which is have expensive on data set, platform-specific datasets. The main purpose creates a hybrid unsupervised anomaly detection frame work that use Isolation FOrest combined with Autoencoder, both provides a stronger detection which almost as good as previous method but more cheaper way. Autoencoder works with trying to reconstruct the reviews and give calculation how hard the construction will be, higher error rates when doing so resulting higher fake reviews score. In other side Isolation Forest work kinda differently, theysplits and randomly partitions feature space to provide anomaly score. Both score they resulting are calculated according to hybrid decision rule for classification. We use the Amazon fake reviews dataset [2] is used to assess th frame work since it give equal on both gpt-2 reviews and real amazon reviews along all category of items. Both approaches representing features TF-IDF and BERT. Suggested method is compared to a stand-alone Autoencoder, a stand alone Isolation Forest, and supervised SVM classifier. Precision, recall, f1-score, and AUR ROC are used in evaluation. The results reveal that hybrid structure offering a scalable substitute for actual e-commerce systems by means of competitive detection performance but its free reliance on tagged data.

Preprint available via [DOI: 10.21203/rs.3.rs-10162747/v1](https://doi.org/10.21203/rs.3.rs-10162747/v1).

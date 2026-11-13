---
title: "Improving Indonesian Cognitive Distortion Classification under Extreme Class Imbalance"
collection: publications
category: conferences
status: accepted
permalink: /publication/cognitive-distortion-class-imbalance/
excerpt: "A four-stage, multi-seed study of data-level versus algorithmic interventions for multi-class Indonesian cognitive distortion detection at a 59:1 imbalance ratio."
date: 2026-11-01
venue: "2026 International Conference on Intelligent Cybernetics Technology & Applications (ICICyTA), IEEE"
citation: "Utomo, D. T. D.; Nugroho, K. S.; Tarigan, G. A.; Bachtiar, F. A.; Cooper, E. W.; &amp; Pardamean, B. (2026). &quot;Improving Indonesian Cognitive Distortion Classification under Extreme Class Imbalance.&quot; <i>2026 International Conference on Intelligent Cybernetics Technology &amp; Applications (ICICyTA)</i>."
---

Cognitive distortions are systematic biases in thought patterns that reinforce negative thinking and contribute to depression, and detecting them automatically in Indonesian text is hard: the available expert-annotated dataset carries a class imbalance ratio of up to 59:1, far beyond the IR>9 threshold that defines extreme imbalance. Earlier work fine-tuned IndoBERT with LoRA but collapsed the twelve distortion categories into a single binary label, which leaves the multi-class problem open.

This study fine-tunes IndoLEM IndoBERT through a four-stage experimental framework run with three random seeds, to separate the contribution of data-level interventions from loss-function changes. Data-level work dominated: the gap between the weakest and strongest sampling configurations exceeded 27 weighted F1 points, while every loss-function configuration differed by less than 1 point. A hybrid of majority-class undersampling with minority-class contextual augmentation reached a mean test weighted F1 of 0.7852 ± 0.0033 and macro F1 of 0.5364 ± 0.0184, and the configuration selected by hyperparameter tuning validated at 0.7793 ± 0.0014 with lower variance. Per-class analysis showed that classes with fewer than 50 training samples stayed near zero F1 in every configuration, which makes data collection for minority categories the binding constraint rather than any augmentation or loss-function trick. Accepted for presentation at ICICyTA 2026.

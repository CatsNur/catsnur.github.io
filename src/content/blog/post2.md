---
title: "Recognition of errors in gaze-based interaction with anomaly detection"
description: "This gaze-based anomaly detection method can detect rare but critical selection errors in under 300ms after a selection is made. It achieves over 90% accuracy on correct selections while detecting around 75% of incorrect selections in a VR visual search task."
pubDate: "May 25 2025"
heroImage: "/anomaly_detection.png"
tags: ["Eye Tracking","Gaze-Based Interaction", "Accessibility","Deep Learning/Machine Learning", "Scanpath Analysis"]
---

Gaze-based interaction provides an intuitive way to control robotic systems, but unintended selections remains a challenge. Conventional approaches mitigate this problem by requiring additional confirmation actions, yet incorrect decisions still occur. In this study, we propose an anomaly detection approach to improve selection accuracy. We conducted a virtual reality experiment with a visual search task and tested different methods to find anomalies in the gaze pattern. These methods are trained with correct selections to learn their features. By exploiting the gaze patterns, the methods effectively discriminate between correct and incorrect selections, since unintended inputs are not well represented in the learned gaze patterns and therefore the features differ from the normal case. The results show that our approach maintains over 90% accuracy for correct selections while successfully identifying over 60% incorrect selections, thereby reducing false activations. To further validate our method, future work should investigate its effectiveness in real-time scenarios.

### Publication

[View OpenAccess publication](https://dl.acm.org/doi/full/10.1145/3715669.3725895)

### BibTeX

```bibtex
@inproceedings{severitt2025recognition,
  title={Recognition of errors in gaze-based interaction with anomaly detection},
  author={Severitt, Bj{\"o}rn Rene and Sauer, Yannick and Castner, Nora Jane and Fuhl, Wolfgang and Wahl, Siegfried},
  booktitle={Proceedings of the 2025 Symposium on Eye Tracking Research and Applications},
  pages={1--6},
  year={2025}
}

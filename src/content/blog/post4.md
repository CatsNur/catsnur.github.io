---
title: "A MinHash approach for fast scanpath classification"
description: "We introduce a MinHash-based method for efficient scanpath similarity, achieving competitive clustering and classification with constant memory and fast runtime, suitable for real-time or large-scale analysis"
pubDate: "June 2 2020"
heroImage: "/minhash.png"
badge: "Best Paper Award"
tags: ["Eye Tracking", "Scanpath Analysis","Deep Learning/Machine Learning"]
---

The visual scanpath describes the shift of visual attention over time. Characteristic patterns in the attention shifts allow inferences about cognitive processes, performed tasks, intention, or expertise. To analyse such patterns, the scanpath is often represented as a sequence of symbols that can be used to calculate a similarity score to other scanpaths. However, as the length of the scanpath or the number of possible symbols increases, established methods for scanpath similarity become inefficient, both in terms of runtime and memory consumption. We present a MinHash approach for efficient scanpath similarity calculation. Our approach shows competitive results in clustering and classification of scanpaths compared to established methods such as Needleman-Wunsch, but at a fraction of the required runtime. Furthermore, with time complexity of and constant memory consumption, our approach is ideally suited for real-time operation or analyzing large amounts of data.

### Publication

[View OpenAccess publication](https://dl.acm.org/doi/abs/10.1145/3379155.3391325)

### BibTeX

```bibtex
@inproceedings{geisler2020minhash,
  title={A MinHash approach for fast scanpath classification},
  author={Geisler, David and Castner, Nora and Kasneci, Gjergji and Kasneci, Enkelejda},
  booktitle={ACM Symposium on Eye Tracking Research and Applications},
  pages={1--9},
  year={2020}
}




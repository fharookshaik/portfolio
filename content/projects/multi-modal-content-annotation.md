---
title: "Multi-modal Content Annotation for Comic Mischief Detection"
date: 2021-08-01
---

**Aug 2021 – Dec 2021 | IIIT Dharwad**

Built a video humor understanding system on the MOCHA dataset (Mustard-based Comic Humor Annotation).
Goal: classify short video clips into four fine-grained humor types – Slapstick, Sarcasm, Gory, and Others.

**Approach & results:**
- Designed a two-stream architecture: VGG16 for spatial features + TimeDistributed wrapper feeding into LSTM for temporal modeling
- Outperformed image-only CNN baselines by correctly capturing motion and sequence dependencies
- Conducted extensive ablation studies on frame sampling rates and sequence lengths

The project gave me deep experience in modeling temporal dynamics in video with limited labeled data.

**Tech:** TensorFlow/Keras, OpenCV, VGG16, LSTM, Matplotlib
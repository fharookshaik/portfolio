---
title: "Multi-modal Fake News Detection"
date: 2021-01-01
---

**Jan 2021 – May 2021 | IIIT Dharwad**

Developed a robust multimodal fake news classifier using the Fakeddit benchmark (1M+ samples from Reddit).

**Key innovations:**
- Text branch: Bi-directional LSTM with GloVe/Word2Vec embeddings (86% training accuracy, beat traditional CNN-text models)
- Image branch: ResNet-50 for visual feature extraction
- Late fusion via TI-CNN (Text-Image CNN) architecture with explicit and latent multimodal branches
- Extensive preprocessing pipeline for cleaning noisy social-media text and removing near-duplicates

The system achieved strong generalization on misleading multimodal posts and helped me understand the power (and pitfalls) of combining vision and language.

**Tech:** PyTorch, Transformers, ResNet-50, NLTK, Pandas, Scikit-learn
---
title: "Dissecting Harmful Memes – Semantic Role Labeling"
date: 2022-01-01
---

**Jan 2022 – May 2022 | IIIT Dharwad | Published at ACL Workshop 2022**

Part of the Constraint@AAAI 2022 Shared Task on Hero-Villain-Victim prediction in harmful memes.
Developed an NLP-focused system that treats memes as short propaganda narratives and assigns semantic roles (Hero, Villain, Victim, Other) to every entity mentioned in the text layer of the meme.

**Highlights:**
- Combined Named Entity Recognition with Wu-Palmer semantic similarity (WordNet) to capture implicit propaganda patterns
- Built a BERT-based classifier fine-tuned on the task dataset
- Achieved an F1-score of 23.855 and ranked 8th among 50+ international teams
- Co-authored paper accepted at the ACL 2022 Workshop on Combating Online Hostile Posts

**Tech:** Python, spaCy, Transformers (BERT), WordNet, Scikit-learn, Pandas

**Paper:** “Are you a hero or a villain? A semantic role labelling approach for detecting harmful memes”
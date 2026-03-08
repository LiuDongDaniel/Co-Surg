# Co-Surg: Collaborative Perception and Agentic Reflection for Surgical Scene Graph Generation

[![Paper](https://img.shields.io/badge/Paper-Under_Review-orange)]()
[![Code](https://img.shields.io/badge/Code-Coming_Soon-blue)]()
[![Dataset](https://img.shields.io/badge/Dataset-EgoExOR%20%7C%20MM--OR-brightgreen)]()

> **⚠️ Note to Reviewers:** > This repository is the official implementation of **Co-Surg**. To comply with double-blind review policies and protect intellectual property during the review process, the source code is currently withheld. 
> 
> The complete codebase, pre-trained models, and dataset preprocessing scripts will be made fully public **immediately upon paper acceptance**.

---

## 📖 Abstract

Holistic understanding of the Operating Room (OR) is pivotal for next-generation Computer-Assisted Interventions. However, generating robust Surgical Scene Graphs (SSGs) from omni-modal sensor streams presents two fundamental challenges: the *Perceptual Gap* (naive multi-view fusion without cross-view semantic consensus) and the *Cognitive Gap* (single-pass LVLMs ignoring extreme asymmetric clinical risks). 

To address these limitations, we propose **Co-Surg**, a novel framework orchestrating Collaborative Perception and Agentic Reflection. By introducing a Surgical Agent Interaction Module for subtractive refinement and a training-free "System 2" Cognitive Router for explicit clinical risk management, Co-Surg establishes a new state-of-the-art on the large-scale EgoExOR and MM-OR benchmarks, successfully preserving data integrity for automated clinical documentation.

---

## 🚀 Release Roadmap (TODO)

Upon acceptance, we will release the following assets to facilitate full reproducibility:

- [ ] **Core Codebase**: PyTorch implementation of the `Surgical Agent Interaction Module` (including the Adaptive Gating mechanism).
- [ ] **Agentic Reflection Engine**: The training-free `System 2 Cognitive Router` (including prompt templates for Precision-Oriented Verification and Recall-Oriented Affordance Rescue).
- [ ] **Pre-trained Weights**: Fine-tuned LLaVA-v1.5-7B checkpoints for both EgoExOR and MM-OR benchmarks.
- [ ] **Data Pipeline**: Instructions and scripts for processing omni-modal data (Gaze, Hand Pose, Audio, Point Clouds) into unified agent tokens.
- [ ] **Evaluation Scripts**: Scripts to compute decoupled evaluation metrics (Critical Operative Actions vs. Generic Background Relations).

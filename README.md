# Co-Surg: Collaborative Perception with Targeted Reflection for Surgical Scene Graph Generation

[![Paper](https://img.shields.io/badge/Paper-Under_Review-orange)]()
[![Code](https://img.shields.io/badge/Code-Coming_Soon-blue)]()
[![Dataset](https://img.shields.io/badge/Dataset-EgoExOR%20%7C%20MM--OR-brightgreen)]()

> This repository will host the official implementation of **Co-Surg**.
> To protect the integrity of the review process, the source code is not publicly released at this stage.
> The codebase, pretrained models, and preprocessing scripts will be made available upon acceptance.

---

## Abstract

Understanding interactions in the operating room is important for next-generation computer-assisted interventions. Yet generating surgical scene graphs (SSGs) from synchronized multimodal observations remains difficult. Egocentric streams reflect local operative intent but miss broader context, while exocentric views provide a wider scene but are often occluded.

To address this problem, we propose **Co-Surg**, a multimodal framework for surgical scene graph generation that combines explicit cross-view interaction with lightweight post-hoc refinement. At the core of the framework is a Surgical Agent Interaction Module with adaptive gating, which uses exocentric contextual responses to refine egocentric representations and reduce view-specific visual ambiguity before graph prediction. In addition, we introduce a training-free refinement step that is selectively applied to a small set of ambiguous or high-risk predicates, aiming to suppress false positives in dynamic actions and recover missed fine-grained interactions through object-affordance cues.

Experiments on EgoExOR show that Co-Surg improves over the official baseline under the same multimodal setting. Preliminary plug-and-play results on MM-OR also suggest that the refinement strategy may retain limited utility in exocentric-only settings without retraining the visual backbone.

---

## Release Roadmap

Upon acceptance, we plan to release the following materials:

- [ ] Core PyTorch implementation of Co-Surg
- [ ] Surgical Agent Interaction Module with adaptive gating
- [ ] Training-free targeted reflection module
- [ ] Pretrained model checkpoints
- [ ] Data preprocessing scripts for multimodal inputs
- [ ] Evaluation scripts and instructions for reproduction

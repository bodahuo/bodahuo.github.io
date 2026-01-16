---
title: "LocoTouch: Learning Dynamic Quadrupedal Transport with Tactile Sensing"
collection: publications
category: conferences
permalink: /publication/locotouch-corl-2025
excerpt: "Learning dynamic quadrupedal transport with tactile sensing."
date: 2025-08-30  # year known; adjust month/day if you want
venue: "Conference on Robot Learning (CoRL ’25), PMLR 305: 2779–2801"
paperurl: "https://proceedings.mlr.press/v305/lin25a.html"
citation: "Lin, C.; Song, Y. R.; Huo, B.; Yu, M.; Wang, Y.; Liu, S.; Yang, Y.; Yu, W.; Zhang, T.; Tan, J.; Luo, Y.; Zhao, D. (2025). &quot;LocoTouch: Learning Dynamic Quadrupedal Transport with Tactile Sensing.&quot; <i>Conference on Robot Learning (CoRL 2025)</i>, PMLR 305: 2779–2801."
---

**Paper:** [PMLR proceedings](https://proceedings.mlr.press/v305/lin25a.html)

**Project page:** [linchangyi1.github.io/LocoTouch](https://linchangyi1.github.io/LocoTouch/)

### Summary
LocoTouch studies tactile-aware learning for **dynamic quadrupedal transport**. The core idea is to use distributed tactile sensing to improve robustness during long-horizon carrying tasks, especially under contact uncertainty.

### My Contribution
I contributed to both the **hardware** and **learning / sim-to-real pipeline** that enable tactile-aware transport:

- **Designed and fabricated the distributed tactile hardware** (221-taxel piezoresistive array) to provide wide-area, high-density contact feedback over the robot’s back. I iterated on the physical build and wiring/scanning approach to support reliable, repeatable sensing during dynamic motion.
- **Improved manufacturability and robustness of the sensing stack**, focusing on practical issues that matter for long experiments—repeatability, yield, and stability across runs. In parallel, I supported updates to the PCB and sensing electronics with the goal of reducing cross-talk and increasing frame rate.
- **Helped develop the tactile-aware transport policy**, contributing to a teacher–student training pipeline (PPO → DAgger) and emphasizing reliable tracking behavior with PD control so the learned policy remains stable during real hardware execution.


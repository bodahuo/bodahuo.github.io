---
title: "LightTact: A Visual-Tactile Fingertip Sensor for Deformation-Independent Contact Sensing"
collection: publications
category: conferences
permalink: /publication/lighttact-arxiv-2025
excerpt: "A visual–tactile fingertip sensor that enables deformation-independent contact sensing by capturing both deformation and surface appearance cues."
date: 2025-12-01
venue: "arXiv preprint arXiv:2512.20591"
paperurl: "https://arxiv.org/abs/2512.20591"
citation: "Lin, C.<sup>&#8224;</sup>; Huo, B.<sup>&#8224;</sup>; Yu, M.; Ruppel, E.; Chen, B.; Francis, J.; Zhao, D. (2025). &quot;LightTact: A Visual-Tactile Fingertip Sensor for Deformation-Independent Contact Sensing.&quot; <i>arXiv preprint</i> arXiv:2512.20591. <sup>&#8224;</sup>Equal contribution."
---

**Paper:** [Arxiv preprint](https://arxiv.org/abs/2512.20591)

## Summary
LightTact is a visual–tactile fingertip sensor designed to make contact sensing more robust under large and diverse deformations. By capturing both the tactile deformation field and surface appearance cues (e.g., color / text), the sensor supports deformation-independent contact understanding and downstream manipulation/perception tasks.

## My contributions (equal contribution)
My work focused on building a sensor + pipeline that is robust in the real world and useful for downstream recognition:

- **Designed and developed the visual–tactile sensing approach** to capture not only deformation signals but also overlaid appearance cues (e.g., color/text). This adds information beyond deformation-only tactile baselines and improves recognition performance when surface appearance matters.
- **Demonstrated robust contact detection and feature extraction on extremely soft, low-stiffness materials** (including messy or highly deformable contacts such as water droplets, facial cream, and thin plastic film), where standard contact sensing can be unreliable.
- **Integrated the sensor with a vision-language model (VLM) in a full system demo**, using the sensor output to sort resistors by color codes with high end-to-end accuracy (>90%). This served as a practical validation that the sensor’s cues are informative and usable in a complete perception-to-action loop.

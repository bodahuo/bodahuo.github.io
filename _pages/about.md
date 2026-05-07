---
permalink: /
title: "Home"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## About

I completed my M.S. degree in Mechanical Engineering at Carnegie Mellon University in 2026. Previously, I completed my B.S. in Mechanical Engineering at UC Santa Barbara in 2024.

My research goal is to make robots **reliably perceive and act under contact uncertainty**. I work on tactile sensing systems and learning-based control for contact-rich tasks, with an emphasis on real-world robustness.

I am honored to have worked with [Prof. Ding Zhao](https://www.meche.engineering.cmu.edu/directory/bios/zhao-ding.html) and PhD student [Changyi Lin](https://linchangyi1.github.io/) at CMU’s [Safe AI Lab](https://safeai-lab.github.io/), and with [Prof. Elliot Hawkes](https://me.ucsb.edu/people/elliot-hawkes) at UCSB.

## Research interests
- Visual–tactile sensing and piezoresistive tactile arrays  
- Learning-based whole-body control for contact-rich robotics  
- Sim-to-real reinforcement learning and evaluation for robustness and safety  

## Publications

{% include base_path %}
{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}

## Currently
- Building and calibrating tactile sensing hardware for reliable contact signals  
- Developing tactile-aware policies and evaluation protocols for real robots  
- Studying sim-to-real transfer for contact-rich manipulation and locomotion  

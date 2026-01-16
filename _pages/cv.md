---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download-links" style="margin-bottom: 1rem;">
  <a href="{{ '/files/Boda_Resume_26.pdf' | relative_url }}" class="btn btn--primary">Download CV as PDF</a>
</div>

## Preview

<div style="width: 100%; height: 1100px; border: 1px solid #eee; border-radius: 8px; overflow: hidden;">
  <iframe
    src="{{ '/files/Boda_Resume_26.pdf' | relative_url }}"
    width="100%"
    height="1100"
    style="border:0;">
  </iframe>
</div>

---

Education
======
* M.S. in Mechanical Engineering, Carnegie Mellon University, 2026 (expected)
  * GPA: 3.84/4.00
* B.S. in Mechanical Engineering, University of California Santa Barbara, 2024
  * GPA: 3.86/4.00

Publications
======
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 3
cv_pdf: /assets/pdf/cv_ferran_v2.0.2.pdf
---

<div class="d-flex justify-content-end mb-3">
  <a href="{{ page.cv_pdf | default: '/assets/pdf/cv_ferran_v2.0.2.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" class="btn btn-sm btn-outline-primary">
    <i class="fa-solid fa-file-pdf"></i> Download PDF
  </a>
</div>

<object data="{{ page.cv_pdf | default: '/assets/pdf/cv_ferran_v2.0.2.pdf' | relative_url }}" type="application/pdf" width="100%" style="height: 85vh; min-height: 800px; display: block;">
  <iframe src="{{ page.cv_pdf | default: '/assets/pdf/cv_ferran_v2.0.2.pdf' | relative_url }}" width="100%" style="height: 85vh; min-height: 800px; border: none;">
    <p>Your browser does not support inline PDF viewing. You can <a href="{{ page.cv_pdf | default: '/assets/pdf/cv_ferran_v2.0.2.pdf' | relative_url }}">download the PDF here</a>.</p>
  </iframe>
</object>

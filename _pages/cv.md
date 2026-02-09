---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 6
cv_pdf: assets/pdf/Neha_Shariq_CV.pdf
---
<div>

<center>
<p style="font-weight: bold; text-decoration: underline;">

<a href="{{ page.cv_pdf }}" download>
  <div class="pdficon">
    {% include figure.liquid loading="eager" path="assets/img/pdf.jpg" %}
  </div>
  Download PDF
</a>

&emsp;&emsp;&emsp;

<a href="{{ page.cv_pdf }}" target="_blank">
  <div class="pdficon">
    {% include figure.liquid loading="eager" path="assets/img/view.png" %}
  </div>
  View PDF
</a>

</p>
</center>

<center>
<iframe src="{{ page.cv_pdf }}" width="100%" height="600"></iframe>
</center>

</div>


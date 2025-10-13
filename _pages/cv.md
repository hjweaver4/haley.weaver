---
layout: default
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: Weaver_CV.pdf # you can also use external links here
description: 
toc:
  sidebar: left
---
# My PDF Document

<div style="position: relative; padding-bottom: 120\%; height: 0; overflow: hidden; border: 1px solid #ddd; border-radius: 8px;">
  <iframe 
    src="{{ '/assets/pdf/Weaver_CV.pdf' | relative_url }}" 
    style="position: absolute; top: 0; left: 0; width: 100\%; height: 100\%;" 
    frameborder="0">
  </iframe>
</div>

<p style="text-align: center; margin-top: 1em;">
  <a href="{{ '/assets/files/example.pdf' | relative_url }}" download class="btn">
    📄 Download PDF
  </a>
</p>

<style>
.btn {
  display: inline-block;
  background-color: #007acc;
  color: #fff !important;
  padding: 10px 20px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
  transition: background-color 0.2s ease;
}
.btn:hover {
  background-color: #005fa3;
}
</style>

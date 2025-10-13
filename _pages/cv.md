---
layout: cv
permalink: /cv/
title: Curriculum Vitae
nav: true
nav_order: 5
cv_pdf: Weaver_CV.pdf # you can also use external links here
description: 
toc:
  sidebar: left
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive PDF Embed</title>
  <style>
    .pdf-container {
      position: relative;
      width: 100\%;
      padding-top: 141.42\%; /* 8.5x11 ratio (height/width * 100\%) */
    }
    .pdf-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100\%;
      height: 100\%;
      border: none;
    }
    @media (min-width: 768px) {
      .pdf-container {
        padding-top: 75\%; /* Less tall on larger screens */
      }
    }
  </style>
</head>
<body>
  <h2>View PDF</h2>
  <div class="pdf-container">
    <iframe src="Weaver_CV.pdf" type="application/pdf"></iframe>
  </div>
</body>
</html>

---
layout: default
permalink: /cv/
title: CV
nav: true
nav_order: 2
description: This is a description of the page. You can modify it in '_pages/cv.md'.
toc:
  sidebar: left
---

<style>
.pdf-container {
  width: 100%;
  display: flex;
  justify-content: center;
  margin: 20px 0;
}

.pdf-container object {
  width: 90%;
  height: 800px;
  max-width: 1000px;
}

@media (max-width: 768px) {
  .pdf-container object {
    width: 100%;
    height: 600px;
  }
}
</style>

<div class="pdf-container">
  <object data="/cv.pdf" type="application/pdf"></object>
</div>

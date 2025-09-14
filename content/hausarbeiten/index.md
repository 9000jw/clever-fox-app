---
title: Hausarbeiten
date: 2023-12-01
share: false
---

<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="p-4">

<div class="accordion" id="testAccordion">
  <div class="accordion-item">
    <h2 class="accordion-header" id="h1">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#c1">
        Test 1
      </button>
    </h2>
    <div id="c1" class="accordion-collapse collapse show" data-bs-parent="#testAccordion">
      <div class="accordion-body">Body 1</div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="h2">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#c2">
        Test 2
      </button>
    </h2>
    <div id="c2" class="accordion-collapse collapse" data-bs-parent="#testAccordion">
      <div class="accordion-body">Body 2</div>
    </div>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
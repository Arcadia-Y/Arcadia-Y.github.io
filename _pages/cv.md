---
layout: default
permalink: /cv/
title: cv
nav: true
nav_order: 5
description: CV - redirects to PDF
---

<script>
window.location.replace("{{ '/assets/pdf/CV.pdf' | relative_url }}");
</script>

<noscript>
  <p>Redirecting to CV...</p>
  <p><a href="{{ '/assets/pdf/CV.pdf' | relative_url }}">Click here if you are not redirected automatically</a></p>
</noscript>

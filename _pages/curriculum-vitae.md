---
layout: single
permalink: /cv/
author_profile: true
title: "Curriculum Vitae"
---

You can view my full CV below or download it directly.

<br>

<iframe id="cv-iframe" width="100%" height="800px" style="border: none; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.15);"></iframe>

<br>
<br>

<p><a id="download-link" class="btn btn--primary">Download CV as PDF</a></p>

<script>
  // This function runs after the page has loaded
  document.addEventListener("DOMContentLoaded", function() {
    // Path to your CV
    var cvPath = "/files/Muhammad_Waqas_CV.pdf";

    // Find the iframe and set its source to the CV path
    var iframe = document.getElementById("cv-iframe");
    if (iframe) {
      iframe.src = cvPath;
    }

    // Find the download link and set its href
    var downloadLink = document.getElementById("download-link");
    if (downloadLink) {
      downloadLink.href = cvPath;
      downloadLink.setAttribute("download", "Muhammad_Waqas_CV.pdf");
    }
  });
</script>

---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

<h2>My Curriculum Vitae</h2>

<!-- <embed src="/files/cv.pdf#view=Fit" type="application/pdf" width="100%" height="800px" /> -->

<!-- Alternatively, you can use the iframe tag -->
<!-- <iframe src="/assets/files/cv.pdf" width="100%" height="800px"></iframe> -->

<div id="pdf-container">
  <embed id="pdf-embed" src="/assets/files/cv.pdf#view=Fit" type="application/pdf" width="100%" />
</div>

<script>
  window.onload = function() {
    var embed = document.getElementById('pdf-embed');
    var container = document.getElementById('pdf-container');

    // Try to set the height based on the document's body size or the container's width
    embed.height = container.clientWidth * 1.3 + 'px'; // Adjust 1.3 based on aspect ratio
  };
</script>

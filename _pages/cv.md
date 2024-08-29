---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

<h5> Last updated: Aug 29, 2024 </h5>

<!-- <iframe src="/files/cv.pdf#view=Fit" width=100vh style="height: 100vh; border: none;"></iframe> -->

<!-- <div style="width: 100%; height: 100vh;">
  <embed src="/files/cv.pdf#view=Fit" type="application/pdf" width="100%" height=80vh />
  <embed src="/files/cv.pdf#view=Fit" type="application/pdf" width="100%" height="100%" style="border: none;">
</div> -->

<style>
    /* Container for the iframe to manage responsive behavior */
    .pdf-wrapper {
        position: relative;
        width: 100%;
        padding-top: 56.25%; /* 16:9 Aspect Ratio */
        height: 0;
        overflow: hidden;
    }

    /* The iframe itself */
    .pdf-wrapper iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove border for a cleaner look */
    }

    /* Full-width on mobile screens */
    @media only screen and (max-width: 768px) {
        .pdf-wrapper {
            padding-top: 100%; /* Adjust the aspect ratio for mobile */
            width: 100%;
            margin: 0 auto;
        }
    }

    @media only screen and (max-width: 480px) {
        .pdf-wrapper {
            padding-top: 120%; /* Adjust the aspect ratio for small screens */
            width: 100%;
            margin: 0 auto;
        }
    }
</style>

<!-- Responsive iframe for the PDF -->
<div class="pdf-wrapper">
    <iframe src="/files/cv.pdf#zoom=100" type="application/pdf"></iframe>
</div>


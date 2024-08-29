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
        width: 100%; /* Full width of the section/container */
        height: 100vh; /* Full height of the viewport */
        overflow: auto; /* Allow scrolling */
    }

    /* The iframe itself */
    .pdf-wrapper iframe {
        width: 100%;
        height: 100%;
        border: none; /* Remove border for a cleaner look */
    }

    /* Adjustments for smaller screens */
    @media only screen and (max-width: 768px) {
        .pdf-wrapper {
            height: 100vh; /* Ensure full viewport height */
        }

        .pdf-wrapper iframe {
            width: 100%;
            height: 100%;
        }
    }

    /* Adjustments for very small screens */
    @media only screen and (max-width: 480px) {
        .pdf-wrapper {
            height: 100vh; /* Ensure full viewport height */
            margin: 0 auto;
        }

        .pdf-wrapper iframe {
            width: 100%;
            height: 100%;
        }
    }
</style>

<!-- Responsive iframe for the PDF -->
<div class="pdf-wrapper">
  <iframe src="/files/cv.pdf#zoom=auto" type="application/pdf"></iframe>
</div>

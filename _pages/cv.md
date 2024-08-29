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
        height: 0;
        padding-bottom: 141.42%; /* Adjust for typical A4 aspect ratio */
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

    /* Adjustments for smaller screens */
    @media only screen and (max-width: 768px) {
        .pdf-wrapper {
            width: 100%; /* Ensure full width */
/*             padding-bottom: 141.42%; /* Maintain aspect ratio */ */
        }

        .pdf-wrapper iframe {
            width: 100%;
            height: 100%;
        }
    }

    /* Adjustments for very small screens */
    @media only screen and (max-width: 480px) {
        .pdf-wrapper {
            width: 100%; /* Full width of the screen */
/*             padding-bottom: 141.42%; /* Maintain aspect ratio */ */
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
<!--     <iframe src="/files/cv.pdf#zoom=page-width" type="application/pdf"></iframe> -->
  <iframe src="/files/cv.pdf#zoom=fit" type="application/pdf"></iframe>
</div>

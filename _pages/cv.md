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
        padding-top: 130%; /* Ensures enough height to display the entire page on all screens */
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

    /* Adjustments for wide screens */
    @media only screen and (min-width: 1024px) {
        .pdf-wrapper {
            width: 80%; /* Shrinks the PDF display on wide screens */
            margin: 0 auto; /* Center the iframe on wide screens */
        }
    }
</style>

<!-- Responsive iframe for the PDF -->
<div class="pdf-wrapper">
    <iframe src="/files/cv.pdf#zoom=page-fit" type="application/pdf"></iframe>
</div>

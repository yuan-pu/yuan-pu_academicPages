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
    /* Container for the object to manage responsive behavior */
    .pdf-wrapper {
        position: relative;
        width: 100%; /* Full width of the section/container */
        height: 100vh; /* Full height of the viewport */
        overflow: auto; /* Allow scrolling */
    }

    /* The object itself */
    .pdf-wrapper object {
        width: 100%;
        height: 100%;
        border: none; /* Remove border for a cleaner look */
    }

    /* Adjustments for smaller screens */
    @media only screen and (max-width: 768px) {
        .pdf-wrapper {
            height: 100vh; /* Ensure full viewport height */
        }

        .pdf-wrapper object {
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

        .pdf-wrapper object {
            width: 100%;
            height: 100%;
        }
    }
</style>

<!-- Responsive object for the PDF -->
<div class="pdf-wrapper">
<!--   <object data="/files/cv.pdf#zoom=auto" type="application/pdf">
    <p>Your browser does not support PDFs. <a href="/files/cv.pdf">Download the PDF</a>.</p>
  </object> -->
  <object data="/files/cv.pdf#zoom=auto" type="application/pdf">
        <embed src="/files/cv.pdf#zoom=auto" type="application/pdf" />
    </object>
</div>

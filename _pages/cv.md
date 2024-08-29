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
        padding-top: 56.25%; /* 16:9 Aspect Ratio, adjust as needed */
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

    /* Adjustments for medium screens (tablets, small desktops) */
    @media only screen and (max-width: 1024px) {
        .pdf-wrapper {
            padding-top: 75%; /* 4:3 Aspect Ratio */
        }
    }

    /* Adjustments for mobile screens */
    @media only screen and (max-width: 768px) {
        .pdf-wrapper {
            padding-top: 100%; /* Aspect ratio closer to 1:1 */
            width: 80%; /* Reduce width to 95% on mobile devices */
            margin: 0 auto; /* Center the iframe */
        }

        .pdf-wrapper iframe {
            width: 100%;
            height: 100%;
        }
    }

    /* Further adjustment for very small mobile screens */
    @media only screen and (max-width: 480px) {
        .pdf-wrapper {
            padding-top: 120%; /* Further adjustment for small screens */
            width: 80%; /* Reduce width to 90% */
            margin: 0 auto; /* Center the iframe */
        }
    }
</style>

<!-- Responsive iframe for the PDF -->
<div class="pdf-wrapper">
    <iframe src="/files/cv.pdf#view=FitH" type="application/pdf"></iframe>
</div>


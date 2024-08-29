---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

<h5> Last updated: Aug 29, 2024 </h5>


<style>
    /* Container for the iframe to manage responsive behavior */
    .pdf-wrapper {
        position: relative;
        width: 100%; /* Full width of the section/container */
        height: 0;
        padding-bottom: 100%; /* Ensures height scales with the width */
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
            padding-bottom: 141.42%; /* Adjust for typical A4 aspect ratio */
        }

        .pdf-wrapper iframe {
            width: 100%;
            height: 100%;
        }
    }

    /* Adjustments for wide screens */
    @media only screen and (min-width: 1024px) {
        .pdf-wrapper {
            width: 100%; /* Use full width of the section/container */
            padding-bottom: 141.42%; /* Maintain aspect ratio */
            margin: 0 auto;
        }
    }
</style>

<!-- Responsive iframe for the PDF -->
<div class="pdf-wrapper">
  <iframe id="pdf-frame" src="/files/cv.pdf#zoom=auto&scrollbar=1" type="application/pdf"></iframe>
</div>

<script>
    // Function to switch the PDF link based on screen size
    function switchPDFLink() {
        var iframe = document.getElementById('pdf-frame');
        var screenWidth = window.innerWidth;

        if (screenWidth <= 768) {
            // Use Google Docs preview link for smaller screens
            iframe.src = "https://drive.google.com/file/d/1YQQI0c3ysU20NTOYvtSIWDdMoJ8rmmqo/preview";
        } else {
            // Use the original file link for larger screens
            iframe.src = "/files/cv.pdf#zoom=auto&scrollbar=1";
        }
    }

    // Check screen size on page load
    window.onload = switchPDFLink;

    // Check screen size on window resize
    window.onresize = switchPDFLink;
</script>

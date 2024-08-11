---
layout: archive
title: "Teaching Experience"
permalink: /teaching/
author_profile: true
---

## University of Warwick 
### Senior Graduate Teaching Assistant: 2021/2022 
* International Economics (EC312)
* Economics (EC204)

<!--
## University of Cambridge 
### Teaching Assistant for St John’s College: 2020/2021
* Paper IV International Trade 
-->

<h3 class="expandable-header">University of Warwick</h3>
<div class="expandable-section">
    <p>Here you can provide detailed information about your work at the University of Warwick. This content will be hidden by default and shown when the header is clicked.</p>
    <ul>
        ### Senior Graduate Teaching Assistant: 2021/2022 
        * International Economics (EC312)
        * Economics (EC204)
    </ul>
</div>

<style>
    .expandable-header {
        font-size: 18px;
        font-weight: bold;
        color: #007BFF;
        cursor: pointer;
        margin-bottom: 5px;
        border-left: 4px solid #007BFF;
        padding-left: 10px;
        transition: color 0.3s ease;
    }

    .expandable-header:hover {
        color: #0056b3;
    }

    .expandable-section {
        display: none;
        margin-top: 10px;
        padding: 10px;
        background-color: #f9f9f9;
        border-left: 4px solid #007BFF;
        transition: max-height 0.3s ease;
        overflow: hidden;
    }

    .expandable-section.show {
        display: block;
    }
</style>

<script>
    document.addEventListener("DOMContentLoaded", function() {
        var headers = document.querySelectorAll('.expandable-header');
        headers.forEach(function(header) {
            header.addEventListener('click', function() {
                var section = header.nextElementSibling;
                if (section.classList.contains('show')) {
                    section.classList.remove('show');
                } else {
                    section.classList.add('show');
                }
            });
        });
    });
</script>

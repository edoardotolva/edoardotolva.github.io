---
layout: archive
title: "Teaching Experience"
permalink: /teaching/
author_profile: true
---


<!--### Senior Graduate Teaching Assistant: 2021/2022 
* International Economics (EC312)
* Economics (EC204) -->

<!--
## University of Cambridge 
### Teaching Assistant for St John’s College: 2020/2021
* Paper IV International Trade 
-->
 University of Warwick 
<h3 class="expandable-header">
    <span class="line"></span>
    <span class="arrow">&#x25BC;</span>
</h3>
<div class="expandable-section">
 2021/2022 <b>  Senior Graduate Teaching Assistant:<b>
    <ul>
        <li>  International Economics (EC312) </li>
        <li>  Economics (EC204) </li>
    </ul>
</div>

University of Cambridge
<h3 class="expandable-header">
    <span class="line"></span>
    <span class="arrow">&#x25BC;</span>
</h3>
<div class="expandable-section">
2020/2021  <b> Teaching Assistant for St John’s College:<b>
    <ul>
        <li> Paper IV International Trade </li>
    </ul>
</div>

<style>
    .expandable-header {
        display: flex;
        align-items: center;
        cursor: pointer;
        margin-bottom: 5px;
        padding-left: 10px;
        transition: color 0.3s ease;
    }

    .line {
        flex-grow: 1;
        height: 2px;
        background-color:  #333;
        margin-right: 10px;
    }

    .arrow {
        font-size: 18px;
        color:  #333;
        transition: transform 0.3s ease;
    }

    .expandable-header:hover .arrow {
        color: #0056b3;
    }

    .expandable-section {
        display: none;
        margin-top: 10px;
        padding: 10px;
        background-color: #f9f9f9;
        # border-left: 4px solid #007BFF;
        transition: max-height 0.3s ease;
        overflow: hidden;
    }

    .expandable-section.show {
        display: block;
    }

    .expandable-header.show .arrow {
        transform: rotate(180deg);
    }
</style>

<script>
    document.addEventListener("DOMContentLoaded", function() {
        var headers = document.querySelectorAll('.expandable-header');
        headers.forEach(function(header) {
            header.addEventListener('click', function() {
                var section = header.nextElementSibling;
                var arrow = header.querySelector('.arrow');
                if (section.classList.contains('show')) {
                    section.classList.remove('show');
                    header.classList.remove('show');
                } else {
                    section.classList.add('show');
                    header.classList.add('show');
                }
            });
        });
    });
</script>

---
layout: archive
title: "Teaching Experience"
permalink: /teaching/
author_profile: true
---

<!-- Old Format -->
<!--### Senior Graduate Teaching Assistant: 2021/2022 
* International Economics (EC312)
* Economics (EC204) 
## University of Cambridge 
### Teaching Assistant for St John’s College: 2020/2021
* Paper IV International Trade 
-->
I have taught several courses at the master’s and bachelor’s levels on topics related to international trade and macroeconomics.

<!-- First Expandable Section -->
<h3 class="expandable-header">
    <span class="header-text"> University of Warwick </span>
    <span class="line-container">
        <span class="line"></span>
        <span class="arrow">&#x25BC;</span>
    </span>
</h3>
<div class="expandable-section">
 <b>  Senior Graduate Teaching Assistant (2021/2022):</b> 
    <ul>
        <li>  International Economics (EC312) </li>
        <li>  Economics 2 (EC204) </li>
    </ul>
</div>

<!-- Second Expandable Section -->
<h3 class="expandable-header">
    <span class="header-text"> University of Camdridge </span>
    <span class="line-container">
        <span class="line"></span>
        <span class="arrow">&#x25BC;</span>
    </span>
</h3>
<div class="expandable-section">
<b> Teaching Assistant for St John’s College (2020/2021):</b>
    <ul>
        <li> Paper IV International Trade </li>
    </ul>
</div>

<style>
    .expandable-header {
    display: flex;
    flex-direction: column;
    cursor: pointer;
    margin-bottom: 10px;
    #padding-left: 10px; /*eliminate indent to the left*/
    transition: color 0.3s ease;
}

.header-text {
    font-size: 20px;
    color: $dark-gray; /* Adjust this color to match your site's text color */
    margin-bottom: 5px;
}

.line-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
}

.line {
    flex-grow: 1;
    height: 2px;
    background-color: #333; /* Adjust color as needed */
    margin-right: 10px;
}

.arrow {
    font-size: 16px;
    color:#333; /* Adjust color as needed */
    transition: transform 0.3s ease;
}

.expandable-header:hover .arrow {
    color: #0056b3;
}

.expandable-section {
    display: none;
    margin-top: 10px;
    padding: 10px;
    background-color: #fef8f8;
  font-size: 18px;
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


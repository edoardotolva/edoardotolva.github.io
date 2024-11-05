---
permalink: /
title: "Edoardo Tolva"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align: justify;">
I am a PhD candidate at the <b>University of Warwick</b>. My research interests focus on <b>International Trade</b>, <b> Environmental Economics</b>, and <b>Urban Economics</b>. In particular, I am interested in studying how transportation shapes economic activity across countries. I have been an academic visitor at the <b>Bank of England</b> from September 2022 to July 2024. I also have been a research assistant at the <b>Centre for Economic Performance (CEP)</b> at LSE from September 2020 to May 2023. </div>  <br>



<b> I will be on the Job Market in 2024-2025. </b>  

References: 
<a href="https://warwick.ac.uk/fac/soc/economics/staff/dnovy/" style="text-decoration: none" target="_blank">Prof. Dennis Novy</a>, <a href="https://sites.google.com/site/msantamariaupf/home" style="text-decoration: none" target="_blank"> 
Prof. Marta Santamaria</a>,  <a href="https://warwick.ac.uk/fac/soc/economics/staff/cperroni/" style="text-decoration: none" target="_blank">Prof. Carlo Perroni</a>,  <a href="https://sites.google.com/site/davidedelprete1986/" style="text-decoration: none" target="_blank">Prof. Davide Del Prete</a>

<h3 class="expandable-header">
    <span class="header-text">One Way or Another: Modes of Transport and International Trade (JMP) </span>
    <span class="line-container">
        <span class="line"></span>
        <span class="arrow">&#x25BC;</span>
    </span>
</h3>
<div style="text-align: justify;" class="expandable-section">
The transport sector is the backbone of international trade and has faced multiple disruptions in recent years. I study the substitutability between different transport modes and how mode-specific trade cost shocks affect international trade flows. I use the closure of Russian airspace in 2022 as an exogenous change in transport costs to provide novel estimates of the elasticity of substitution between transport modes. To quantify the importance of this margin of adjustment in equilibrium, I develop a Ricardian model of international trade with multiple transport modes. Modes are substitutable but endogenous congestion forces limit substitutability. I apply this framework to quantify the effects of recent trade cost shocks such as the closure of Russian airspace and the Suez Canal blockage. Transport mode substitution reduces welfare losses by 4% relative to a non-substitution scenario. However, substitution has potentially negative consequences for the carbon footprint of international trade. Higher sea transport costs can lead to increased carbon emissions due to substitution toward more carbon-intensive air transport.
You can find the draft <a href="https://edoardotolva.github.io/files/edoardotolva-jmp.pdf">here</a>
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
    font-size: 18px;
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
  font-size: 14px;
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







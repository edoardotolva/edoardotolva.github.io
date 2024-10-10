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
I am a Phd candidate at the <b>University of Warwick</b>. My research interests focus on <b>International Trade</b>, <b>Enviromental Economics</b>, and <b>Urban Economics</b>. In particular, I am interested in studying how transportation shapes economic activities across countries. 
</div>

I have been an academic visitor at the <b>Bank of England</b> from September 2022 to July 2024.  

<b> I will be on the Job Market in 2024-2025. </b> 

<h3 class="expandable-header">
    <span class="header-text">One Way or Another: Modes of Transport and International Trade (JMP) </span>
    <span class="line-container">
        <span class="line"></span>
        <span class="arrow">&#x25BC;</span>
    </span>
</h3>
<div style="text-align: justify;" class="expandable-section">
The transportation sector is the backbone of international trade and has faced multiple disruptions in recent years. I study the substitutability between different transport modes (such as air and ocean shipping) and how mode-specific trade cost shocks affect international trade flows. I use the closure of Russian airspace in 2022 as an exogenous change in transport costs to provide novel estimates of the elasticity of substitution between transport modes. To quantify the importance of this margin of adjustment in equilibrium, I develop a Ricardian model of international trade with multiple transport modes. Higher trade costs are endogenously mitigated by a shift to relatively cheaper transport modes, thereby dampening the impact of the shock. However, endogenous congestion forces limit the ability to fully substitute. I apply this framework to quantify the effects of recent shocks to the transport sector, such as the closure of the Suez Canal. I find that transport mode substitution reduces welfare losses by 6% relative to a non- substitution scenario. However, this substitutability also has potential negative consequences for the carbon footprint of international trade. Compared to a no-substitution scenario, higher maritime transport costs lead to increased carbon emissions due to substitution toward more carbon-intensive air transport
<b><i>Draft coming soon</i></b> 
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







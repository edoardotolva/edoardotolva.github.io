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

I have also been an academic visitor at the <b>Bank of England</b> from September 2022 to July 2024.  

<b> I will be on the Job Market in 2024-2025. </b> 

## <b>Job Market Paper:</b>
<h3 class="expandable-header">
    <span class="header-text"> One Way or Another: Modes of Transport and International Trade <i>(Draft coming soon)</i></span>
    <span class="line-container">
        <span class="line"></span>
        <span class="arrow">&#x25BC;</span>
    </span>
</h3>
<div style="text-align: justify;" class="expandable-section">
The transportation sector is the backbone of international trade and has faced multiple disruptions
in recent years. I study the substitutability of different transport modes (such as
air and ocean shipping) and how mode-specific trade cost shocks affect international trade
flows. First, I use the closure of Ukrainian-Russian airspace as an exogenous increase
in air transport costs to provide novel estimates of the elasticity of substitution between
transport modes. Second, to quantify the importance of this new margin of adjustment in
equilibrium, I build a Ricardian model of international trade with multiple transport modes.
Higher trade costs on a particular route are endogenously mitigated by a switch to relatively
cheaper transport modes, thereby reducing the impact of the shock. I also introduce congestion
forces that limit the ability to substitute. Finally, I apply this framework to evaluate
the consequences of three distinct transport cost shocks: the closure of Ukrainian-Russian
airspace, the closure of the Suez Canal, and a policy aimed at reducing the carbon footprint
of ocean shipping, effectively increasing maritime transport costs. I find that transport
mode substitution plays a significant role in mitigating welfare losses arising from increased
transport costs. However, the study also highlights potential negative implications for the
carbon footprint of international trade. Relative to a no-substitution scenario, higher maritime
transport costs lead to a six percent increase in carbon emissions due to substitution
toward more carbon-intensive air transport.
</div>

<style>
    .expandable-header {
    display: flex;
    flex-direction: column;
    cursor: pointer;
    margin-bottom: 10px;
    padding-left: 10px;
    transition: color 0.3s ease;
}

.header-text {
    font-size: 16px;
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







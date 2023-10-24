---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

## Vision

<div class="row">
<style>
* {
  box-sizing: border-box;
}
.column {
  float: left;
  padding: 2px;
  height: 450px; 
}
.left {
  width: 50%;
}
.right {
  width: 50%;
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
  <div class="column left" style="background-color:rgb(255,255,255);">
    <ul>
      <li>
        My research goal is to develop new fundamentals and computational approaches to high-speed reacting flows and their applications for a sustainable aerospace future.  
      </li>
      <li>
        My past research focused on fundamental theory and modeling of conventional and sustainable aviation fuel combustion, and simulation of low-speed laminar and turbulent reacting flows, from both the continuum aspect and molecular scale. 
      </li>
      <li>
        With the unique foundation in combustion, fluid mechanics, and quantum chemistry, my future research will focus on development of multiscale computational methods integrating <em>ab initio</em> molecular modeling, chemical kinetic modeling, and turbulence-resolved flow simulations for high-speed reacting flow studies. 
      </li>
    </ul>
  </div>
  <div class="column right" style="background-color:rgb(255,255,255);">
    <ul>
      <figure>
        <img src="/images/research/ResearchVision.png" alt="Research Vision" style="width:100%">
      </figure>
    </ul>
  </div>
</div>

## Research directions
<p>Click on each link below for research directions.</p>
<a href="../_pages/research_saf.md" target="_blank" rel="noopener noreferrer">Sustainable aviation fuel modeling</a> 




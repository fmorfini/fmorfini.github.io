---
layout: page
title: CV
permalink: /CV/
position: 1
#feature-img: "assets/img/pexels/travel.jpeg"
position: 4
---

<!-- 
<div id="anim">
<iframe src="/assets/img/Francesca_Morfini_CV.pdf" width="100%"  height = "700px" align="right" style="border:none;">
</iframe>
</div>
 -->

<div id="anim" class="pdf-container">
  <iframe src="{{ '/assets/img/Francesca_Morfini_CV.pdf' | relative_url }}" width="100%" height="700px" style="border:none;"></iframe>
</div>

<p class="mobile-only">
  <a href="{{ '/assets/img/Francesca_Morfini_CV.pdf' | relative_url }}" target="_blank">
    View Full CV (opens in new tab)
  </a>
</p>

<style>
  /* Hide iframe on small screens */
  @media (max-width: 768px) {
    .pdf-container { display: none; }
    .mobile-only { 
      display: block; 
      text-align: center; 
      margin-top: 1rem;
      font-size: 1.1rem;
    }
  }

  /* Hide link on desktop */
  @media (min-width: 769px) {
    .mobile-only { display: none; }
  }

  /* Button styling */
  .mobile-only a {
    display: inline-block;
    background-color: #e63946; /* match your theme’s red */
    color: white;
    padding: 0.75rem 1.25rem;
    border-radius: 8px;
    text-decoration: none;
  }
  .mobile-only a:hover {
    background-color: #c92d3d;
  }
</style>
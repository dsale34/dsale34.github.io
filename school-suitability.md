---
layout: default
title: School Site Suitability Analysis
---

<a href="/" class="back-link">← Back to Home</a>

# School Site Suitability Analysis

<div class="project-tools">
  <span class="tag">ArcGIS Pro</span>
  <span class="tag">Euclidean Distance</span>
  <span class="tag">Reclassify</span>
  <span class="tag">Weighted Overlay</span>
</div>

<div class="project-page">

This project explored potential locations for a new school by comparing two GIS suitability models to answer a planning question: where does the study area offer the most suitable land for school development?

I used ArcGIS Pro to develop two raster-based suitability models using school and recreation site locations, elevation data, and land-use constraints. The first model applied binary logic to identify land that met all specified criteria, including distance from existing schools, proximity to recreation sites, and slope.

<div class="project-figure">
  <img src="/images/444HW1Task1.png" alt="Binary suitability map showing land meeting all school site criteria">
  <p class="figcaption">Binary suitability model — land meeting every threshold for distance from schools, proximity to recreation sites, and slope.</p>
</div>

The second model used the Reclassify and Weighted Sum tools to score locations on a 1–10 suitability scale, assigning equal weights to distance from schools, proximity to recreation sites, and slope.

<div class="project-figure">
  <img src="/images/444HW1Task2.png" alt="Weighted suitability map for candidate new school sites, scored on a 1-10 scale">
  <p class="figcaption">Weighted suitability model — every cell scored 1–10 based on combined criteria.</p>
</div>

Both models identified promising locations in the eastern portion of the study area near two recreation sites, with additional candidate areas in the northwest. Comparing the results highlighted the trade-offs between the two approaches: binary logic clearly identifies locations that meet every requirement but excludes sites that fall just outside a threshold, while weighted suitability captures a broader range of potential sites but can give similar scores to locations with different strengths and weaknesses. I concluded that using both models together could help planners identify stronger candidates for a new school than either model alone.

</div>

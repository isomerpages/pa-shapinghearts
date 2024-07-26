---
title: Full Width
permalink: /full-width/
variant: markdown
description: ""
---

/* Override container to full width */
.container {
  width: 100%;
  max-width: 100%;
  padding: 0;
  margin: 0;
}

/* Specific section full width */
.full-width-section {
  width: 100vw; /* Full viewport width */
  margin-left: calc(-50vw + 50%); /* Center the section */
  background-color: #f9f9f9; /* Background color to match the full width */
}

/* Ensure other elements within the section are styled appropriately */
.full-width-section .stats {
  justify-content: space-around;
}

.full-width-section .stat-item {
  margin: 20px;
  flex: 1 1 200px;
  max-width: 200px;
}

.full-width-section .stat-number {
  font-size: 48px;
  font-weight: bold;
  color: #333;
}

.full-width-section .stat-description {
  font-size: 18px;
  color: #666;
}

.full-width-section .about-link {
  margin-top: 20px;
}

.full-width-section .about-button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #007bff;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
}

.full-width-section .about-button:hover {
  background-color: #0056b3;
}
<section class="stats-section full-width-section">
  <div class="container">
    <div class="stats">
      <div class="stat-item">
        <p class="stat-number">150</p>
        <p class="stat-description">Participating Artists with Disabilities</p>
      </div>
      <div class="stat-item">
        <p class="stat-number">350</p>
        <p class="stat-description">Exhibited Paintings</p>
      </div>
      <div class="stat-item">
        <p class="stat-number">30</p>
        <p class="stat-description">Participating Social Service Agencies and Partners</p>
      </div>
      <div class="stat-item">
        <p class="stat-number">2.8M</p>
        <p class="stat-description">Public Engagements on Social Media</p>
      </div>
    </div>
    <div class="about-link">
      <a class="about-button" href="#">ABOUT US</a>
    </div>
  </div>
</section>



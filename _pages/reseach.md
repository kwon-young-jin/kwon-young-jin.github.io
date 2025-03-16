---
layout: page
permalink: /Research/
title: Research
description:
nav: true
nav_order: 1
---

<!-- 1) Styles for the container, the title+button row, and the abstract button -->
<style>
  .paper-container {
    margin-bottom: 10px; /* Space between papers */
  }
  .paper-title-line {
    display: flex;
    justify-content: space-between; /* Title on left, button on right */
    align-items: center;
    margin-bottom: 4px;            /* Slight spacing below the line */
  }
  .abstract-button {
    background-color: #aaa;  /* Gray background */
    color: #ffffff;          /* White text */
    border: none;            /* Remove default border */
    border-radius: 4px;      /* Slightly round corners */
    padding: 4px 8px;        /* Spacing inside the button */
    cursor: pointer;
    font-size: 0.9rem;
    font-family: sans-serif;
  }
  .abstract-button:hover {
    background-color: #888;  /* Darker gray on hover */
  }
</style>

<!-- 2) Simple JavaScript toggle function -->
<script>
function toggleAbstract(id) {
  const element = document.getElementById(id);
  element.style.display = (element.style.display === "none") ? "block" : "none";
}
</script>

`Blockchain-based Digital Asset Market`

<!-- Paper 1 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>From Boom to Bust and Beyond: A Longitudinal Analysis of NFT Collector Performance</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract1')">Abstract</button>
  </div>
  - <b>YoungJin Kwon</b>, Teng Ye, and Alok Gupta  
  - Presented at WISE 2024  
  - Presented at INFORMS ISR - ISS Paper Development Workshop 2024  
  - Presented at WITS 2023

  <div id="abstract1" style="display: none; margin-top: 5px;">
    <p>
      This paper explores how...
    </p>
  </div>
</div>

<!-- Paper 2 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>Inclusion by Design: How Disintermediation through Art NFT Empowers Minority Artists</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract2')">Abstract</button>
  </div>
  - <b>YoungJin Kwon</b>, Agnes Yang, Gautam Ray  
  - In preparation for a submission to a top-tier journal  
  - Presented at WITS 2024  
  - Presented at CIST 2024  
  - Presented at INFORMS Annual Meeting 2024

  <div id="abstract2" style="display: none; margin-top: 5px;">
    <p>
      This paper examines...
    </p>
  </div>
</div>

<!-- Paper 3 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>Why NFT Market Has Crashed? Antecedents and Consequences of Wash Trading</b> (<i>Potential job market paper</i>)
    <button class="abstract-button" onclick="toggleAbstract('abstract3')">Abstract</button>
  </div>
  - with Alok Gupta, Teng Ye  
  - Analysis in progress (Targeting <i>Management Science</i> Special Issue on Digital Finance)

  <div id="abstract3" style="display: none; margin-top: 5px;">
    <p>
      Abstract coming soon...
    </p>
  </div>
</div>

`AI Creativity and Productivity`

<!-- Paper 4 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>Perception and Valuation of Human-AI Co-created Art: Computational Aesthetics Approach</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract4')">Abstract</button>
  </div>
  - with Alok Gupta  
  - Analysis in progress

  <div id="abstract4" style="display: none; margin-top: 5px;">
    <p>
      Abstract coming soon...
    </p>
  </div>
</div>

<!-- Paper 5 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>The Unintended Consequence: How ChatGPT Amplifies the Research Productivity Gap Between Native and Non-Native English-Speaking Scholars</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract5')">Abstract</button>
  </div>
  - Analysis in progress  
  - <b>YoungJin Kwon</b>, Agnes Yang

  <div id="abstract5" style="display: none; margin-top: 5px;">
    <p>
      Abstract coming soon...
    </p>
  </div>
</div>

`Platform Economy`

<!-- Paper 6 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>Friend or Foe? Bike-sharing and Ride-sharing in New York City</b> (<i>Master's Thesis</i>)
    <button class="abstract-button" onclick="toggleAbstract('abstract6')">Abstract</button>
  </div>
  - <b>YoungJin Kwon</b>, Agnes Yang, Sang-Yong Tom Lee, and Seung Hyun Kim  
  - Presented at WISE 2019  
  - Best paper award at Post-ICIS KrAIS Research Workshop 2019

  <div id="abstract6" style="display: none; margin-top: 5px;">
    <p>
      This research investigates...
    </p>
  </div>
</div>

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
    <b>(1) From Boom to Bust and Beyond: A Longitudinal Analysis of NFT Collector Performance</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract1')">Abstract</button>
  </div>
  <ul>
    <li><b>YoungJin Kwon</b>, Teng Ye, and Alok Gupta</li>
    <li>In preparation for a submission to <i>Information Systems Research</i></li>
    <li>Presented at WISE 2024</li>
    <li>Presented at INFORMS ISR - ISS Paper Development Workshop 2024</li>
    <li>Presented at WITS 2023</li>
  </ul>

  <div id="abstract1" style="display: none; margin-top: 5px;">
    <p>This paper explores how...</p>
  </div>
</div>

<!-- Paper 2 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(2) Inclusion by Design: How Disintermediation through Art NFT Empowers Minority Artists</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract2')">Abstract</button>
  </div>
  <ul>
    <li><b>YoungJin Kwon</b>, Agnes Yang, Gautam Ray</li>
    <li>In preparation for a submission to a top-tier journal</li>
    <li>Presented at WITS 2024</li>
    <li>Presented at CIST 2024</li>
    <li>Presented at INFORMS Annual Meeting 2024</li>
  </ul>

  <div id="abstract2" style="display: none; margin-top: 5px;">
    <p>This paper examines...</p>
  </div>
</div>

<!-- Paper 3 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(3) Why NFT Market Has Crashed? Antecedents and Consequences of Wash Trading</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract3')">Abstract</button>
  </div>
  <ul>
    <li>with Alok Gupta, Teng Ye</li>
    <li>Targeting <i>Management Science</i> Special Issue on Digital Finance</li>
  </ul>

  <div id="abstract3" style="display: none; margin-top: 5px;">
    <p>Abstract coming soon...</p>
  </div>
</div>

`AI Creativity and Productivity`

<!-- Paper 4 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(2) The Unintended Consequence: How ChatGPT Amplifies the Research Productivity Gap Between Native and Non-Native English-Speaking Scholars</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract5')">Abstract</button>
  </div>
  <ul>
    <li><b>YoungJin Kwon</b>, Agnes Yang</li>
    <li>Analysis in progress</li>
  </ul>

  <div id="abstract5" style="display: none; margin-top: 5px;">
    <p>Abstract coming soon...</p>
  </div>
</div>

<!-- Paper 5 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(1) Perception and Valuation of Human-AI Co-created Art: Computational Aesthetics Approach</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract4')">Abstract</button>
  </div>
  <ul>
    <li>with Alok Gupta</li>
    <li>Analysis in progress</li>
  </ul>

  <div id="abstract4" style="display: none; margin-top: 5px;">
    <p>Abstract coming soon...</p>
  </div>
</div>

`Platform Economy`

<!-- Paper 6 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(1) Friend or Foe? Bike-sharing and Ride-sharing in New York City</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract6')">Abstract</button>
  </div>
  <ul>
    <li><b>YoungJin Kwon</b>, Agnes Yang, Sang-Yong Tom Lee, and Seung Hyun Kim</li>
    <li>Presented at WISE 2019 (& <i>Master's Thesis</i>)</li>
    <li>Best paper award at Post-ICIS KrAIS Research Workshop 2019</li>
  </ul>

  <div id="abstract6" style="display: none; margin-top: 5px;">
    <p>This research investigates...</p>
  </div>
</div>

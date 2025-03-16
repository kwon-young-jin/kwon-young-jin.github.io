---
layout: page
permalink: /Research/
title: Research
description:
nav: true
nav_order: 1
---

<!-- 1) Style the Abstract Buttons -->
<style>
  /* Simple styling for all buttons with the .abstract-button class */
  .abstract-button {
    background-color: #0066cc;     /* Primary background color */
    color: #ffffff;               /* Text color */
    border: none;                 /* Remove default border */
    border-radius: 4px;           /* Slightly round corners */
    padding: 6px 12px;            /* Spacing inside the button */
    cursor: pointer;              /* Cursor changes to pointer on hover */
    font-size: 0.9rem;            /* Adjust text size as needed */
    font-family: sans-serif;      /* Use a cleaner font (optional) */
  }
  /* Hover effect */
  .abstract-button:hover {
    background-color: #0052a3;    /* Darken the background slightly on hover */
  }
</style>

<!-- 2) A simple JavaScript function to toggle show/hide any element by ID. -->
<script>
function toggleAbstract(id) {
  const element = document.getElementById(id);
  if (element.style.display === "none") {
    element.style.display = "block";
  } else {
    element.style.display = "none";
  }
}
</script>

## Working Paper

<!-- Paper 1 -->
<b>An Exploration of Investor Strategies and Outcomes on the Roller Coaster Ride in NFT Markets</b>  
- <b>YoungJin Kwon</b>, Teng Ye, and Alok Gupta  
- Presented at WISE 2024  
- Presented at INFORMS ISR - ISS Paper Development Workshop 2024  
- Presented at WITS 2023

<!-- Abstract Button and Hidden Abstract -->
<button class="abstract-button" onclick="toggleAbstract('abstract1')">Abstract</button>
<div id="abstract1" style="display: none; margin: 5px 0;">
  <p>
    This paper explores how...
  </p>
</div>

<br>

<!-- Paper 2 -->
<b>Inclusion by Design: How Disintermediation through Art NFT Empowers Minority Artists</b>  
- <b>YoungJin Kwon</b>, Agnes Yang, Gautam Ray  
- Presented at WITS 2024  
- Presented at CIST 2024  
- Presented at INFORMS Annual Meeting 2024

<button class="abstract-button" onclick="toggleAbstract('abstract2')">Abstract</button>
<div id="abstract2" style="display: none; margin: 5px 0;">
  <p>
    This paper examines...
  </p>
</div>

<br>

## In-progress

<!-- Paper 3 -->
<b>Antecedents and Consequences of NFT Wash Trading</b> (<i>Potential job market paper</i>)  
- with Alok Gupta, Teng Ye  
- Analysis in progress 

<button class="abstract-button" onclick="toggleAbstract('abstract3')">Abstract</button>
<div id="abstract3" style="display: none; margin: 5px 0;">
  <p>
    Abstract coming soon...
  </p>
</div>

<br>

<!-- Paper 4 -->
<b>Perception and Valuation of Human-AI Co-created Art: Computational Aesthetics Approach</b>  
- with Alok Gupta  
- Analysis in progress

<button class="abstract-button" onclick="toggleAbstract('abstract4')">Abstract</button>
<div id="abstract4" style="display: none; margin: 5px 0;">
  <p>
    Abstract coming soon...
  </p>
</div>

<br>

<!-- Paper 5 -->
<b>Friend or Foe? Bike-sharing and Ride-sharing in New York City</b> (<i>Master's Thesis</i>)  
- <b>YoungJin Kwon</b>, Agnes Yang, Sang-Yong Tom Lee, and Seung Hyun Kim  
- Presented at WISE 2019  
- Best paper award at Post-ICIS KrAIS Research Workshop 2019

<button class="abstract-button" onclick="toggleAbstract('abstract5')">Abstract</button>
<div id="abstract5" style="display: none; margin: 5px 0;">
  <p>
    Abstract here...
  </p>
</div>

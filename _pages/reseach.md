---
layout: page
permalink: /Research/
title: Research
description:
nav: true
nav_order: 1
---

<!-- Styles for the container, title-button row, buttons, and abstract box -->
<style>
  .paper-container {
    margin-bottom: 20px;
  }

  .paper-title-line {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 6px;
  }

  .abstract-button {
    background-color: #aaa;
    color: white;
    border: 1px solid transparent;
    border-radius: 20px;
    padding: 6px 12px;
    font-size: 0.85rem;
    font-family: 'Segoe UI', sans-serif;
    cursor: pointer;
    transition: all 0.3s ease;
  }

  .abstract-button:hover {
    background-color: #888;
  }

  .abstract-button.active {
    background-color: #6a0dad; /* Purple */
    border-color: #6a0dad;
  }

  .abstract-box {
    display: none;
    margin-top: 8px;
    border: 1.5px dotted #bbb;
    border-radius: 8px;
    padding: 10px 14px;
    background-color: #fafafa;
    font-size: 0.95rem;
    line-height: 1.5;
  }
</style>

<!-- JavaScript toggle function with button state change -->
<script>
  function toggleAbstract(id, btn) {
    const element = document.getElementById(id);
    const isVisible = element.style.display === "block";

    // Toggle visibility
    element.style.display = isVisible ? "none" : "block";

    // Toggle button appearance and text
    btn.classList.toggle("active", !isVisible);
    btn.innerText = isVisible ? "Abstract" : "Hide Abstract";
  }
</script>

`Blockchain-based Digital Asset Market`

<!-- Paper 1 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(1) Why Has NFT Market Crashed? Antecedents and Consequences of Wash Trading</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract1', this)">Abstract</button>
  </div>
  <ul>
    <li>with Alok Gupta, Teng Ye</li>
    <li>Job market paper</li>
    <li>Targeting <i>Management Science</i> Special Issue on Digital Finance</li>
  </ul>

<div id="abstract1" class="abstract-box">
    <p>Abstract coming soon...</p>
  </div>
</div>

<!-- Paper 2 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(2) From Boom to Bust and Beyond: A Longitudinal Analysis of NFT Collector Performance</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract2', this)">Abstract</button>
  </div>
  <ul>
    <li><b>YoungJin Kwon</b>, Teng Ye, and Alok Gupta</li>
    <li>In preparation for a submission to <i>Information Systems Research</i></li>
    <li>Presented at WISE 2024</li>
    <li>Presented at INFORMS ISR - ISS Paper Development Workshop 2024</li>
    <li>Presented at WITS 2023</li>
  </ul>

<div id="abstract2" class="abstract-box">
    <p>As digital technologies create new products and services, new market participants exhibit diverse sets of behaviors that are rarely predicted by the singular theoretical lens.  IS research has taken the lead in examining user behaviors and developed new measures and even theoretical paradigms to examine emerging products and markets (Bapna et al., 2004).  The rise of Non-Fungible Tokens (NFTs) has attracted global attention and significant investment; however, collector/investor strategies and their investment performance in this nascent market remain largely unexplored.  This paper systematically analyzes the performance of different collector groups in the NFT market using transaction data from prominent NFT art collections.  We examine portfolio returns and realized returns across several collector groups, identified through cluster analysis, where the emphasis was on identifying and interpreting distinct behaviors that might indicate different strategic or tactical investor goals. The study discovers and analyzes trader activities through a significant boom-bust cycle that is discernible through overall market valuation, turnover, volatility, and trading characteristics. The key findings of our study reveal that NFT markets do not show a close resemblance to art collector markets, nor do they exhibit the characteristics of investing markets.  In particular, we find: i) Contrary to expectations from traditional art economics, art collectors who prioritize holding NFTs for an extended period (Buy-and-Holder investors) outperform speculators who chase popular NFTs (Popularity Investors); ii) collectors who concentrate their investments in extremely high-priced NFTs (Masterpiece Collectors) underperform, despite the high demand for such NFTs; iii) collectors with extensive trading experience (Active Traders) tend to outperform, but this advantage is limited to those who entered the market during pre-boom or boom periods; iv) outperforming collector groups tend to minimize extrapolation of past returns but maximize participation in early NFT sales.  Overall, our research provides valuable contributions to the growing literature on blockchain-based digital asset markets and art economics, offering insights into investor behavior, market efficiency, and the dynamics of boom-bust cycles.</p>
  </div>
</div>

<!-- Paper 3 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(3) Inclusion by Design: How Disintermediation through Art NFT Empowers Minority Artists</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract3', this)">Abstract</button>
  </div>
  <ul>
    <li><b>YoungJin Kwon</b>, Agnes Yang, Gautam Ray</li>
    <li>In preparation for a submission to a top-tier journal</li>
    <li>Presented at WITS 2024</li>
    <li>Presented at CIST 2024</li>
    <li>Presented at INFORMS Annual Meeting 2024</li>
  </ul>

<div id="abstract3" class="abstract-box">
    <p>Abstract coming soon...</p>
  </div>
</div>

`GenAI Creativity and Productivity`

<!-- Paper 4 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(1) Large Language Models in Academia: Boosting Productivity and Reinforcing Inequality</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract4', this)">Abstract</button>
  </div>
  <ul>
    <li><b>YoungJin Kwon</b></li>
    <li>Manuscript available</li>
  </ul>

<div id="abstract4" class="abstract-box">
    <p>Large language models (LLMs) have garnered significant attention for their potential to enhance knowledge worker productivity. In this study, we provide the first large-scale empirical evaluations of LLMs’ impact on academic research productivity. Leveraging a comprehensive dataset of 4,582 computer science scholars across 194 top U.S. universities and analyzing 251,124 research papers published between 2018 and 2024, we find that the introduction of LLMs is associated with about 8% increase in publication output. Our regression discontinuity in time (RDiT) analysis further reveals that LLMs not only shifted the average publication level but also accelerated the growth rate of productivity, rising to 3.2% in 2023 and 12.8% in 2024. Notably, junior scholars realize stronger gains than their senior counterparts, suggesting that those with fewer years in academia benefit disproportionately from LLM adoption. Recognizing that LLMs’ benefits may not be uniformly distributed, we also investigate their impact on non-native English-speaking (NNES) researchers, who have historically faced disadvantages in academic writing (Liao et al., 2024). Difference-in-differences and generalized synthetic control analyses indicate that, following LLM adoption, native English-speaking (NES) researchers produced more papers than their NNES counterparts—a gap that persists across alternative measures, including the first-author publications and top-tier conference papers. Overall, our findings indicate that while LLMs significantly boost scholarly productivity, they also exhibit dual effects, lowering barriers for junior scholars while potentially reinforcing linguistic inequities.</p>
  </div>
</div>

<!-- Paper 5 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(2) Perception and Valuation of Human-AI Co-created Art: Computational Aesthetics Approach</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract5', this)">Abstract</button>
  </div>
  <ul>
    <li>with Alok Gupta</li>
    <li>Analysis in progress</li>
  </ul>

<div id="abstract5" class="abstract-box">
    <p>Abstract coming soon...</p>
  </div>
</div>

`Sharing Economy`

<!-- Paper 6 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(1) Friend or Foe? Bike-sharing and Ride-sharing in New York City</b> <i>(Master's Thesis)</i>
    <button class="abstract-button" onclick="toggleAbstract('abstract6', this)">Abstract</button>
  </div>
  <ul>
    <li><b>YoungJin Kwon</b>, Agnes Yang, Sang-Yong Tom Lee, and Seung Hyun Kim</li>
    <li>Presented at WISE 2019</li>
    <li>Best paper award at Post-ICIS KrAIS Research Workshop 2019</li>
  </ul>

<div id="abstract6" class="abstract-box">
    <p>App-based bike-sharing platforms are rapidly transforming urban transportation. This study investigates how bike-sharing platforms influence demand for ride-sharing services, with a focus on platform interaction. To measure this effect, we use spatiotemporally staggered expansions of Citi Bike, New York City’s largest bike-sharing service, as a natural experiment. We examine the treatment effects on ride-sharing services (Uber, Lyft) and Yellow taxi demand across the city. Our novel identification strategy, geographically nearest neighbor matching, is based on 0.38 billion individual trip records. This research contributes to the sharing economy literature in Information Systems (IS). To our knowledge, it is one of the first studies to explore interactions between app-based sharing platforms. Understanding how people connect different shared mobility services has never been more important. We argue that this study lays the foundation for future research on sharing-to-sharing mobility interactions.</p>
  </div>
</div>

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
    <b>(1) Why Did the NFT Market Crash? Antecedents and Consequences of Wash Trading</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract1', this)">Abstract</button>
  </div>
  <ul>
    <li>with Alok Gupta, Teng Ye</li>
    <li><span style="color: purple;">Job Market Paper</span></li>
    <li>Targeting <i>Management Science</i></li>
  </ul>

<div id="abstract1" class="abstract-box">
    <p>The non-fungible-token (NFT) market, long hailed for frictionless, gatekeeper-free trading, experienced a meteoric rise in 2021–2022 before collapsing abruptly in mid-2022. To identify the forces behind this crash, we analyze 15 million on-chain transactions from 867 leading NFT collections. We estimate that wash trading, a fraudulent self-trade behavior designed to fabricate demand, generated approximately US $33 billion, or 47% of recorded trade volume, and was conducted by just 4% of addresses. Our Local Projections with Instrumental Variables (LP-IV) estimations provide four key results. First, increases in wash-trade volume inflate performance metrics (trade count, trader count, capital inflow, and realized returns) during year 1, forming a speculative bubble. Second, the same activities are linked to significant declines across key performance metrics during year 2, crowding out genuine participation and eroding valuations. Third, these boom–bust dynamics are significantly dampened in collections characterized by a higher share of experienced traders, a larger proportion of long-horizon art collectors, and greater trader-network centrality, implying that informed or socially embedded participants buffer speculative shocks. Fourth, collection-level transaction fees and creator resale royalties deter the entry of wash traders, underscoring the importance of trading frictions while also benefiting creators. Taken together, our findings suggest three policy implications for NFT platforms and regulators: (i) implement real-time wash-trade detection in this largely unregulated market, (ii) disclose market-quality indicators, such as the art-collector ratio and network-centrality scores, to support informed investment decisions and enhance market resilience, and (iii) reconsider recent moves to revoke or make optional collection-level transaction fees and creator resale royalties, given their deterrent effect on wash trading.</p>
  </div>
</div>

<!-- Paper 2 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(2) From Boom to Bust and Beyond: Developing an NFT Market Index for a Longitudinal Analysis of NFT Collectors and Their Performance</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract2', this)">Abstract</button>
  </div>
  <ul>
    <li><b>YoungJin Kwon</b>, Teng Ye, and Alok Gupta</li>
    <li>Submitted to <i>Information Systems Research</i></li>
    <li>Presented at WISE 2024</li>
    <li>Presented at INFORMS ISR - ISS Paper Development Workshop 2024</li>
    <li>Presented at WITS 2023</li>
  </ul>

<div id="abstract2" class="abstract-box">
    <p>Information Systems researchers have led efforts to understand user behaviors in emerging digital markets that often diverge from traditional theories (Bapna et al. 2004). However, collector behavior in the rising Non-Fungible Token (NFT) markets remains largely unexplored due to a lack of analytical tools and challenges posed by their low-liquidity nature. We address this methodological gap by introducing two novel instruments: an NFT market index adapting the Case-Shiller repeat-sales framework, and a collector-level portfolio return metric considering both realized and unrealized gains. Using transaction data from 56,609 NFTs and 18,733 collectors over 5 years, we identify a complete boom-bust market cycle and uncover distinct collector groups by cluster analysis. We find that unlike traditional art or conventional investment markets, collectors of extremely high-priced NFTs (Masterpiece Collectors) underperform most others. Notably, long-term holders (Buy-and-Holders) outperform speculators chasing popular NFTs (Popularity Collectors). Collectors with extensive trading experience (Active Traders) succeed only if entering during pre-boom and boom but not bust periods. Mechanism analyses reveal that successful groups avoid extrapolating past returns and prioritize early participation in primary sales. This study contributes a novel methodological framework for NFT market analysis and provides actionable insights into boom-bust dynamics and NFT collector behaviors.</p>
  </div>
</div>

<!-- Paper 3 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(3) Tokenized Access: How NFT Market Empowers Minority Artists</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract3', this)">Abstract</button>
  </div>
  <ul>
    <li><b>YoungJin Kwon</b>, Agnes Yang, Gautam Ray</li>
    <li>Submitted to <i>MIS Quarterly</i></li>
    <li>Presented at WITS 2024</li>
    <li>Presented at CIST 2024</li>
    <li>Presented at INFORMS Annual Meeting 2024</li>
  </ul>

<div id="abstract3" class="abstract-box">
    <p>Blockchain-based Web3 has created a decentralized digital ecosystem that reduces reliance on traditional gatekeepers and intermediaries. This transformation raises a critical question: How does this new environment affect gender and racial minorities in the art market? To address this, we analyze approximately 27,000 sales and 90,000 offers/bids involving 40,000 NFTs created by 2,500 artists on SuperRare, a leading curated NFT art market, proposing a nuanced view of the NFT art market: (i) White male artists still dominate supply, but less than in traditional markets; (ii) non-White artists face larger disadvantages than female artists in both sale probability and price, relative to White male artists; and (iii) self-curation via verifiable quality signals materially mitigates these gaps, with minority artists benefiting disproportionately. Robustness checks exclude supply-side explanations (e.g., artist self-underpricing), pointing to demand-side factors. Despite lower entry barriers from disintermediation, structural inequities endure; however, self-curation enables minority artists to mitigate demand-side disadvantages.</p>
  </div>
</div>

`GenAI Creativity and Productivity`

<!-- Paper 4 -->
<div class="paper-container">
  <div class="paper-title-line">
    <b>(1) Large Language Models in Academia: Boosting Productivity but Reinforcing Inequality</b>
    <button class="abstract-button" onclick="toggleAbstract('abstract4', this)">Abstract</button>
  </div>
  <ul>
    <li><b>YoungJin Kwon</b>, Agnes Yang</li>
    <li>To be presented at ICIS 2025</li>
    <li>To be presented at INFORMS Annual Meeting 2025</li>
    <li>Presented at Wharton Annual Business & Generative AI Conference 2025</li>

  </ul>

<div id="abstract4" class="abstract-box">
    <p>Large language models (LLMs) have attracted significant attention for their potential to enhance knowledge worker productivity. In this study, we provide the first large-scale empirical evaluations of LLMs’ impact on academic research productivity. Leveraging a comprehensive dataset of 4,582 computer science scholars across 194 top U.S. universities and analyzing 218,723 research papers published between 2019 and 2024, we find that the introduction of LLMs is associated with about 8% increase in publication output; a gap that persists across alternative measures, including the first-author publications and top-tier conference papers. Our regression discontinuity in time (RDiT) analysis further reveals that LLMs not only shifted the average publication level but also accelerated the growth rate of productivity, rising to 3.2% in 2023 and 12.8% in 2024. Notably, junior scholars realize stronger gains than their senior counterparts, with the productivity benefit diminishing by roughly 1% for each additional year of experience. Recognizing that LLMs’ benefits may not be uniformly distributed, we also investigate their impact on non-native English-speaking (NNES) researchers, who have historically faced disadvantages in academic writing (Liao et al., 2024). Difference-in-differences and generalized synthetic control analyses indicate that, following LLM adoption, native English-speaking (NES) researchers produced more papers than their NNES counterparts. Overall, our findings indicate that while LLMs significantly boost scholarly productivity, they also exhibit dual effects, lowering barriers for junior scholars while potentially reinforcing linguistic inequities.</p>
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
    <p>App-based bike-sharing platforms are rapidly transforming urban transportation. This study investigates how bike-sharing platforms influence demand for ride-sharing services, with a focus on platform interaction. To measure this effect, we use spatiotemporally staggered expansions of Citi Bike, New York City’s largest bike-sharing service, as a natural experiment. We examine the treatment effects on ride-sharing services (Uber, Lyft) and Yellow taxi demand across the city. Our novel identification strategy, geographically nearest neighbor matching, is based on 0.38 billion individual trip records. The results reveal a complementary relationship between bike‑sharing and ride‑hailing (Citi Bike stations stimulate nearby ride‑hailing trips) while simultaneously depressing Yellow Taxi demand, pointing to a substitution between ride‑hailing and taxis. This research contributes to the sharing economy literature in Information Systems (IS). To our knowledge, it is one of the first studies to explore interactions between app-based sharing platforms. Understanding how people connect different shared mobility services has never been more important. We argue that this study lays the foundation for future research on sharing-to-sharing mobility interactions.</p>
  </div>
</div>

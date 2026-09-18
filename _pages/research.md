---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
profile_page: true
profile_story: true
page_eyebrow: "Arctic hydrology · Analysis & attribution"
page_description: "Understanding Alaska’s water-balance response to a warming climate."
redirect_from: 
  - /research
---

<nav class="research-chapters" aria-label="Research chapters">
  <a href="#overview">Overview</a><a href="#data">The data</a><a href="#attribution">Attribution</a><a href="#projects">More projects</a>
</nav>

<section class="research-opening" id="overview">
  <p class="story-eyebrow">Alaska · Arctic hydrology</p>
  <h1>Where does<br>Alaska’s water go?</h1>
  <p class="story-lead">A changing climate. A changing water balance.<br>I study how much precipitation becomes runoff—and why that fraction changes.</p>
  <figure class="water-landscape">
    <img src="{{ '/images/water-balance-concept.svg' | relative_url }}" width="1000" height="460" alt="Conceptual landscape showing precipitation entering a basin, evaporation returning water to the atmosphere, runoff leaving the basin, and terrestrial water storage" fetchpriority="high">
    <figcaption>Conceptual water-balance illustration. Not simulation output.</figcaption>
  </figure>
</section>

<section class="ratio-story story-chapter">
  <div class="ratio-story__symbol" aria-label="Runoff divided by precipitation"><span>R</span><span class="ratio-story__rule"></span><span>P</span></div>
  <div>
    <p class="story-eyebrow">01 / The question</p>
    <h2>One ratio.<br>A view of the water balance.</h2>
    <p><strong>R/P is the fraction of precipitation that becomes runoff.</strong> I examine how it varies across Alaska’s climate regions, how it may change under mid-century warming, and which processes contribute to those changes.</p>
    <details class="story-details">
      <summary>About this research</summary>
      <div><p><strong>Historical and projected changes in Alaska’s runoff-to-precipitation ratio.</strong> Research at the University at Buffalo’s A.C.T. Hydrology Lab, advised by <a href="https://arts-sciences.buffalo.edu/earth-sciences/faculty-staff/faculty/cheng-yifan.html">Dr. Yifan Cheng</a>.</p></div>
    </details>
  </div>
</section>

<section class="data-story story-chapter" id="data">
  <header>
    <p class="story-eyebrow">02 / The data</p>
    <h2>Regional questions.<br><span>High-resolution data.</span></h2>
    <p>I analyze existing RASM simulation data to examine historical patterns and projected changes across Alaska.</p>
  </header>
  <div class="data-story__stage">
    <div class="data-story__resolution"><strong>4<span> km</span></strong><p>Spatial resolution<br>of the RASM dataset</p></div>
    <figure><img src="{{ '/images/alaska-study-region.svg' | relative_url }}" alt="Alaska study region" width="520" height="440" loading="lazy"><figcaption>Geographic context · Alaska</figcaption></figure>
  </div>
  <div class="data-story__comparison">
    <div><span>Historical patterns</span><h3>Understand the baseline.</h3><p>Examine how R/P varies across Alaska’s diverse climate regions.</p></div>
    <div><span>Projected change</span><h3>Explore a warmer climate.</h3><p>Compare historical conditions with mid-century warming scenarios.</p></div>
  </div>
  <details class="story-details" id="rasm-framework">
    <summary>Inside the RASM framework</summary>
    <div>
      <p>The RASM configuration used to produce the dataset couples the <strong>WRF 3 atmosphere</strong> and <strong>CTSM land model</strong> through <strong>CPL 7</strong>. Sea-surface temperature and sea ice are prescribed from ERA5; streamflow is computed offline with MizuRoute.</p>
      <figure class="rasm-framework-figure">
        <a href="{{ '/images/rasm-framework.svg' | relative_url }}" aria-label="Open full-size RASM framework diagram"><img src="{{ '/images/rasm-framework.svg' | relative_url }}" alt="RASM framework: WRF 3 atmosphere and CTSM land exchange fluxes through CPL 7. Prescribed ERA5 sea-surface temperature and sea ice feed the coupler. CTSM supplies offline MizuRoute streamflow routing." width="900" height="760" loading="lazy"></a>
        <figcaption>RASM model components and flux connections, redrawn from the supplied framework. <a href="{{ '/images/rasm-framework.svg' | relative_url }}">View SVG ↗</a> · <a href="{{ '/images/rasm-framework.png' | relative_url }}">Original diagram</a></figcaption>
      </figure>
      <p>This is the model framework behind the data. My work analyzes its outputs using the Budyko-based attribution framework described below.</p>
    </div>
  </details>
  <details class="story-details">
    <summary>Dataset, scenarios &amp; analysis tools</summary>
    <div><dl><dt>Dataset</dt><dd>4-km RASM coupled land–atmosphere simulation data.</dd><dt>Scenarios</dt><dd>Historical conditions, PGW and DDD scenarios.</dd><dt>My contribution</dt><dd>Geospatial analysis and water-energy balance attribution of R/P changes.</dd><dt>Tools</dt><dd>Python and a Budyko-based attribution framework.</dd></dl></div>
  </details>
</section>

<section class="attribution-story story-chapter" id="attribution">
  <p class="story-eyebrow">03 / The explanation</p>
  <h2>See the change.<br><span>Investigate the drivers.</span></h2>
  <p class="story-lead">A change in runoff is the starting point. I use a Budyko-based water-energy balance framework to separate the contributions of four controlling factors.</p>
  <div class="driver-spectrum">
    <div><span aria-hidden="true">P</span><h3>Water supply</h3><p>Precipitation entering the system.</p></div>
    <div><span aria-hidden="true">PET</span><h3>Evaporative demand</h3><p>The atmosphere’s potential demand for water.</p></div>
    <div><span aria-hidden="true">ΔS</span><h3>Water storage</h3><p>Changes in terrestrial water storage.</p></div>
    <div><span aria-hidden="true">n</span><h3>Basin characteristics</h3><p>Effective basin properties represented in the framework.</p></div>
  </div>
  <details class="story-details">
    <summary>How the attribution fits together</summary>
    <div><p>The analysis uses a Budyko-based framework to attribute changes in R/P to precipitation supply, evaporative demand, terrestrial water storage, and effective basin characteristics. These contributions provide a framework-based interpretation of the regional hydrologic response.</p></div>
  </details>
</section>

<section class="projects-story story-chapter" id="projects">
  <header><p class="story-eyebrow">04 / Related experience</p><h2>Different landscapes.<br>Connected questions.</h2><p>Previous projects explore sea ice, coastal ecosystems, and river runoff.</p></header>
<div class="research-project">
  <a href="/images/Poster_Junhao.png" aria-label="Open full-size sea-ice research poster"><img src="/images/Poster_Junhao.png" alt="Research poster about sea-ice season and ecosystem response" width="4992" height="3840" loading="lazy"></a>
  <div class="research-project__content">
    <p class="profile-card__eyebrow">MITACS Globalink Research Internship · 2024</p>
    <h3>Climate impacts on sea-ice season and ecosystem response</h3>
    <p class="research-project__supervisor"><strong>Supervisor:</strong> Prof. Paul Myers, University of Alberta</p>
    <details class="story-details"><summary>Explore the methods</summary><div>    <ul>
      <li>Analyzed changes in sea-ice concentration, thickness, and spatial structure in Baffin Bay, the Labrador Sea, and Hudson Bay.</li>
      <li>Evaluated ice-free-season changes through breakup and freeze-up timing.</li>
      <li>Examined relationships between sea-ice change and biogeochemical patterns.</li>
    </ul></div></details>
  </div>
</div>

<div class="research-project">
  <a href="/images/coast.png" aria-label="Open full-size coastal analysis figure"><img src="/images/coast.png" alt="Maps of coastal land-use and habitat-quality analysis" width="2757" height="2524" loading="lazy"></a>
  <div class="research-project__content">
    <p class="profile-card__eyebrow">NUIST · 2023–2024</p>
    <h3>Land-use change and habitat quality in China’s coastal zone</h3>
    <p class="research-project__supervisor"><strong>Supervisor:</strong> Prof. Chengyi Zhao</p>
    <details class="story-details"><summary>Explore the methods</summary><div>    <ul>
      <li>Coupled PLUS and InVEST to project land-use patterns and assess habitat quality from 2020 to 2060 under three SSP scenarios.</li>
      <li>Evaluated drivers of habitat-quality change and the contribution of land-cover transitions to ecosystem degradation.</li>
    </ul></div></details>
  </div>
</div>

<div class="research-project">
  <a href="/images/cuntan.png" aria-label="Open full-size Yangtze runoff figure"><img src="/images/cuntan.png" alt="Runoff analysis for the upper Yangtze River basin" width="2266" height="1418" loading="lazy"></a>
  <div class="research-project__content">
    <p class="profile-card__eyebrow">NUIST · 2022–2024</p>
    <h3>Anthropogenic climate-change impacts on upper Yangtze runoff</h3>
    <p class="research-project__supervisor"><strong>Supervisor:</strong> Prof. Buda Su</p>
    <details class="story-details"><summary>Explore the methods</summary><div>    <ul>
      <li>Developed a random-forest model using temperature and precipitation to estimate runoff under different forcing scenarios.</li>
      <li>Compared anthropogenic-plus-natural and natural-only forcing to assess changes in annual, monthly, and extreme discharge.</li>
    </ul></div></details>
  </div>
</div>

</section>

<footer class="research-next"><p>Continue exploring</p><a href="{{ '/publications/' | relative_url }}">Read the publications <span aria-hidden="true">→</span></a><a href="{{ '/cv/' | relative_url }}">View my CV <span aria-hidden="true">→</span></a></footer>

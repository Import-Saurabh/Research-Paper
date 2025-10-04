<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="description" content="A simple explanation of how global trade chokepoints like the Suez Canal and Strait of Hormuz affect oil prices and stock markets — especially in India. Research by Saurabh Hadole.">
  <title>Trade Shocks and Market Shifts — README</title>
  <style>
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial; line-height:1.6; color:#111; margin:20px; max-width:900px; }
    header { border-bottom: 3px solid #eee; padding-bottom:12px; margin-bottom:18px; }
    h1 { margin:0; font-size:28px; }
    h2 { color:#222; margin-top:24px; }
    p { margin:10px 0; }
    .grid { display:grid; grid-template-columns:repeat(2, 1fr); gap:12px; margin-top:12px; }
    .img-card { border:1px solid #e8e8e8; padding:8px; background:#fafafa; text-align:center; border-radius:8px; }
    .img-card img { max-width:100%; height:180px; object-fit:cover; background:#ddd; border-radius:6px; }
    .caption { font-size:13px; color:#555; margin-top:6px; }
    code { background:#f4f4f4; padding:2px 6px; border-radius:4px; }
    footer { margin-top:28px; border-top:1px solid #eee; padding-top:12px; color:#666; font-size:14px; }
    .note { background:#fffbe6; border-left:4px solid #ffd666; padding:10px; margin:12px 0; }
    .center { text-align:center; }
    @media (max-width:600px) {
      .grid { grid-template-columns:1fr; }
    }
  </style>
</head>

<body>

<header>
  <h1>Trade Shocks and Market Shifts</h1>
  <p><strong>Simple summary (for everyone):</strong> This project studies how problems in key global sea routes — like the Suez Canal, Panama Canal, and Strait of Hormuz — can make oil prices jump and affect stock markets, especially India’s Nifty sectors.</p>
  <p><strong>Author:</strong> Saurabh Hadole &nbsp; | &nbsp; <strong>Year:</strong> 2025</p>
</header>

<main>

<section>
  <h2>What is this paper about? (Simple)</h2>
  <p>Think of the world’s trade routes as highways on the ocean. Most ships follow a few narrow passages. When one of those gets blocked — by war, an accident, or a political crisis — it’s like a global traffic jam. Oil and goods get delayed, prices rise, and stock markets react. This paper studies those moments and asks: <em>how big are the price shocks, which industries are most affected, and how quickly does the economy recover?</em></p>
  <p>This research also includes <strong>geopolitical shocks</strong> like the <em>2021 Suez blockage</em>, <em>2022 Russia–Ukraine war</em>, <em>2023 Red Sea tensions</em>, and <em>2025 Israel–Iran conflict</em>, which disrupted major chokepoints.</p>
</section>

<section>
  <h2>Key Sea Routes (Global Chokepoints)</h2>
  <p>Below are the most critical global trade passages we studied. You can attach your maps or satellite images by replacing the image paths.</p>

  <div class="grid">
    <div class="img-card">
      <img src="Images/suez_canal.jpg" alt="Suez Canal map">
      <div class="caption"><strong>Suez Canal</strong><br>Connects Europe and Asia by linking the Mediterranean Sea to the Red Sea. A blockage here delays 12% of world trade.</div>
    </div>

    <div class="img-card">
      <img src="Images/panama_canal.jpg" alt="Panama Canal map">
      <div class="caption"><strong>Panama Canal</strong><br>Links the Atlantic and Pacific Oceans — essential for global container trade and U.S.–Asia routes.</div>
    </div>

    <div class="img-card">
      <img src="Images/strait_of_hormuz.jpg" alt="Strait of Hormuz map">
      <div class="caption"><strong>Strait of Hormuz</strong><br>The world’s most important oil chokepoint — around 20% of global oil passes through here daily.</div>
    </div>

    <div class="img-card">
      <img src="Images/strait_of_malacca.jpg" alt="Strait of Malacca map">
      <div class="caption"><strong>Strait of Malacca</strong><br>Vital route between the Indian Ocean and the South China Sea — key for energy shipments to East Asia.</div>
    </div>

    <div class="img-card">
      <img src="Images/bab_el_mandeb.jpg" alt="Bab el-Mandeb map">
      <div class="caption"><strong>Bab el-Mandeb</strong><br>Connects the Red Sea to the Gulf of Aden. When threatened, ships must reroute around Africa.</div>
    </div>

    <div class="img-card">
      <img src="Images/cape_of_good_hope.jpg" alt="Cape of Good Hope map">
      <div class="caption"><strong>Cape of Good Hope (Alternate Route)</strong><br>Used when the Suez route is blocked. It adds thousands of kilometers, raising costs and delivery times.</div>
    </div>
  </div>
</section>

<section>
  <h2>Why the Cape of Good Hope Matters</h2>
  <p>If the Suez Canal or Bab el-Mandeb is blocked, ships detour around southern Africa — the Cape of Good Hope. This longer route increases travel time and fuel cost, causing shipping rates and oil prices to rise. It’s included in this research as a fallback trade path.</p>
</section>

<section>
  <h2>What Has Been Done So Far (from Research Notebook)</h2>
  <ul>
    <li><strong>Data collected:</strong> Global oil prices (Brent &amp; WTI), Indian market sector indices (Nifty sectors), and event timelines.</li>
    <li><strong>Event timeline built:</strong> Includes major disruptions like the Suez blockage, COVID-19 lockdowns, Russia–Ukraine war, and Israel–Iran tensions.</li>
    <li><strong>Data cleaning:</strong> Standardized oil and market datasets into comparable daily formats.</li>
    <li><strong>Exploratory analysis:</strong> Visualized how oil and sector indices moved before, during, and after each event.</li>
    <li><strong>Impact measurement:</strong> Quantified short-term oil spikes and Nifty sector declines after chokepoint crises.</li>
    <li><strong>Resilience testing:</strong> Checked how quickly sectors (Energy, Auto, Pharma, Banks, IT) recovered post-shock.</li>
  </ul>

  <div class="note">
    <strong>Summary of findings:</strong> When a chokepoint is blocked or threatened, oil prices rise sharply. Energy and transport sectors are hit hardest. Healthcare and essential goods sectors remain relatively stable and recover faster.
  </div>
</section>

<section>
  <h2>How the Analysis Works (Step-by-Step)</h2>
  <ol>
    <li><strong>Identify events:</strong> Pinpoint exact dates of global trade disruptions.</li>
    <li><strong>Compare data:</strong> Check oil and stock index behavior before, during, and after each event.</li>
    <li><strong>Measure reactions:</strong> Calculate percentage changes and time to recovery.</li>
    <li><strong>Repeat:</strong> Apply the same process across all chokepoints and crises to find patterns.</li>
  </ol>
</section>

<section>
  <h2>Why This Matters</h2>
  <p>Modern economies rely on these maritime chokepoints. When they’re blocked, energy costs, inflation, and market volatility rise. Understanding this helps policymakers, investors, and companies plan better — such as building fuel reserves, diversifying trade routes, or investing in resilient sectors.</p>
</section>

<section>
  <h2>How to Add Your Images</h2>
  <p>To attach your images, replace the sample file paths like:</p>
  <pre><code>&lt;img src="Images/suez_canal.jpg" alt="Suez Canal map"&gt;</code></pre>
  <p>Store them in an <code>Images/</code> folder next to this README file so GitHub can load them easily.</p>
</section>

</main>

<footer>
  <p class="center"><strong>Contact / Author:</strong> Saurabh Hadole — Independent Researcher</p>
  <p class="center">For dataset or visualization requests, reach out via your academic or research portfolio.</p>
</footer>

</body>
</html>

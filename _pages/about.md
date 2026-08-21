---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Computer Science Ph.D. candidate at the National University of Singapore, advised by Prof. [Bingsheng He](https://www.comp.nus.edu.sg/~hebs/). I work on **LLM for Finance**: teaching LLMs to read financial text and turn it into investment decisions, along three threads —

- **Financial benchmarks & data.** Building the datasets this field is missing, e.g., [**CrossAlpha**](https://arxiv.org/abs/2605.29286) (EMNLP 2026 Findings), an annual-report benchmark testing whether disclosures in one market predict stock returns in another.
- **LLM trading agents.** Agents that reason over market information to make trading decisions, e.g., [**CryptoTrade**](https://aclanthology.org/2024.emnlp-main.63.pdf) (EMNLP 2024) and [FS-ReasoningAgent](https://arxiv.org/abs/2410.12464) (ICLR 2025 Financial AI Workshop).
- **Trustworthy LLM judgment.** Financial decisions need unbiased judges — I characterize LLM judging bias empirically ([COLM 2025](https://arxiv.org/abs/2504.09946)) and mitigate it via reinforcement learning ([Treat Bias as Noise](https://arxiv.org/abs/2602.01528)).

Before this, I worked broadly on LLM multi-agent systems ([**MegaAgent**](https://arxiv.org/abs/2408.09955), ACL 2025 Findings — a 590-agent fully autonomous system) and graph datasets ([EX-Graph](https://openreview.net/forum?id=juE0rWGCJW), ICLR 2024). My work has appeared at **ICLR, NeurIPS, ICML, ACL, EMNLP, COLM, and LOG**, with several <span class="news-hot">Oral</span> presentations and an **Outstanding Reviewer Award** (EACL 2026).

<span style="color:#800020;font-weight:600;">I am always open to collaborations</span> — and happy to chat about research, PhD applications, or life choices. Email me at persdre@gmail.com!

# 📰 News

- *2026.08* — 🎉 **CrossAlpha: An Annual-Report Benchmark for Cross-Market Factor Research** was accepted to **EMNLP 2026 Findings**. Hope to see you all in Budapest!
- *2026.05* — 📈 New preprint **CrossAlpha**: an annual-report benchmark for cross-market factor research, covering ~3,600 firms across 5 markets with ~19M firm-pair scores. [arXiv](https://arxiv.org/abs/2605.29286)
- *2026.05* — 🎉 **4 papers** accepted to the **ICML 2026** Agents-in-the-Wild Workshop. Looking forward to meeting you in Seoul!
- *2026.05* — 🏆 Received the <span class="news-hot">Outstanding Reviewer Award</span> from **EACL 2026**.
- *2026.05* — 🎯 **Treat Bias as Noise** (bias-robust LLM reasoning via reinforcement learning, with collaborators from UC Berkeley) was accepted to the **ICML 2026** AI4GOOD Workshop. [arXiv](https://arxiv.org/abs/2602.01528)
- *2026.04* — 🎉 **3 papers** accepted to **ACL 2026** (incl. Findings).
- *2026.01* — 🎉 **LLM DNA: Tracing Model Evolution via Functional Representations** was accepted to **ICLR 2026** as an <span class="news-hot">Oral</span> presentation.
- *2025.10* — 1 paper accepted to **LOG 2025** as an <span class="news-hot">Oral</span> presentation.
- *2025.09* — 🛡️ **Towards Evaluating Fake Reasoning Bias in Language Models** was accepted to the **NeurIPS 2025** Lock-LLM Workshop.
- *2025.07* — Our paper *Assessing Judging Bias in Large Reasoning Models: An Empirical Study* was accepted to **COLM 2025**.
- *2025.06* — 🤝 **Multiple papers** accepted to **ICML 2025** workshops (incl. the Multi-Agent Systems Workshop), covering multi-agent systems and LLMs for finance.
- *2025.05* — Our paper *MegaAgent: A Large-Scale Autonomous LLM-based Multi-Agent System Without Predefined SOPs* was accepted to **ACL 2025** Findings.

# 📝 Selected Publications

Click a topic to filter; my name is shown in **bold**. The complete list is on my <span class="pub-links"><a href="https://scholar.google.com/citations?user=KAGrBdoAAAAJ">Google Scholar</a></span>

<div class="pub-filter">
  <button class="active" data-filter="all">All</button>
  <button data-filter="mas">🤖 Multi-Agent Systems</button>
  <button data-filter="trust">🛡️ Trustworthy AI</button>
  <button data-filter="rl">🎯 Reinforcement Learning</button>
  <button data-filter="fma">🔬 Foundation Model Analysis</button>
  <button data-filter="mem">🧠 Agent Memory</button>
  <button data-filter="fin">📈 LLM for Finance</button>
  <button data-filter="graph">🕸️ Graph Learning</button>
  <button data-filter="sim">👥 Human Simulation</button>
</div>

<div id="pub-list">

<div class="pub-card has-thumb" data-topic="mas">
  <img class="pub-thumb" src="/images/papers/megaagent.png" alt="" loading="lazy">
  <div class="pub-body">
    <span class="badge-venue">ACL 2025 Findings</span> <span class="badge-honor">ICLR 2025 FM-Wild Workshop Oral</span>
    <span class="pub-title">MegaAgent: A Large-Scale Autonomous LLM-based Multi-Agent System Without Predefined SOPs</span>
    <span class="pub-tldr">An autonomous multi-agent framework that decomposes tasks, spawns agents on the fly, and coordinates up to 590 of them — no predefined SOPs.</span>
    <span class="pub-links"><a href="https://arxiv.org/abs/2408.09955">Paper</a> <a href="https://github.com/Xtra-Computing/MegaAgent">Code</a></span>
    <span class="pub-authors"><span class="me">Qian Wang</span>, T. Wang, Z. Tang, Q. Li, N. Chen, J. Liang, B. He</span>
  </div>
</div>

<div class="pub-card" data-topic="mas">
  <span class="badge-venue">ICML 2025 Multi-Agent Systems Workshop</span>
  <span class="pub-title">AgentTaxo: Dissecting and Benchmarking Token Distribution of LLM Multi-Agent Systems</span>
  <span class="pub-tldr">Dissects where tokens actually go inside LLM multi-agent systems and benchmarks their token efficiency.</span>
  <span class="pub-links"><a href="https://openreview.net/forum?id=0iLbiYYIpC">Paper</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Tang, N. Chen, T. Wang, B. He</span>
</div>

<div class="pub-card" data-topic="mas">
  <span class="badge-venue">ACL 2026 Findings</span>
  <span class="pub-title">Diversity Collapse in Multi-Agent LLM Systems: Structural Coupling and Collective Failure in Open-Ended Idea Generation</span>
  <span class="pub-tldr">Shows how tightly-coupled multi-agent LLM discussion collapses open-ended idea generation into the same few ideas.</span>
  <span class="pub-authors">N. Chen, Y. Tong, Y. Yang, X. Zhang, <span class="me">Qian Wang</span>, B. He</span>
</div>

<div class="pub-card has-thumb" data-topic="trust">
  <img class="pub-thumb" src="/images/papers/judging-bias.png" alt="" loading="lazy">
  <div class="pub-body">
    <span class="badge-venue">COLM 2025</span>
    <span class="pub-title">Assessing Judging Bias in Large Reasoning Models: An Empirical Study</span>
    <span class="pub-tldr">An empirical audit of large reasoning models as judges, uncovering systematic bandwagon, authority, and position biases.</span>
    <span class="pub-links"><a href="https://arxiv.org/abs/2504.09946">Paper</a></span>
    <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Lou, Z. Tang, N. Chen, X. Zhao, W. Zhang, D. Song, B. He</span>
  </div>
</div>

<div class="pub-card has-thumb" data-topic="trust">
  <img class="pub-thumb" src="/images/papers/fake-reasoning-bias.png" alt="" loading="lazy">
  <div class="pub-body">
    <span class="badge-venue">NeurIPS 2025 Lock-LLM Workshop</span>
    <span class="pub-title">Towards Evaluating Fake Reasoning Bias in Language Models</span>
    <span class="pub-tldr">Shows LLM judges reward text that merely looks like reasoning, and builds a benchmark to measure this bias.</span>
    <span class="pub-links"><a href="https://arxiv.org/abs/2507.13758">Paper</a></span>
    <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Tang, Z. Lou, N. Chen, W. Wang, B. He</span>
  </div>
</div>

<div class="pub-card" data-topic="trust">
  <span class="badge-venue">Preprint 2025</span>
  <span class="pub-title">JudgeLRM: Large Reasoning Models as a Judge</span>
  <span class="pub-tldr">Trains large reasoning models into better judges with judgment-oriented reinforcement learning.</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2504.00050">Paper</a></span>
  <span class="pub-authors">N. Chen, Z. Hu, Q. Zou, J. Wu, <span class="me">Qian Wang</span>, B. Hooi, B. He</span>
</div>

<div class="pub-card has-thumb" data-topic="rl">
  <img class="pub-thumb" src="/images/papers/treat-bias-as-noise.png" alt="" loading="lazy">
  <div class="pub-body">
    <span class="badge-venue">ICML 2026 AI4GOOD Workshop</span>
    <span class="pub-title">Treat Bias as Noise: Training Bias-Robust LLM Reasoning via Reinforcement Learning</span>
    <span class="pub-tldr">RL training that treats biased cues as noise, yielding LLM reasoning that stays robust on biased prompts.</span>
    <span class="pub-links"><a href="https://arxiv.org/abs/2602.01528">Paper</a></span>
    <span class="pub-authors"><span class="me">Qian Wang</span>, X. Zhao, Z. Zhang, Z. Lou, N. Chen, D. Song, B. He</span>
  </div>
</div>

<div class="pub-card" data-topic="rl">
  <span class="badge-venue">Preprint 2026</span>
  <span class="pub-title">Learning to Learn-at-Test-Time: Language Agents with Learnable Adaptation Policies</span>
  <span class="pub-tldr">Language agents with learnable policies that decide how to adapt themselves at test time.</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2604.00830">Paper</a></span>
  <span class="pub-authors">Z. Lou, H. Chen, Y. Li, <span class="me">Qian Wang</span>, B. Hooi</span>
</div>

<div class="pub-card" data-topic="rl">
  <span class="badge-venue">Preprint 2026</span>
  <span class="pub-title">RL-RIG: A Generative Spatial Reasoner via Intrinsic Reflection</span>
  <span class="pub-tldr">A generative spatial reasoner that learns to reflect on its own intermediate steps via reinforcement learning.</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2602.19974">Paper</a></span>
  <span class="pub-authors">T. Wang, Z. Ma, <span class="me">Qian Wang</span>, X. Zhang, X. Long, B. Zhou</span>
</div>

<div class="pub-card has-thumb" data-topic="fma">
  <img class="pub-thumb" src="/images/papers/llm-dna.png" alt="" loading="lazy">
  <div class="pub-body">
    <span class="badge-venue">ICLR 2026</span> <span class="badge-honor">Oral</span>
    <span class="pub-title">LLM DNA: Tracing Model Evolution via Functional Representations</span>
    <span class="pub-tldr">Gives every LLM a functional 'DNA' embedding, making model lineage and evolution traceable across families.</span>
    <span class="pub-links"><a href="https://arxiv.org/abs/2509.24496">Paper</a></span>
    <span class="pub-authors">Z. Wu, H. Zhao, Z. Wang, J. Guo, <span class="me">Qian Wang</span>, B. He</span>
  </div>
</div>

<div class="pub-card" data-topic="mem">
  <span class="badge-venue">Preprint 2026</span>
  <span class="pub-title">LLM Agent Memory: A Survey from a Unified Representation–Management Perspective</span>
  <span class="pub-tldr">A survey unifying LLM agent memory research under one representation–management framework.</span>
  <span class="pub-links"><a href="https://openreview.net/forum?id=KPs1EgGKcT">Paper</a></span>
  <span class="pub-authors">Z. Tang, X. He, T. Zhao, F. Wei, X. Liu, P. Dong, <span class="me">Qian Wang</span>, et al.</span>
</div>

<div class="pub-card" data-topic="mem">
  <span class="badge-venue">ICML 2026 Agents-in-the-Wild Workshop</span>
  <span class="pub-title">Parameters as Agentic Memory: Internalizing Long-Horizon Memories for Efficient LLM Agents</span>
  <span class="pub-tldr">Internalizes an agent's long-horizon memory into model parameters instead of ever-growing context.</span>
  <span class="pub-authors">Z. Tang, F. Wei, P. Dong, X. Liu, <span class="me">Qian Wang</span>, X. Chu, B. Li</span>
</div>

<div class="pub-card has-thumb" data-topic="fin">
  <img class="pub-thumb" src="/images/papers/crossalpha.png" alt="" loading="lazy">
  <div class="pub-body">
    <span class="badge-venue">EMNLP 2026 Findings</span>
    <span class="pub-title">CrossAlpha: An Annual-Report Benchmark for Cross-Market Factor Research</span>
    <span class="pub-tldr">A public annual-report benchmark testing whether firm disclosures in one market predict stock returns in another.</span>
    <span class="pub-links"><a href="https://arxiv.org/abs/2605.29286">Paper</a></span>
    <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Tong, N. Chen, Z. Wu, B. He</span>
  </div>
</div>

<div class="pub-card has-thumb" data-topic="fin">
  <img class="pub-thumb" src="/images/papers/fs-reasoningagent.png" alt="" loading="lazy">
  <div class="pub-body">
    <span class="badge-venue">ICLR 2025 Financial AI Workshop</span>
    <span class="pub-title">Exploring LLM Cryptocurrency Trading Through Fact-Subjectivity Aware Reasoning</span>
    <span class="pub-tldr">Splits crypto-trading reasoning into factual and subjective paths, improving LLM trading decisions.</span>
    <span class="pub-links"><a href="https://arxiv.org/abs/2410.12464">Paper</a> <a href="https://github.com/Persdre/FS-ReasoningAgent">Code</a></span>
    <span class="pub-authors"><span class="me">Qian Wang</span>, Y. Gao, Z. Tang, B. Luo, N. Chen, B. He</span>
  </div>
</div>

<div class="pub-card has-thumb" data-topic="fin">
  <img class="pub-thumb" src="/images/papers/cryptotrade.png" alt="" loading="lazy">
  <div class="pub-body">
    <span class="badge-venue">EMNLP 2024</span>
    <span class="pub-title">CryptoTrade: A Reflective LLM-based Agent to Guide Zero-shot Cryptocurrency Trading</span>
    <span class="pub-tldr">A reflective LLM agent that fuses on-chain and off-chain signals for zero-shot cryptocurrency trading.</span>
    <span class="pub-links"><a href="https://aclanthology.org/2024.emnlp-main.63.pdf">Paper</a> <a href="https://github.com/Xtra-Computing/CryptoTrade">Code</a></span>
    <span class="pub-authors">Y. Li, B. Luo, <span class="me">Qian Wang</span>, N. Chen, X. Liu, B. He</span>
  </div>
</div>

<div class="pub-card has-thumb" data-topic="graph">
  <img class="pub-thumb" src="/images/papers/ex-graph.png" alt="" loading="lazy">
  <div class="pub-body">
    <span class="badge-venue">ICLR 2024</span>
    <span class="pub-title">EX-Graph: A Pioneering Dataset Bridging Ethereum and X</span>
    <span class="pub-tldr">The first public dataset linking Ethereum transaction wallets with X (Twitter) accounts.</span>
    <span class="pub-links"><a href="https://openreview.net/forum?id=juE0rWGCJW">Paper</a> <a href="https://github.com/Persdre/EX-Graph">Code</a></span>
    <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Zhang, Z. Liu, S. Lu, B. Luo, B. He</span>
  </div>
</div>

<div class="pub-card" data-topic="graph">
  <span class="badge-venue">LOG 2025</span> <span class="badge-honor">Oral</span>
  <span class="pub-title">Less is More: Using Buffer Nodes to Reduce Excessive Majority Node Influence in Class Imbalance Graphs</span>
  <span class="pub-tldr">Inserts buffer nodes into graphs to damp excessive majority-class influence in imbalanced node classification.</span>
  <span class="pub-links"><a href="https://openreview.net/forum?id=6ikB5L1kzq">Paper</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Liu, Z. Zhang, B. Luo, B. He</span>
</div>

<div class="pub-card" data-topic="graph">
  <span class="badge-venue">NeurIPS 2024 Datasets & Benchmarks</span>
  <span class="pub-title">Multi-Chain Graphs of Graphs: A New Approach to Analyzing Blockchain Datasets</span>
  <span class="pub-tldr">A graphs-of-graphs dataset spanning multiple blockchains, enabling cross-chain analysis.</span>
  <span class="pub-links"><a href="https://openreview.net/forum?id=mlbVgVKwD7">Paper</a></span>
  <span class="pub-authors">B. Luo, Z. Zhang, <span class="me">Qian Wang</span>, B. He</span>
</div>

<div class="pub-card" data-topic="graph">
  <span class="badge-venue">IEEE TKDE 2025</span>
  <span class="pub-title">A Survey of Imbalanced Learning on Graphs: Problems, Techniques, and Future Directions</span>
  <span class="pub-tldr">A systematic survey of imbalanced learning on graphs: problems, techniques, and future directions.</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2308.13821">Paper</a></span>
  <span class="pub-authors">Z. Liu, Y. Li, N. Chen, <span class="me">Qian Wang</span>, B. Hooi, B. He</span>
</div>

<div class="pub-card" data-topic="sim">
  <span class="badge-venue">Preprint 2025</span>
  <span class="pub-title">LLM-based Human Simulations Have Not Yet Been Reliable</span>
  <span class="pub-tldr">Argues LLM-based human simulations are not yet reliable, and maps out where and why they fail.</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2501.08579">Paper</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, J. Wu, Z. Tang, B. Luo, N. Chen, W. Chen, B. He</span>
</div>

<div class="pub-card" data-topic="sim">
  <span class="badge-venue">ICLR 2025 Blogposts</span>
  <span class="pub-title">Can LLM Simulations Truly Reflect Humanity? A Deep Dive</span>
  <span class="pub-tldr">A deep dive into whether LLM simulations truly reflect human behavior.</span>
  <span class="pub-links"><a href="https://iclr-blogposts.github.io/2025/blog/rethinking-llm-simulation/">Paper</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Tang, B. He</span>
</div>

</div>

<script>
(function () {
  function initPubFilter() {
    var bar = document.querySelector('.pub-filter');
    var list = document.getElementById('pub-list');
    if (!bar || !list) return;
    var buttons = bar.querySelectorAll('button');
    var cards = list.querySelectorAll('.pub-card');
    bar.addEventListener('click', function (e) {
      var btn = e.target.closest('button');
      if (!btn) return;
      var topic = btn.getAttribute('data-filter');
      buttons.forEach(function (b) { b.classList.remove('active'); });
      btn.classList.add('active');
      cards.forEach(function (card) {
        var show = (topic === 'all' || card.getAttribute('data-topic') === topic);
        card.style.display = show ? '' : 'none';
      });
    });
  }
  function initThumbLightbox() {
    document.addEventListener('click', function (e) {
      var t = e.target;
      if (!t.classList || !t.classList.contains('pub-thumb')) return;
      var overlay = document.createElement('div');
      overlay.className = 'thumb-lightbox';
      var img = document.createElement('img');
      img.src = t.src;
      overlay.appendChild(img);
      overlay.addEventListener('click', function () { overlay.remove(); });
      document.body.appendChild(overlay);
    });
    document.addEventListener('keydown', function (e) {
      if (e.key !== 'Escape') return;
      var open = document.querySelector('.thumb-lightbox');
      if (open) open.remove();
    });
  }
  function init() {
    initPubFilter();
    initThumbLightbox();
  }
  if (document.readyState === 'loading') {
    document.addEventListener('DOMContentLoaded', init);
  } else {
    init();
  }
})();
</script>

# 🏆 Awards

- *2026*, <span class="news-hot">Outstanding Reviewer Award</span>, EACL 2026
- *2025*, Graduate Student Travel Grant × 2, NUS
- *2024*, **Research Achievement Award**, NUS
- *2024*, [**Venture Initiation Program@SoC (10K SGD)**](https://www.comp.nus.edu.sg/entrepreneurship/awards/iepsoc/), NUS
- *2019 - 2022*, Ong Sin Seng & Lim Song Kie Bursary, NUS
- *2019*, Academic Scholarship, SJTU
- *2018*, Zhiyuan Honors Scholarship, SJTU
- *2018*, [Soh Bing Undergraduate Scholarship](https://en.wikipedia.org/wiki/Shuping_Scholarship), Shanghai
- *2017*, Zhiyuan Honors Scholarship, SJTU
- *2017*, **Zhiyuan Honors Program (Top 5% of all undergraduates)**, SJTU
- *2016*, [Soh Bing High School Student Scholarship](https://baike.baidu.com/item/%E5%8F%94%E8%98%8B%E5%A5%96%E5%AD%A6%E9%87%91/15518392), Fuyang

# 🎤 Invited Talks & Interviews

- *2025*, Invited talk at **Qube Research & Technologies** (Singapore office) on leveraging LLMs to make fair and unbiased judgments about factors.
- *2025*, Invited talk at **AI4X 2025** on utilizing LLMs to make trading decisions in the cryptocurrency market.
- *2025*, Invited talk on LLM-based human simulations at **Renmin University of China**, hosted by [Yunhai Wang](https://www.yunhaiwang.net/). [Slides](https://docs.google.com/presentation/d/1o1QLzx59E2pbUxGg935crnCGPt-fww4nTpRZ5KONi_w/edit?usp=sharing)
- *2025*, Invited talk by **AI Time** on my ICLR 2025 BlogPost *Can LLMs Truly Simulate Humanity? A Deep Dive*. [Video](https://www.bilibili.com/video/BV1JuRPYRECM/?share_source=copy_web&vd_source=cc8bcf9a00d3f9ba43eb256a2c7068bd)
- *2024*, Interviewed by the **Open Source Promotion Plan (OSPP)**, a summer program organized by the Institute of Software, Chinese Academy of Sciences. [Interview](https://mp.weixin.qq.com/s/MWJtW-cB_wXkXHsOHy2m3Q)
- *2023*, Invited talk on [EX-Graph](https://arxiv.org/abs/2310.01015) at **The Hong Kong University of Science and Technology (Guangzhou)**. [Slides](https://drive.google.com/file/d/1Iy7wUvbZ-Z-7dLvlEY0CupCVrPX5GbyL/view?usp=sharing)

# 📖 Education

- *2023 - Now*, Ph.D. Student, Computer Science, National University of Singapore
- *2019 - 2022*, Bachelor, Computer Science with a Minor in Economics, National University of Singapore
- *2017 - 2019*, Undergraduate, Chemistry, Shanghai Jiao Tong University

# 💼 Industry Experience

- *2026.01 - Now*, Quant Researcher, MS Capital, Singapore
- *2022*, Algorithm Tutor, OI Wiki, GitHub
- *2021*, Backend Engineer Intern, Ant Group, Shanghai
- *2020*, Python Tutor, InterMine, University of Cambridge

# 💬 Projects

- **SurviveSJTU Manual:** I authored a chapter for the latest edition of the SurviveSJTU Manual — an online survival guide for students at Shanghai Jiao Tong University. You can browse the manual and my contributions [on GitHub](https://github.com/SurviveSJTU/SurviveSJTUManual).

# 🔥 Service

- *2025*, ICAIF 2025 Secure FinAI Contest Local Organizer
- *2023 - Now*, Seminar Organizer, Xtra Lab, NUS
- *2023 - Now*, Fire Warden, School of Computing, NUS

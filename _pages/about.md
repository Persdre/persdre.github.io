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

I am a Computer Science Ph.D. candidate at the National University of Singapore, advised by Prof. [Bingsheng He](https://www.comp.nus.edu.sg/~hebs/). My research focuses on **LLM Multi-Agent Systems**, **Trustworthy AI**, and **data-centric approaches to improving foundation models**. My research has appeared at top venues including **ICLR, NeurIPS, ICML, ACL, EMNLP, COLM, and LOG**, as well as in journals such as **ACM Computing Surveys** and **IEEE TKDE**, with several <span class="news-hot">Oral</span> presentations. I also received an **Outstanding Reviewer Award** from **EACL 2026**.

My representative work, [**MegaAgent**](https://arxiv.org/abs/2408.09955) (ACL 2025 Findings), is a fully **autonomous** large-scale LLM-based multi-agent system that needs no predefined SOPs — it dynamically decomposes tasks, spawns and coordinates agents in parallel, and scales to **590 agents** in a national policy simulation.

On the data side, I build pioneering datasets and benchmarks (e.g., [EX-Graph](https://openreview.net/forum?id=juE0rWGCJW) at ICLR 2024 and [CrossAlpha](https://arxiv.org/abs/2605.29286)), and I characterize and mitigate model biases both empirically ([judging bias in large reasoning models](https://arxiv.org/abs/2504.09946), COLM 2025) and at training time via reinforcement learning ([Treat Bias as Noise](https://arxiv.org/abs/2602.01528)). I am also passionate about **LLMs for finance**: using LLMs to mine cross-market alpha factors from corporate disclosures and to guide trading decisions.

I believe LLMs should be developed and deployed in a way that benefits all of humanity, not just a privileged segment. As a typical ENTP, I'm positive, outgoing, and full of curiosity. I enjoy discussing research, PhD applications, life choices, and beyond — feel free to reach out. <span style="color:#800020;font-weight:600;">I am always open to collaborations: if you share similar interests or see potential synergies, email me at persdre@gmail.com!</span>

# 📰 News

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

<div class="pub-card" data-topic="mas">
  <span class="badge-venue">ACL 2025 Findings</span> <span class="badge-honor">ICLR 2025 FM-Wild Workshop Oral</span>
  <span class="pub-title">MegaAgent: A Large-Scale Autonomous LLM-based Multi-Agent System Without Predefined SOPs</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2408.09955">Paper</a> <a href="https://github.com/Xtra-Computing/MegaAgent">Code</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, T. Wang, Z. Tang, Q. Li, N. Chen, J. Liang, B. He</span>
</div>

<div class="pub-card" data-topic="mas">
  <span class="badge-venue">ICML 2025 Multi-Agent Systems Workshop</span>
  <span class="pub-title">AgentTaxo: Dissecting and Benchmarking Token Distribution of LLM Multi-Agent Systems</span>
  <span class="pub-links"><a href="https://openreview.net/forum?id=0iLbiYYIpC">Paper</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Tang, N. Chen, T. Wang, B. He</span>
</div>

<div class="pub-card" data-topic="mas">
  <span class="badge-venue">ACL 2026 Findings</span>
  <span class="pub-title">Diversity Collapse in Multi-Agent LLM Systems: Structural Coupling and Collective Failure in Open-Ended Idea Generation</span>
  <span class="pub-authors">N. Chen, Y. Tong, Y. Yang, X. Zhang, <span class="me">Qian Wang</span>, B. He</span>
</div>

<div class="pub-card" data-topic="trust">
  <span class="badge-venue">COLM 2025</span>
  <span class="pub-title">Assessing Judging Bias in Large Reasoning Models: An Empirical Study</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2504.09946">Paper</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Lou, Z. Tang, N. Chen, X. Zhao, W. Zhang, D. Song, B. He</span>
</div>

<div class="pub-card" data-topic="trust">
  <span class="badge-venue">NeurIPS 2025 Lock-LLM Workshop</span>
  <span class="pub-title">Towards Evaluating Fake Reasoning Bias in Language Models</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2507.13758">Paper</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Tang, Z. Lou, N. Chen, W. Wang, B. He</span>
</div>

<div class="pub-card" data-topic="trust">
  <span class="badge-venue">Preprint 2025</span>
  <span class="pub-title">JudgeLRM: Large Reasoning Models as a Judge</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2504.00050">Paper</a></span>
  <span class="pub-authors">N. Chen, Z. Hu, Q. Zou, J. Wu, <span class="me">Qian Wang</span>, B. Hooi, B. He</span>
</div>

<div class="pub-card" data-topic="rl">
  <span class="badge-venue">ICML 2026 AI4GOOD Workshop</span>
  <span class="pub-title">Treat Bias as Noise: Training Bias-Robust LLM Reasoning via Reinforcement Learning</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2602.01528">Paper</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, X. Zhao, Z. Zhang, Z. Lou, N. Chen, D. Song, B. He</span>
</div>

<div class="pub-card" data-topic="rl">
  <span class="badge-venue">Preprint 2026</span>
  <span class="pub-title">Learning to Learn-at-Test-Time: Language Agents with Learnable Adaptation Policies</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2604.00830">Paper</a></span>
  <span class="pub-authors">Z. Lou, H. Chen, Y. Li, <span class="me">Qian Wang</span>, B. Hooi</span>
</div>

<div class="pub-card" data-topic="rl">
  <span class="badge-venue">Preprint 2026</span>
  <span class="pub-title">RL-RIG: A Generative Spatial Reasoner via Intrinsic Reflection</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2602.19974">Paper</a></span>
  <span class="pub-authors">T. Wang, Z. Ma, <span class="me">Qian Wang</span>, X. Zhang, X. Long, B. Zhou</span>
</div>

<div class="pub-card" data-topic="fma">
  <span class="badge-venue">ICLR 2026</span> <span class="badge-honor">Oral</span>
  <span class="pub-title">LLM DNA: Tracing Model Evolution via Functional Representations</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2509.24496">Paper</a></span>
  <span class="pub-authors">Z. Wu, H. Zhao, Z. Wang, J. Guo, <span class="me">Qian Wang</span>, B. He</span>
</div>

<div class="pub-card" data-topic="mem">
  <span class="badge-venue">Preprint 2026</span>
  <span class="pub-title">LLM Agent Memory: A Survey from a Unified Representation–Management Perspective</span>
  <span class="pub-links"><a href="https://openreview.net/forum?id=KPs1EgGKcT">Paper</a></span>
  <span class="pub-authors">Z. Tang, X. He, T. Zhao, F. Wei, X. Liu, P. Dong, <span class="me">Qian Wang</span>, et al.</span>
</div>

<div class="pub-card" data-topic="mem">
  <span class="badge-venue">ICML 2026 Agents-in-the-Wild Workshop</span>
  <span class="pub-title">Parameters as Agentic Memory: Internalizing Long-Horizon Memories for Efficient LLM Agents</span>
  <span class="pub-authors">Z. Tang, F. Wei, P. Dong, X. Liu, <span class="me">Qian Wang</span>, X. Chu, B. Li</span>
</div>

<div class="pub-card" data-topic="fin">
  <span class="badge-venue">Preprint 2026</span>
  <span class="pub-title">CrossAlpha: An Annual-Report Benchmark for Cross-Market Factor Research</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2605.29286">Paper</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Tong, N. Chen, Z. Wu, B. He</span>
</div>

<div class="pub-card" data-topic="fin">
  <span class="badge-venue">ICLR 2025 Financial AI Workshop</span>
  <span class="pub-title">Exploring LLM Cryptocurrency Trading Through Fact-Subjectivity Aware Reasoning</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2410.12464">Paper</a> <a href="https://github.com/Persdre/FS-ReasoningAgent">Code</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, Y. Gao, Z. Tang, B. Luo, N. Chen, B. He</span>
</div>

<div class="pub-card" data-topic="fin">
  <span class="badge-venue">EMNLP 2024</span>
  <span class="pub-title">CryptoTrade: A Reflective LLM-based Agent to Guide Zero-shot Cryptocurrency Trading</span>
  <span class="pub-links"><a href="https://aclanthology.org/2024.emnlp-main.63.pdf">Paper</a> <a href="https://github.com/Xtra-Computing/CryptoTrade">Code</a></span>
  <span class="pub-authors">Y. Li, B. Luo, <span class="me">Qian Wang</span>, N. Chen, X. Liu, B. He</span>
</div>

<div class="pub-card" data-topic="graph">
  <span class="badge-venue">ICLR 2024</span>
  <span class="pub-title">EX-Graph: A Pioneering Dataset Bridging Ethereum and X</span>
  <span class="pub-links"><a href="https://openreview.net/forum?id=juE0rWGCJW">Paper</a> <a href="https://github.com/Persdre/EX-Graph">Code</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Zhang, Z. Liu, S. Lu, B. Luo, B. He</span>
</div>

<div class="pub-card" data-topic="graph">
  <span class="badge-venue">LOG 2025</span> <span class="badge-honor">Oral</span>
  <span class="pub-title">Less is More: Using Buffer Nodes to Reduce Excessive Majority Node Influence in Class Imbalance Graphs</span>
  <span class="pub-links"><a href="https://openreview.net/forum?id=6ikB5L1kzq">Paper</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, Z. Liu, Z. Zhang, B. Luo, B. He</span>
</div>

<div class="pub-card" data-topic="graph">
  <span class="badge-venue">NeurIPS 2024 Datasets & Benchmarks</span>
  <span class="pub-title">Multi-Chain Graphs of Graphs: A New Approach to Analyzing Blockchain Datasets</span>
  <span class="pub-links"><a href="https://openreview.net/forum?id=mlbVgVKwD7">Paper</a></span>
  <span class="pub-authors">B. Luo, Z. Zhang, <span class="me">Qian Wang</span>, B. He</span>
</div>

<div class="pub-card" data-topic="graph">
  <span class="badge-venue">IEEE TKDE 2025</span>
  <span class="pub-title">A Survey of Imbalanced Learning on Graphs: Problems, Techniques, and Future Directions</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2308.13821">Paper</a></span>
  <span class="pub-authors">Z. Liu, Y. Li, N. Chen, <span class="me">Qian Wang</span>, B. Hooi, B. He</span>
</div>

<div class="pub-card" data-topic="sim">
  <span class="badge-venue">Preprint 2025</span>
  <span class="pub-title">LLM-based Human Simulations Have Not Yet Been Reliable</span>
  <span class="pub-links"><a href="https://arxiv.org/abs/2501.08579">Paper</a></span>
  <span class="pub-authors"><span class="me">Qian Wang</span>, J. Wu, Z. Tang, B. Luo, N. Chen, W. Chen, B. He</span>
</div>

<div class="pub-card" data-topic="sim">
  <span class="badge-venue">ICLR 2025 Blogposts</span>
  <span class="pub-title">Can LLM Simulations Truly Reflect Humanity? A Deep Dive</span>
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
  if (document.readyState === 'loading') {
    document.addEventListener('DOMContentLoaded', initPubFilter);
  } else {
    initPubFilter();
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

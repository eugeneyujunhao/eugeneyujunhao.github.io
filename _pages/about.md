---
permalink: /
title: "Eugene Yu Jun Hao"
excerpt: "Eugene Yu Jun Hao is a PhD student in Computer Science at Peking University and a research intern at Microsoft Research Asia, working on rich-format document generation."
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<div class="hero" markdown="0">
  <img class="hero__avatar" src="/images/profile.jpg" alt="Eugene Yu Jun Hao" />
  <h1 class="hero__name">Eugene <span class="accent">Yu Jun Hao</span></h1>
  <p class="hero__tagline" style="text-align:center;"><span class="hero__type" id="typed"></span></p>
  <div class="hero__links">
    <span class="hero__location"><i class="fas fa-location-dot"></i> Beijing, China</span>
    <a href="https://scholar.google.com/citations?user=AsPV7QIAAAAJ&hl=zh-CN"><i class="ai ai-google-scholar"></i> Google Scholar</a>
    <a href="https://www.linkedin.com/in/eugenejyu"><i class="fab fa-linkedin"></i> LinkedIn</a>
    <a href="https://github.com/eugeneyujunhao"><i class="fab fa-github"></i> GitHub</a>
    <a href="mailto:ejyu@pku.edu.cn"><i class="fas fa-envelope"></i> Email</a>
  </div>
</div>

<script>
(function () {
  var phrases = [
    "PhD Student @ Peking University",
    "Research Intern @ Microsoft Research Asia",
    "Productivity agents"
  ];
  var el = document.getElementById('typed');
  if (!el) return;
  if (window.matchMedia && window.matchMedia('(prefers-reduced-motion: reduce)').matches) {
    el.textContent = phrases[0]; el.classList.add('done'); return;
  }
  var p = 0, i = 0, deleting = false;
  function tick() {
    var full = phrases[p];
    if (!deleting) {
      el.textContent = full.slice(0, ++i);
      if (i === full.length) { deleting = true; return setTimeout(tick, 1600); }
    } else {
      el.textContent = full.slice(0, --i);
      if (i === 0) { deleting = false; p = (p + 1) % phrases.length; }
    }
    setTimeout(tick, deleting ? 35 : 70);
  }
  tick();
})();
</script>

I am a PhD student in Computer Science at Peking University, advised by
**Prof. Sujian Li**, where I also earned my bachelor's degree. I was born and
raised in Malaysia, and am currently based in Beijing, China. I am also
currently a research intern at Microsoft Research Asia, working on
**rich-format document generation**. Broadly, I am interested in building
**productivity agents** that help people get real work done.

<div class="affil" markdown="0">
  <span class="affil-label">Affiliations &amp; Experience</span>
  <div class="affil-logos">
    <img src="/images/logos/pku.svg" alt="Peking University" title="Peking University" />
    <img src="/images/logos/microsoft.svg" alt="Microsoft Research Asia" title="Microsoft Research Asia" />
    <img src="/images/logos/huawei.svg" alt="Huawei Noah's Ark Lab" title="Huawei Noah's Ark Lab" />
  </div>
</div>

Publications
======
<div class="pub-list" markdown="0">

<div class="pub">
  <span class="venue">ICML 26</span>
  <span class="pub-main">
    <a class="pub-title" href="https://icml.cc/virtual/2026/poster/61769">FormAct: Agentic Source Editing for Rich-Format Document Generation</a>
    <span class="authors"><b>Eugene J. Yu</b>, Xingxing Zhang, Yuan Xia, Tao Ge, Xun Wang, FNU Kartik, Vishwas Suryanarayanan, Cheng Yang, Amanda Jiang, Jiayu Ding, Xiangyu Wong, Tengchao Lv, Lei Cui, Si-Qing Chen, Furu Wei, Sujian Li</span>
  </span>
</div>

<div class="pub">
  <span class="venue">ICLR 26</span>
  <span class="pub-main">
    <a class="pub-title" href="https://openreview.net/pdf?id=DrhWTuhtYq">Qurl: Rubrics as Judge for Open-Ended Question Answering</a>
    <span class="authors">Xiyu Wei, Qingwei Zong, Xiaoguang Li, <b>Eugene J. Yu</b>, Sujian Li</span>
  </span>
</div>

<div class="pub">
  <span class="venue">arXiv 26</span>
  <span class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2606.02091">DFlare: Scaling Up Draft Capacity for Block Diffusion Speculative Decoding</a>
    <span class="authors">Jiebin Zhang, Zhenghan Yu, Song Liu, <b>Eugene J. Yu</b>, Zheng Li, Dawei Zhu, Jiangshan Duo, Weimin Xiong, Yifan Song, Guanghua Yu, Jianchen Zhu, Sujian Li</span>
  </span>
</div>

<div class="pub">
  <span class="venue">ICLR 26</span>
  <span class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2603.01639">Learning to Draft: Adaptive Speculative Decoding with Reinforcement Learning</a>
    <span class="authors">Jiebin Zhang, Zhenghan Yu, Liang Wang, Nan Yang, <b>Eugene J. Yu</b>, Zheng Li, Yifan Song, Dawei Zhu, Xingxing Zhang, Furu Wei, Sujian Li</span>
  </span>
</div>

<div class="pub">
  <span class="venue">ACL 25</span>
  <span class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2506.23393">Hierarchical Memory Organization for Wikipedia Generation</a>
    <span class="authors"><b>Eugene J. Yu</b>, Dawei Zhu, Yifan Song, Xiangyu Wong, Jiebin Zhang, Wenxuan Shi, Xiaoguang Li, Qun Liu, Sujian Li</span>
  </span>
</div>

<div class="pub">
  <span class="venue">COLING 25</span>
  <span class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2402.18264v2">WikiGenBench: Exploring Full-Length Wikipedia Generation under Real-World Scenario</a>
    <span class="authors">Jiebin Zhang, <b>Eugene J. Yu</b>, Qinyu Chen, Chenhao Xiong, Dawei Zhu, Han Qian, Mingbo Song, Weimin Xiong, Xiaoguang Li, Qun Liu, Sujian Li <span class="note">(Co-first author)</span></span>
  </span>
</div>

</div>

<!-- TODO: replace each "#" with the arXiv/paper URL; fill in full author lists for the ACL/COLING entries. -->

Experience
======
<div class="exp-list" markdown="0">

<div class="exp">
  <div class="exp-head">
    <span class="exp-role"><b>Research Intern</b>, Microsoft Research Asia</span>
    <span class="exp-when">Jul 2025 – Present · Beijing</span>
  </div>
  <ul class="exp-points">
    <li>Building <b>productivity agents</b> for rich-format document generation, with <b>Xingxing Zhang</b>.</li>
  </ul>
</div>

<div class="exp">
  <div class="exp-head">
    <span class="exp-role"><b>Research Intern</b>, Huawei Noah's Ark Lab</span>
    <span class="exp-when">Jul 2024 – Sep 2024 · Shenzhen</span>
  </div>
  <ul class="exp-points">
    <li>Worked on long-form Wikipedia generation, with <b>Wenxuan Shi</b> &amp; <b>Xiaoguang Li</b>.</li>
  </ul>
</div>

<div class="exp">
  <div class="exp-head">
    <span class="exp-role"><b>Quantitative Analysis Intern</b>, Derivatives China</span>
    <span class="exp-when">Feb 2023 – Apr 2023 · Beijing</span>
  </div>
  <ul class="exp-points">
    <li>Worked on factor mining and risk-assessment models for market-trend analysis.</li>
  </ul>
</div>

</div>

Education
======
<div class="exp-list" markdown="0">

<div class="exp">
  <div class="exp-head">
    <span class="exp-role"><b>Ph.D. in Computer Science</b>, Peking University</span>
    <span class="exp-when">2023 – Present · Beijing</span>
  </div>
  <ul class="exp-points">
    <li>Advised by <b>Prof. Sujian Li</b>. Research on large language models and rich-format document generation.</li>
  </ul>
</div>

<div class="exp">
  <div class="exp-head">
    <span class="exp-role"><b>B.S. in Computer Science</b>, Peking University</span>
    <span class="exp-when">2019 – 2023 · Beijing</span>
  </div>
</div>

</div>

News
======
<div class="news-list" markdown="0">

<div class="news-row">
  <span class="news-date">Jul 2026</span>
  <span class="news-body">Attending <b>ICML 2026</b> in Seoul, South Korea (Jul 6–11) to present <b>FormAct</b>.</span>
</div>

<div class="news-row">
  <span class="news-date">Apr 2026</span>
  <span class="news-body"><b>FormAct</b> accepted to ICML 2026.</span>
</div>

<div class="news-row">
  <span class="news-date">Jul 2025</span>
  <span class="news-body">Attended <b>ACL 2025</b> in Vienna, Austria (Jul 27 – Aug 1) to present <b>MOG</b>.</span>
</div>

<div class="news-row">
  <span class="news-date">May 2025</span>
  <span class="news-body"><b>MOG</b> accepted to ACL 2025.</span>
</div>

<div class="news-row">
  <span class="news-date">May 2025</span>
  <span class="news-body">Prize winner at <b>ETH Beijing 2025</b> hackathon.</span>
</div>

<div class="news-row">
  <span class="news-date">Nov 2024</span>
  <span class="news-body">Prize winner at <b>ETHGlobal Bangkok 2024</b> hackathon.</span>
</div>

<div class="news-row">
  <span class="news-date">Nov 2024</span>
  <span class="news-body"><b>WikiGenBench</b> accepted to COLING 2025.</span>
</div>

</div>

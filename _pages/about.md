---
layout: academic-home
permalink: /
title: "Qixun Wang (王启迅)"
author_profile: false
classes: wide
redirect_from:
  - /about/
  - /about.html
---

<section id="about">
  <h1><strong>Qixun</strong> Wang <span lang="zh">王启迅</span></h1>

  <div class="academic-profile">
    <img src="/images/wqx_new.jpg" alt="Portrait of Qixun Wang">
  </div>

  <div class="academic-intro">
    <p>
      I am a third-year Ph.D. student in the School of Intelligence Science and Technology at
      <strong>Peking University</strong>.
    </p>

    <p>My research interests include:</p>
    <ul class="research-interests">
      <li>
        <strong>Multimodal Large Language Models (MLLMs)</strong>, including latent visual reasoning,
        agentic visual reasoning, and evaluation of MLLMs.
      </li>
      <li>
        <strong>Out-of-distribution (OOD) generalization</strong>, including theoretical analysis and
        algorithm design across computer vision, graph data, and the generalization behavior of LLMs.
      </li>
    </ul>

    <div class="academic-social" aria-label="Contact links">
      <a href="mailto:qixun.wang@pku.edu.cn" title="Email" aria-label="Email">
        <i class="fas fa-envelope" aria-hidden="true"></i>
      </a>
      <a href="https://scholar.google.com/citations?user=a_dDoucAAAAJ&amp;hl=en" title="Google Scholar" aria-label="Google Scholar">
        <i class="ai ai-google-scholar" aria-hidden="true"></i>
      </a>
      <a href="https://github.com/NOVAglow646" title="GitHub" aria-label="GitHub">
        <i class="fab fa-github" aria-hidden="true"></i>
      </a>
    </div>
  </div>
</section>

<section id="news">
  <h2>News</h2>
  <div class="news-scroll">
    <table class="news-table">
      <tbody>
        <tr>
          <th scope="row">May, 2026</th>
          <td>
            One paper, <a href="https://arxiv.org/pdf/2607.28595">Beacon</a>, won improving reasoning-mode adaptiveness and achieving genuine tool-induced performance gains in agentic visual reasoning, was released on arXiv.
          </td>
        </tr>
        <tr>
          <th scope="row">May, 2026</th>
          <td>
            A paper entitled <a href="https://arxiv.org/pdf/2605.18984">Artifact-Bench</a>, which evaluates MLLMs for AI-generated video detection, was released on arXiv.
          </td>
        </tr>
        <tr>
          <th scope="row">May, 2026</th>
          <td>
            Our paper <a href="https://arxiv.org/pdf/2605.19342">Semantic-Enriched Latent Visual Reasoning</a>
            was accepted to ICML 2026.
          </td>
        </tr>
        <tr>
          <th scope="row">March, 2026</th>
          <td>I joined the Kling Team at Kuaishou Technology as a research intern.</td>
        </tr>
        <tr>
          <th scope="row">February, 2026</th>
          <td>
            Two papers were accepted to CVPR 2026, covering reasoning in latent visual space and a
            benchmark for unified multimodal models.
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</section>

<section id="publications">
  <h2>
    Selected papers
    <span class="section-note">(<a href="https://scholar.google.com/citations?user=a_dDoucAAAAJ&amp;hl=en">see full publication</a>)</span>
  </h2>

  <ol class="publications-list">
    <li class="publication-item">
      <div class="publication-badges">
        <span class="publication-badge preprint">arXiv</span>
      </div>
      <div>
        <div class="publication-title">Beacon: Knowing When and Why to Perform Agentic Visual Reasoning</div>
        <div class="publication-authors">
          <u>Qixun Wang</u>*, Yang Shi*, Letian Cheng, Zhuoran Zhang, Yan He, Yuqi Tang, Qi Zhang, Xinlei Yu, Ruizhe Chen, Tianrun Xu, Yuanxing Zhang, Pengfei Wan, Haotian Wang, Xianghua Ying
        </div>
        <div class="publication-venue"><em>CVPR</em>, 2026</div>
        <div class="publication-highlights">
          <div>
            • Conduct a comprehensive analysis of reasoning-mode adaptiveness and tool-induced performance changes in existing agentic visual reasoning models.
          </div>
          <div>• Propose a novel training recipe that achieves state-of-the-art or competitive performance across 13 visual reasoning benchmarks, while improving reasoning-mode adaptiveness and delivering genuine tool-induced performance gains.</div>
        </div>
        <div class="publication-links">
          <a href="https://arxiv.org/pdf/2607.28595">PDF</a>
          <a href="https://github.com/NOVAglow646/Beacon">Code</a>
        </div>
      </div>
    </li>

    <li class="publication-item">
      <div class="publication-badges">
        <span class="publication-badge">CVPR</span>
      </div>
      <div>
        <div class="publication-title">Monet: Reasoning in Latent Visual Space Beyond Images and Language</div>
        <div class="publication-authors">
          <u>Qixun Wang</u>, Yang Shi, Yifei Wang, Yuanxing Zhang, Pengfei Wan, Kun Gai,
          Xianghua Ying, and Yisen Wang
        </div>
        <div class="publication-venue"><em>CVPR</em>, 2026</div>
        <div class="publication-highlights">
          <div>
            • Propose a new framework for multimodal latent reasoning, including dataset construction,
            SFT, and RL algorithms, achieving significant improvements on both in-domain and OOD visual
            reasoning benchmarks
          </div>
          <div>• 200+ GitHub stars</div>
        </div>
        <div class="publication-links">
          <a href="http://arxiv.org/abs/2511.21395">PDF</a>
          <a href="https://github.com/NOVAglow646/Monet">Code</a>
        </div>
      </div>
    </li>

    <li class="publication-item">
      <div class="publication-badges">
        <span class="publication-badge">ICLR</span>
      </div>
      <div>
        <div class="publication-title">Can In-context Learning Really Generalize to Out-of-distribution Tasks?</div>
        <div class="publication-authors">
          <u>Qixun Wang</u>, Yifei Wang, Xianghua Ying, and Yisen Wang
        </div>
        <div class="publication-venue"><em>ICLR</em>, 2025</div>
        <div class="publication-highlights">
          <div>• Reveal the capability boundary and algorithm selection mechanism of ICL on OOD tasks through carefully designed experiments and theoretical analysis.</div>
        </div>
        <div class="publication-links">
          <a href="https://openreview.net/pdf?id=INe4otjryz">PDF</a>
          <a href="https://github.com/NOVAglow646/ICL-OOD">Code</a>
        </div>
      </div>
    </li>

    <li class="publication-item">
      <div class="publication-badges">
        <span class="publication-badge">NeurIPS</span>
      </div>
      <div>
        <div class="publication-title">Dissecting the Failure of Invariant Learning on Graphs</div>
        <div class="publication-authors">
          <u>Qixun Wang</u>, Yifei Wang, Yisen Wang, and Xianghua Ying
        </div>
        <div class="publication-venue"><em>NeurIPS</em>, 2024</div>
        <div class="publication-highlights">
          <div>• Theoretically and empirically demonstrate the failure modes of classic invariant learning approaches on graph data, and propose a new training objective with
significant performance gains and theoretical guarantees.</div>
        </div>
        <div class="publication-links">
          <a href="https://arxiv.org/pdf/2411.02847">PDF</a>
          <a href="https://github.com/NOVAglow646/NeurIPS24-Invariant-Learning-on-Graphs">Code</a>
        </div>
      </div>
    </li>

    <li class="publication-item">
      <div class="publication-badges">
        <span class="publication-badge">NeurIPS</span>
        <span class="publication-badge spotlight">Spotlight</span>
      </div>
      <div>
        <div class="publication-title">
          Improving Out-of-distribution Generalization by Adversarial Training with Structured Priors
        </div>
        <div class="publication-authors">
          <u>Qixun Wang*</u>, Yifei Wang*, Hong Zhu, and Yisen Wang
        </div>
        <div class="publication-venue"><em>NeurIPS</em>, 2022</div>
        <div class="publication-highlights">
          <div>• Propose a simple yet effective low-rank adversarial training strategy that improves the OOD generalization of visual recognition models.</div>
        </div>
        <div class="publication-links">
          <a href="https://arxiv.org/pdf/2210.06807">PDF</a>
          <a href="https://github.com/NOVAglow646/NIPS22-MAT-and-LDAT-for-OOD">Code</a>
        </div>
      </div>
    </li>

   <li class="publication-item">
      <div class="publication-badges">
        <span class="publication-badge">ICML</span>
      </div>
      <div>
        <div class="publication-title">Semantic-Enriched Latent Visual Reasoning</div>
        <div class="publication-authors">
          Tianrun Xu, Yue Sun, <u>Qixun Wang</u>, Jingyi Lu, Yuan Wang, Tianren Zhang, Longteng Guo,
          Fengyun Rao, Jing Lyu, Feng Chen, and Jing Liu
        </div>
        <div class="publication-venue"><em>ICML</em>, 2026</div>
        <div class="publication-highlights">
          <div>• Reveal and address the lack of semantic richness in latent embeddings learned by prior latent visual reasoning training paradigms.</div>
        </div>
        <div class="publication-links">
          <a href="https://arxiv.org/pdf/2605.19342">PDF</a>
          <a href="https://github.com/tinnel123666888/slvr">Code</a>
        </div>
      </div>
    </li>


    <li class="publication-item">
      <div class="publication-badges">
        <span class="publication-badge preprint">arXiv</span>
      </div>
      <div>
        <div class="publication-title">
          Artifact-Bench: Evaluating MLLMs on Detecting and Assessing the Artifacts of AI-Generated Videos
        </div>
        <div class="publication-authors">
          Yuqi Tang*, Yang Shi*, Zhuoran Zhang*, <u>Qixun Wang*</u>, and a group of outstanding researchers
        </div>
        <div class="publication-venue"><em>arXiv preprint</em>, 2026</div>
        <div class="publication-highlights">
          <div>• Propose a comprehensive benchmark for evaluating MLLMs’ ability to detect and analyze artifacts in AI-generated videos</div>
        </div>
        <div class="publication-links">
          <a href="https://arxiv.org/pdf/2605.18984">PDF</a>
          <a href="https://github.com/FrankYang-17/Artifact-Bench">Code</a>
        </div>
      </div>
    </li>


  </ol>
</section>

<section id="experiences">
  <h2>Experience</h2>
  <ul class="compact-list">
    <li>
      <strong>Kling Team, Kuaishou Technology (快手科技)</strong> — Research Intern
      <em>(March 2026–present)</em><br>
      Working on multimodal agents.
    </li>
  </ul>
</section>

<section id="education">
  <h2>Education</h2>
  <ul class="compact-list">
    <li>
      Ph.D. Candidate in Machine Learning and Computer Vision, School of Intelligence Science and
      Technology, <strong>Peking University</strong> (2023–present)
    </li>
    <li>
      B.S. in Intelligence Science and Technology, EECS, <strong>Peking University</strong> (2019–2023)
    </li>
  </ul>
</section>

<section id="awards">
  <h2>Awards</h2>
  <ul class="compact-list">
    <li>The Third-Class Scholarship of Peking University (2025)</li>
    <li>Merit Student at Peking University (2025)</li>
    <li>Outstanding Graduate of Peking University (2023)</li>
    <li>Yanchuang Capital Scholarship, Top 6% (2022)</li>
    <li>Merit Student at Peking University, Top 6% (2022)</li>
    <li>Academic Innovation Award at Peking University, Top 1% (2022)</li>
    <li>Award for Academic Excellence (2021)</li>
  </ul>
</section>

<!--
Paper teaser images retained for future use:
<img src="/images/publications/SLVR2.png" alt="SLVR teaser" class="paper-teaser">
<img src="/images/publications/Monet2.png" alt="Monet teaser" class="paper-teaser">
<img src="/images/publications/ICL-OOD2.png" alt="ICL-OOD teaser" class="paper-teaser">
<img src="/images/publications/GRAPH-OOD2.png" alt="Invariant Learning on Graphs teaser" class="paper-teaser">
<img src="/images/publications/AT-OOD2.png" alt="OOD robustness teaser" class="paper-teaser">
<img src="/images/publications/artifact_taxonomy.png" alt="ArtifactBench teaser" class="paper-teaser">
<img src="/images/publications/artifact_taxonomy.png" alt="ArtifactBench teaser" class="paper-teaser">
-->

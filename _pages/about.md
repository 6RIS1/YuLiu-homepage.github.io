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

Hello, I am an Assistant Professor at [Xi'an Jiaotong-Liverpool University](https://scholar.xjtlu.edu.cn/en/persons/YuLiu02). My research interests lie primarily in Human-Computer Interaction (HCI) and Visualization. More specifically, my work focuses on mobile device interaction and visualization, multi-device interaction and visualization, narrative visualization for digital cultural heritage, and data physicalization.

<span class='anchor' id='news'></span>
<span class='anchor' id='-news'></span>
# ![world-news_2644746](https://github.com/user-attachments/assets/f25c2d8f-46b8-4880-9473-4280fb48cc65) News
- *2026.08*: &nbsp; Two papers were accepted to **ACM MobileHCI 2026**! Notably, *"Exploring the Effects of Narrative Virtual Reality in Traditional Chinese Scroll Paintings"* received the **Honorable Mention** award. The second paper is *"MoveMate: Supporting Video-Guided Workouts through Motion Visual Analysis and Multi-Device Guidance"*.
- *2025.12*: &nbsp; Two papers were accepted to **ACM VINCI 2025**! Notably, *"Text-Color Hybrid Labeling for Multiclass Map Visualization: A Comparative Evaluation of Four Annotation Strategies"* received the **Honorable Mention** award. The second paper is *"From Myth to Interface: An AI-Augmented Interactive Visual System for Exploring Artifact Interactions in Journey to the West"*.

<details class="news-archive">
  <summary class="news-toggle-btn"><span>View More News (4)</span> ▾</summary>
  <ul class="news-archive-list">
    <li><em>2025.06</em>: &nbsp; Our project <em>"ARthroMap (画游姑苏)"</em> received the <strong>Third Prize</strong> in the <strong>2025 "Huihu Youth Innovation" Suzhou Dushu Lake University Student Cultural and Creative Competition</strong>, along with an entrepreneurial seed fund of 50,000 RMB. I received the title of <strong>Excellent Instructor</strong>.</li>
    <li><em>2025.05</em>: &nbsp; I received the <strong>Student-Voted Best Teacher Award</strong> for the academic year 2023-2024! Thanks to all for your wonderful support!</li>
    <li><em>2024.07</em>: &nbsp; Our paper <em>"MapCraft: Dissecting and Designing Custom Geo-Infographics"</em> received the <strong>Honorable Mention</strong> award at <strong>ChinaVis 2024</strong>.</li>
    <li><em>2024.06</em>: &nbsp; Our project <em>"Totem Tales (图腾说)"</em> won the <strong>Second Prize</strong> in the <strong>ChinaVis 2024 Data Challenge Contest</strong>.</li>
  </ul>
</details>

<span class='anchor' id='publications'></span>
<span class='anchor' id='-publications'></span>
# ![paper_420287](https://github.com/user-attachments/assets/457296da-93ad-4669-bf3c-bfbe831df244) Publications 

<div class="filter-panel-container">
  <div class="filter-card filter-card-device">
    <div class="filter-card-header">
      <span class="filter-card-title">📱 Interaction & Devices</span>
      <span class="filter-card-hint">Device Modality</span>
    </div>
    <div class="filter-card-desc">Interactive modalities, wearable systems, and novel display setups</div>
    <div class="filter-card-tags">
      <button class="filter-btn filter-btn-device" data-filter="immersive" onclick="toggleFilter('immersive', '🥽 Immersive XR')">🥽 Immersive XR</button>
      <button class="filter-btn filter-btn-device" data-filter="smartwatch" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</button>
      <button class="filter-btn filter-btn-device" data-filter="multi-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</button>
      <button class="filter-btn filter-btn-device" data-filter="physicalization" onclick="toggleFilter('physicalization', '🧱 Data Physicalization')">🧱 Data Physicalization</button>
      <button class="filter-btn filter-btn-device" data-filter="projection" onclick="toggleFilter('projection', '📽️ Projection Augmented')">📽️ Projection Augmented</button>
    </div>
  </div>

  <div class="filter-card filter-card-theme">
    <div class="filter-card-header">
      <span class="filter-card-title">🎯 Application Domains</span>
      <span class="filter-card-hint">Domain & Theme</span>
    </div>
    <div class="filter-card-desc">Sports & health analytics, digital cultural heritage, and visual design</div>
    <div class="filter-card-tags">
      <button class="filter-btn filter-btn-theme" data-filter="sports" onclick="toggleFilter('sports', '🏃 Sports & Fitness')">🏃 Sports & Fitness</button>
      <button class="filter-btn filter-btn-theme" data-filter="cultural" onclick="toggleFilter('cultural', '🏛️ Cultural Heritage')">🏛️ Cultural Heritage</button>
      <button class="filter-btn filter-btn-theme" data-filter="vis-analytics" onclick="toggleFilter('vis-analytics', '📊 Visual Analytics & Design')">📊 Visual Analytics & Design</button>
    </div>
  </div>
</div>

<div class="filter-status-bar" id="filterStatusBar" style="display:none;">
  <div class="filter-info">
    <span>Active Filter:</span>
    <strong id="currentFilterName" style="color:#111827;"></strong>
    <span style="color:#6b7280;">(<span id="filterCount">0</span> papers found)</span>
  </div>
  <button class="clear-filter-btn" onclick="resetFilter()">Show All Papers ✕</button>
</div>

<div class="pub-subheading">🌟 Featured Highlights</div>

<div class='paper-box' data-tags="immersive cultural">
  <div class='paper-box-image'>
    <div class="teaser-tags-top-left">
      <span class="tag-device-overlay" onclick="toggleFilter('immersive', '🥽 Immersive XR')">🥽 Immersive XR</span>
      <span class="tag-theme-overlay" onclick="toggleFilter('cultural', '🏛️ Cultural Heritage')">🏛️ Cultural Heritage</span>
    </div>
    <div class="teaser-award-top-right">
      <span class="badge-award-overlay">🏆 Honorable Mention</span>
    </div>
    <img src='images/scroll_vr.png' alt="Teaser">
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Exploring the Effects of Narrative Virtual Reality in Traditional Chinese Scroll Paintings</div>
    <div class="paper-authors">Yuanyuan Peng, Yuhan Guo, Yutong Zhou, Suxuan Liu, Jiayu Wang, Jiawen Cai, Yihan Fu, Xiaojiao Chen, <b>Yu Liu</b></div>
    <div class="paper-venue"><em>ACM International Conference on Mobile Human-Computer Interaction (MobileHCI)</em>, 2026.</div>
    <div class="paper-actions">
      <a class="paper-btn" href="https://programs.sigchi.org/mobilehci/2026/program/content/263572" target="_blank">Full Text</a>
      <details class="paper-bibtex">
        <summary class="paper-btn">BibTeX</summary>
        <pre><code>@inproceedings{peng2026exploring,
  title={Exploring the Effects of Narrative Virtual Reality in Traditional Chinese Scroll Paintings},
  author={Peng, Yuanyuan and Guo, Yuhan and Zhou, Yutong and Liu, Suxuan and Wang, Jiayu and Cai, Jiawen and Fu, Yihan and Chen, Xiaojiao and Liu, Yu},
  booktitle={Proceedings of the 28th International Conference on Mobile Human-Computer Interaction (MobileHCI '26)},
  year={2026},
  publisher={ACM}
}</code></pre>
      </details>
    </div>
  </div>
</div>

<div class='paper-box' data-tags="smartwatch sports">
  <div class='paper-box-image'>
    <div class="teaser-tags-top-left">
      <span class="tag-device-overlay" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
      <span class="tag-theme-overlay" onclick="toggleFilter('sports', '🏃 Sports & Fitness')">🏃 Sports & Fitness</span>
    </div>
    <img src='images/movemate.png' alt="Teaser">
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">MoveMate: Supporting Video-Guided Workouts through Motion Visual Analysis and Multi-Device Guidance</div>
    <div class="paper-authors">Yihan Liu, Anqi Xie, Shuheng Hu, Yong Yue, <b>Yu Liu</b></div>
    <div class="paper-venue"><em>ACM International Conference on Mobile Human-Computer Interaction (MobileHCI)</em>, 2026.</div>
    <div class="paper-actions">
      <a class="paper-btn" href="https://programs.sigchi.org/mobilehci/2026/program/content/263573" target="_blank">Full Text</a>
      <details class="paper-bibtex">
        <summary class="paper-btn">BibTeX</summary>
        <pre><code>@inproceedings{liu2026movemate,
  title={MoveMate: Supporting Video-Guided Workouts through Motion Visual Analysis and Multi-Device Guidance},
  author={Liu, Yihan and Xie, Anqi and Hu, Shuheng and Yue, Yong and Liu, Yu},
  booktitle={Proceedings of the 28th International Conference on Mobile Human-Computer Interaction (MobileHCI '26)},
  year={2026},
  publisher={ACM}
}</code></pre>
      </details>
    </div>
  </div>
</div>

<div class="pub-subheading">📚 All Publications</div>

<div class="pub-timeline-container">

  <!-- 2026 Year Section -->
  <div class="timeline-year-section" data-year="2026">
    <div class="timeline-content-col">
      <div class="paper-row" data-tags="smartwatch multi-device">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
          <span class="tag-theme" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">📊 Multi-Device Systems</span>
        </div>
        <div class="paper-title">A Survey on Multi-Device Systems Involving Smartwatches</div>
        <div class="paper-authors">Yihan Liu, Jiazhe Huang, Yuchen Gu, Fabiola Polidoro, Lingyun Yu, <b>Yu Liu</b></div>
        <div class="paper-venue"><em>International Journal of Human–Computer Interaction (IJHCI)</em>, 2026.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://doi.org/10.1080/10447318.2026.2643339" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@article{liu2026survey,
  title={A Survey on Multi-Device Systems Involving Smartwatches},
  author={Liu, Yihan and Huang, Jiazhe and Gu, Yuchen and Polidoro, Fabiola and Yu, Lingyun and Liu, Yu},
  journal={International Journal of Human–Computer Interaction},
  pages={1--32},
  year={2026},
  publisher={Taylor \& Francis},
  doi={10.1080/10447318.2026.2643339}
}</code></pre>
          </details>
        </div>
      </div>
    </div>
    <div class="timeline-spine-col">
      <div class="timeline-year-badge">2026</div>
      <div class="timeline-track-line"></div>
    </div>
  </div>

  <!-- 2025 Year Section -->
  <div class="timeline-year-section" data-year="2025">
    <div class="timeline-content-col">
      <div class="paper-row" data-tags="smartwatch sports">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
          <span class="tag-theme" onclick="toggleFilter('sports', '🏃 Sports & Fitness')">🏃 Sports & Fitness</span>
        </div>
        <div class="paper-title">Comparative Study of Four Visualization Techniques and Positional Variations for Displaying Exercise Data on Smartwatches</div>
        <div class="paper-authors"><b>Yu Liu</b>, Zhouxuan Xia, Jinyuan Du</div>
        <div class="paper-venue"><em>Computer Graphics Forum (CGF)</em>, 2025.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://doi.org/10.1111/cgf.70224" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@article{liu2025comparative,
  title={Comparative Study of Four Visualization Techniques and Positional Variations for Displaying Exercise Data on Smartwatches},
  author={Liu, Yu and Xia, Zhouxuan and Du, Jinyuan},
  journal={Computer Graphics Forum},
  volume={44},
  number={6},
  year={2025},
  publisher={Wiley},
  doi={10.1111/cgf.70224}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="multi-device vis-analytics">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
          <span class="tag-theme" onclick="toggleFilter('vis-analytics', '📊 Visual Analytics & Design')">📊 Collaborative Vis</span>
        </div>
        <div class="paper-title">Evaluating Information Synchronization Methods in Large Display-Centered Multi-Device Collaboration</div>
        <div class="paper-authors">Qiuyao Cheng, Lingyun Yu, <b>Yu Liu</b></div>
        <div class="paper-venue"><em>The China Visualization and Visual Analytics Conference (ChinaVis)</em>, 2025.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://chinavis.org/2025/papers/Evaluating%20Information%20Synchronization%20Methods%20in%20Large%20Display-Centered%20Multi-Device%20Collaboration.pdf" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{cheng2025evaluating,
  title={Evaluating Information Synchronization Methods in Large Display-Centered Multi-Device Collaboration},
  author={Cheng, Qiuyao and Yu, Lingyun and Liu, Yu},
  booktitle={Proceedings of the China Visualization and Visual Analytics Conference (ChinaVis '25)},
  year={2025}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="vis-analytics">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('vis-analytics', '📊 Visual Analytics & Design')">🖥️ Display Interaction</span>
          <span class="tag-theme" onclick="toggleFilter('vis-analytics', '📊 Visual Analytics & Design')">📊 Map Visualization</span>
          <span class="badge-award">🏆 Honorable Mention</span>
        </div>
        <div class="paper-title">Text-Color Hybrid Labeling for Multiclass Map Visualization: A Comparative Evaluation of Four Annotation Strategies</div>
        <div class="paper-authors">Xinyao Chen, Xinyuan Zhang, Teng Ma, Lingyun Yu, <b>Yu Liu</b></div>
        <div class="paper-venue"><em>ACM International Symposium on Visual Information Communication and Interaction (VINCI)</em>, 2025.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://dl.acm.org/doi/10.1145/3769534.3769610" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{chen2025textcolor,
  title={Text-Color Hybrid Labeling for Multiclass Map Visualization: A Comparative Evaluation of Four Annotation Strategies},
  author={Chen, Xinyao and Zhang, Xinyuan and Ma, Teng and Yu, Lingyun and Liu, Yu},
  booktitle={Proceedings of the 18th International Symposium on Visual Information Communication and Interaction (VINCI '25)},
  pages={1--8},
  year={2025},
  publisher={ACM},
  doi={10.1145/3769534.3769610}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="cultural vis-analytics">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Interactive System</span>
          <span class="tag-theme" onclick="toggleFilter('cultural', '🏛️ Cultural Heritage')">🏛️ Cultural Heritage</span>
        </div>
        <div class="paper-title">From Myth to Interface: An AI-Augmented Interactive Visual System for Exploring Artifact Interactions in Journey to the West</div>
        <div class="paper-authors">Zeyu Chen, Anqi Xie, Lingyun Yu, <b>Yu Liu</b></div>
        <div class="paper-venue"><em>ACM International Symposium on Visual Information Communication and Interaction (VINCI)</em>, 2025.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://dl.acm.org/doi/10.1145/3769534.3769615" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{chen2025myth,
  title={From Myth to Interface: An AI-Augmented Interactive Visual System for Exploring Artifact Interactions in Journey to the West},
  author={Chen, Zeyu and Xie, Anqi and Yu, Lingyun and Liu, Yu},
  booktitle={Proceedings of the 18th International Symposium on Visual Information Communication and Interaction (VINCI '25)},
  pages={1--8},
  year={2025},
  publisher={ACM},
  doi={10.1145/3769534.3769615}
}</code></pre>
          </details>
        </div>
      </div>
    </div>
    <div class="timeline-spine-col">
      <div class="timeline-year-badge">2025</div>
      <div class="timeline-track-line"></div>
    </div>
  </div>

  <!-- 2024 Year Section -->
  <div class="timeline-year-section" data-year="2024">
    <div class="timeline-content-col">
      <div class="paper-row" data-tags="vis-analytics">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('vis-analytics', '📊 Visual Analytics & Design')">🖥️ Visual Design</span>
          <span class="tag-theme" onclick="toggleFilter('vis-analytics', '📊 Visual Analytics & Design')">📊 Geo-Infographics</span>
          <span class="badge-award">🏆 Honorable Mention</span>
        </div>
        <div class="paper-title">MapCraft: Dissecting and Designing Custom Geo-Infographics</div>
        <div class="paper-authors">Xinyuan Zhang, Yifan Xu, Kaiwen Li, Lingyun Yu, <b>Yu Liu</b></div>
        <div class="paper-venue"><em>ChinaVis 2024 / Journal of Visualization</em>, 2024.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://arxiv.org/abs/2409.13424" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@article{zhang2024mapcraft,
  title={MapCraft: Dissecting and Designing Custom Geo-Infographics},
  author={Zhang, Xinyuan and Xu, Yifan and Li, Kaiwen and Yu, Lingyun and Liu, Yu},
  journal={Journal of Visualization},
  year={2024},
  doi={10.1007/s12650-024-01048-w}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="physicalization vis-analytics">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('physicalization', '🧱 Data Physicalization')">🧱 Data Physicalization</span>
          <span class="tag-theme" onclick="toggleFilter('vis-analytics', '📊 Visual Analytics & Design')">📊 Comparative Evaluation</span>
        </div>
        <div class="paper-title">A Comparative Study of Table-Sized Physicalization and Digital Visualization</div>
        <div class="paper-authors">Yanxin Wang, Yihan Liu, Lingyun Yu, Chengtao Ji, <b>Yu Liu</b></div>
        <div class="paper-venue"><em>ChinaVis 2024 / Journal of Visualization</em>, 2024.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://arxiv.org/abs/2409.06951" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@article{wang2024comparative,
  title={A Comparative Study of Table-Sized Physicalization and Digital Visualization},
  author={Wang, Yanxin and Liu, Yihan and Yu, Lingyun and Ji, Chengtao and Liu, Yu},
  journal={Journal of Visualization},
  year={2024},
  doi={10.1007/s12650-024-01042-2}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="smartwatch multi-device">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
          <span class="tag-theme" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">📊 Cross-Device Interaction</span>
        </div>
        <div class="paper-title">Enhancing Mobile Interaction: Practical Insights from Smartphone and Smartwatch Integration</div>
        <div class="paper-authors">Qiuyao Cheng, Xuanyao Tian, Fengyuan Liao, Tan Chen, Xinyao Chen, Zixuan Wang, Yutong Dong, <b>Yu Liu</b></div>
        <div class="paper-venue"><em>ACM International Conference on Mobile Human-Computer Interaction (MobileHCI)</em>, 2024.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://dl.acm.org/doi/10.1145/3640471.3680451" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{cheng2024enhancing,
  title={Enhancing Mobile Interaction: Practical Insights from Smartphone and Smartwatch Integration},
  author={Cheng, Qiuyao and Tian, Xuanyao and Liao, Fengyuan and Chen, Tan and Chen, Xinyao and Wang, Zixuan and Dong, Yutong and Liu, Yu},
  booktitle={Adjunct Proceedings of the 26th International Conference on Mobile Human-Computer Interaction (MobileHCI '24)},
  pages={1--7},
  year={2024},
  doi={10.1145/3640471.3680451}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="projection vis-analytics">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('projection', '📽️ Projection Augmented')">📽️ Projection Augmented</span>
          <span class="tag-theme" onclick="toggleFilter('vis-analytics', '📊 Visual Analytics & Design')">📊 Geographic Vis</span>
        </div>
        <div class="paper-title">Enhancing Geographic Information Visualization: A Comparative Analysis of Digital Maps and Projection Augmented Relief Maps</div>
        <div class="paper-authors">Changyuanlang Teng, Zhiwei Shi, Lingyun Yu, <b>Yu Liu</b></div>
        <div class="paper-venue"><em>International Workshop on Big Spatial Data and Visualization (BigVis)</em>, 2024.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://bigvis.imsi.athenarc.gr/bigvis2024/cfp.html" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{teng2024enhancing,
  title={Enhancing Geographic Information Visualization: A Comparative Analysis of Digital Maps and Projection Augmented Relief Maps},
  author={Teng, Changyuanlang and Shi, Zhiwei and Yu, Lingyun and Liu, Yu},
  booktitle={International Workshop on Big Spatial Data and Visualization (BigVis '24)},
  year={2024}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="immersive vis-analytics">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('immersive', '🥽 Immersive XR')">🥽 Immersive XR</span>
          <span class="tag-theme" onclick="toggleFilter('vis-analytics', '📊 Visual Analytics & Design')">📊 Data Exploration</span>
        </div>
        <div class="paper-title">Exploring Embodied Asymmetric Two-Handed Interactions for Immersive Data Exploration</div>
        <div class="paper-authors">Haonan Yao, Lixiang Zhao, Hai-Ning Liang, <b>Yu Liu</b>, Yue Li, Lingyun Yu</div>
        <div class="paper-venue"><em>ACM Conference on Human Factors in Computing Systems (CHI Extended Abstracts)</em>, 2024.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://dl.acm.org/doi/10.1145/3613905.3650956" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{yao2024exploring,
  title={Exploring Embodied Asymmetric Two-Handed Interactions for Immersive Data Exploration},
  author={Yao, Haonan and Zhao, Lixiang and Liang, Hai-Ning and Liu, Yu and Li, Yue and Yu, Lingyun},
  booktitle={Extended Abstracts of the 2024 CHI Conference on Human Factors in Computing Systems (CHI EA '24)},
  pages={1--7},
  year={2024},
  doi={10.1145/3613905.3650956}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="smartwatch vis-analytics">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
          <span class="tag-theme" onclick="toggleFilter('vis-analytics', '📊 Visual Analytics & Design')">📊 Prototyping Approach</span>
        </div>
        <div class="paper-title">Enhancing Mobile Visualisation Interactivity: Insights on a Mixed-fidelity Prototyping Approach</div>
        <div class="paper-authors">Fabiola Polidoro, <b>Yu Liu</b>, Paul Craig</div>
        <div class="paper-venue"><em>ACM Conference on Human Factors in Computing Systems (CHI Extended Abstracts)</em>, 2024.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://dl.acm.org/doi/10.1145/3613905.3650949" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{polidoro2024enhancing,
  title={Enhancing Mobile Visualisation Interactivity: Insights on a Mixed-fidelity Prototyping Approach},
  author={Polidoro, Fabiola and Liu, Yu and Craig, Paul},
  booktitle={Extended Abstracts of the 2024 CHI Conference on Human Factors in Computing Systems (CHI EA '24)},
  pages={1--7},
  year={2024},
  doi={10.1145/3613905.3650949}
}</code></pre>
          </details>
        </div>
      </div>
    </div>
    <div class="timeline-spine-col">
      <div class="timeline-year-badge">2024</div>
      <div class="timeline-track-line"></div>
    </div>
  </div>

</div>

<script>
function toggleFilter(tag, label) {
  var activeBtn = document.querySelector('.filter-btn[data-filter="' + tag + '"]');
  var isAlreadyActive = activeBtn && activeBtn.classList.contains('active');
  if (isAlreadyActive) {
    resetFilter();
  } else {
    filterPubs(tag, label);
  }
}

function filterPubs(tag, label) {
  document.querySelectorAll('.filter-btn').forEach(function(btn) {
    if (btn.getAttribute('data-filter') === tag) {
      btn.classList.add('active');
    } else {
      btn.classList.remove('active');
    }
  });

  var statusBar = document.getElementById('filterStatusBar');
  var currentName = document.getElementById('currentFilterName');
  var countSpan = document.getElementById('filterCount');
  if (statusBar) statusBar.style.display = 'flex';
  if (currentName) currentName.textContent = label;

  var matchCount = 0;

  document.querySelectorAll('.paper-box').forEach(function(card) {
    var tags = (card.getAttribute('data-tags') || '').split(' ');
    var match = tags.indexOf(tag) !== -1;
    card.style.display = match ? 'flex' : 'none';
    if (match) matchCount++;
  });

  document.querySelectorAll('.paper-row').forEach(function(row) {
    var tags = (row.getAttribute('data-tags') || '').split(' ');
    var match = tags.indexOf(tag) !== -1;
    row.style.display = match ? 'block' : 'none';
    if (match) matchCount++;
  });

  if (countSpan) countSpan.textContent = matchCount;

  // Toggle year section visibility based on whether it has visible papers
  document.querySelectorAll('.timeline-year-section').forEach(function(section) {
    var hasVisible = false;
    section.querySelectorAll('.paper-row').forEach(function(row) {
      if (row.style.display !== 'none') {
        hasVisible = true;
      }
    });
    section.style.display = hasVisible ? 'grid' : 'none';
  });

  if (statusBar) {
    statusBar.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
  }
}

function resetFilter() {
  document.querySelectorAll('.filter-btn').forEach(function(btn) {
    btn.classList.remove('active');
  });
  var statusBar = document.getElementById('filterStatusBar');
  if (statusBar) statusBar.style.display = 'none';

  document.querySelectorAll('.paper-box').forEach(function(card) {
    card.style.display = 'flex';
  });
  document.querySelectorAll('.paper-row').forEach(function(row) {
    row.style.display = 'block';
  });
  document.querySelectorAll('.timeline-year-section').forEach(function(section) {
    section.style.display = 'grid';
  });
}
</script>

<span class='anchor' id='teaching'></span>
<span class='anchor' id='-teaching'></span>
# ![teaching](https://github.com/user-attachments/assets/20e43195-f4c2-4b65-95a2-2c57a358de63) Teaching
- CPT001 Professional Skills in Computer Science
- CPT003 Introduction to Database


<span class='anchor' id='student-competitions'></span>
<span class='anchor' id='-honors-and-awards'></span>
# ![gong_3420372](https://github.com/user-attachments/assets/f495385b-4699-4c6b-b935-d71fc3e3052d) Student Competitions
- *2026.06* ChinaVis Data Challenge Contest, Third Prize.
- *2024.06* ChinaVis Data Challenge Contest, Second Prize.
- *2023.06* ChinaVis Data Challenge Contest, First Prize.
- *2022.06* ChinaVis Data Challenge Contest, Second Prize.
- *2021.06* ChinaVis Data Challenge Contest, Merit Prize (优秀奖). 



<span class='anchor' id='educations'></span>
<span class='anchor' id='-educations'></span>
# ![global-education_3379870](https://github.com/user-attachments/assets/1ffecb0d-2ef9-4507-9815-6d66c19d6726) Educations
- *2018.02 - 2022.06*, Ph.D. Computer Science, University of Liverpool (UoL). 
- *2016.09 - 2017.12*, MSc. Design for Informatics, University of Edinburgh (UoE).
- *2012.09 - 2016.06*, BSc. Computer Science and Software Engineering. Taiyuan University of Technology (TYUT).

<span class='anchor' id='invited-talks'></span>
<span class='anchor' id='-invited-talks'></span>
# ![teacher_1115729](https://github.com/user-attachments/assets/1152abf1-9e5a-467b-9a7a-9686709e4427) Invited Talks
- *2023.04*, 2023 China-Japan-South Korea Visualization Forum, Seoul, Korea.

<span class='anchor' id='service'></span>
<span class='anchor' id='-service'></span>
# ![studying_16493824](https://github.com/user-attachments/assets/d3738a87-6ca4-45eb-af0f-32482cfbf07d) Service
Reviewer of IEEE VIS, ACM MobileHCI, CSCW, IJHCI, ISS, IEEE VR, ISMAR, PacificVis, ChinaVis, VINCI etc.

<span class='anchor' id='internships'></span>
<span class='anchor' id='-internships'></span>
# ![identification_16269807](https://github.com/user-attachments/assets/17932ed8-0177-4e37-ab5a-070e73a9e0e4) Internships
- *2021.12 - 2022.06*, Visualization Designer, [Bytedance](https://www.bytedance.com/en/), Beijing, China.

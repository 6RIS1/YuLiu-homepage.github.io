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
# <span class="heading-icon-badge">📰</span> News
- *2026.08*: &nbsp; Two papers were accepted to **ACM MobileHCI 2026**! Notably, *"Exploring the Effects of Narrative Virtual Reality in Traditional Chinese Scroll Paintings"* received the **Honorable Mention** award. The second paper is *"MoveMate: Supporting Video-Guided Workouts through Motion Visual Analysis and Multi-Device Guidance"*.
- *2025.12*: &nbsp; Two papers were accepted to **ACM VINCI 2025**! Notably, *"Text-Color Hybrid Labeling for Multiclass Map Visualization: A Comparative Evaluation of Four Annotation Strategies"* received the **Honorable Mention** award. The second paper is *"From Myth to Interface: An AI-Augmented Interactive Visual System for Exploring Artifact Interactions in Journey to the West"*.

<details class="news-archive">
  <summary class="news-toggle-btn"><span>View More News (5)</span> <span class="toggle-arrow">▾</span></summary>
  <ul class="news-archive-list">
    <li><em>2025.06</em>: &nbsp; Our project <em>"ARthroMap (画游姑苏)"</em> received the <strong>Third Prize</strong> in the <strong>2025 "Huihu Youth Innovation" Suzhou Dushu Lake University Student Cultural and Creative Competition</strong>, along with an entrepreneurial seed fund of 50,000 RMB. I received the title of <strong>Excellent Instructor</strong>.</li>
    <li><em>2025.05</em>: &nbsp; I received the <strong>Student-Voted Best Teacher Award</strong> for the academic year 2023-2024! Thanks to all for your wonderful support!</li>
    <li><em>2024.07</em>: &nbsp; Our paper <em>"MapCraft: Dissecting and Designing Custom Geo-Infographics"</em> received the <strong>Honorable Mention</strong> award at <strong>ChinaVis 2024</strong>.</li>
    <li><em>2024.06</em>: &nbsp; Our project <em>"Totem Tales (图腾说)"</em> won the <strong>Second Prize</strong> in the <strong>ChinaVis 2024 Data Challenge Contest</strong>.</li>
    <li><em>2023.09</em>: &nbsp; Our paper <em>"EmotionVis: Affective Visualization with Physical Devices"</em> received the <strong>Best Short Paper</strong> award at <strong>ACM VINCI 2023</strong>.</li>
  </ul>
</details>

<span class='anchor' id='publications'></span>
<span class='anchor' id='-publications'></span>
# <span class="heading-icon-badge">📄</span> Publications 

<div class="filter-panel-container">
  <div class="filter-card filter-card-device">
    <div class="filter-card-header">
      <span class="filter-card-title"><span class="subheading-icon-badge">📱</span> Interaction & Devices</span>
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
      <span class="filter-card-title"><span class="subheading-icon-badge" style="background:#edf4f8; border-color:#b7d2e3;">🎯</span> Application Domains</span>
      <span class="filter-card-hint">Domain & Theme</span>
    </div>
    <div class="filter-card-desc">Real-world applications in cultural heritage, sports, and cartography</div>
    <div class="filter-card-tags">
      <button class="filter-btn filter-btn-theme" data-filter="cultural" onclick="toggleFilter('cultural', '🏛️ Cultural Heritage')">🏛️ Cultural Heritage</button>
      <button class="filter-btn filter-btn-theme" data-filter="sports" onclick="toggleFilter('sports', '🏃 Sports & Fitness')">🏃 Sports & Fitness</button>
      <button class="filter-btn filter-btn-theme" data-filter="maps" onclick="toggleFilter('maps', '🗺️ Cartography & Maps')">🗺️ Cartography & Maps</button>
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

<div class="pub-timeline-container">

  <!-- 2026 Year Section -->
  <div class="timeline-year-section" data-year="2026">
    <div class="timeline-content-col">
      <div class="paper-row has-teaser" data-tags="immersive cultural">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('immersive', '🥽 Immersive XR')">🥽 Immersive XR</span>
            <span class="tag-theme" onclick="toggleFilter('cultural', '🏛️ Cultural Heritage')">🏛️ Cultural Heritage</span>
            <span class="badge-award">🏆 Honorable Mention</span>
          </div>
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
        <div class="paper-row-teaser">
          <a href="images/scroll_vr.png" class="image-popup" title="Click to enlarge"><img src="images/scroll_vr.png" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="smartwatch sports">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
            <span class="tag-theme" onclick="toggleFilter('sports', '🏃 Sports & Fitness')">🏃 Sports & Fitness</span>
          </div>
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
        <div class="paper-row-teaser">
          <a href="images/movemate.png" class="image-popup" title="Click to enlarge"><img src="images/movemate.png" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="smartwatch multi-device">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
            <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
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
  publisher={Taylor & Francis},
  doi={10.1080/10447318.2026.2643339}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/multidevice_survey.jpg" class="image-popup" title="Click to enlarge"><img src="images/multidevice_survey.jpg" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="multi-device">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
          </div>
          <div class="paper-title">NFTSpot: Visualizing Price Patterns and Investment Opportunities in NFTs</div>
          <div class="paper-authors"><b>Yu Liu</b>, Ruiqi Chen, Teng Ma</div>
          <div class="paper-venue"><em>2026 29th International Conference on Computer Supported Cooperative Work in Design (CSCWD)</em>, 2026.</div>
          <div class="paper-actions">
            <a class="paper-btn" href="https://ieeexplore.ieee.org/document/11582077/" target="_blank">Full Text</a>
            <details class="paper-bibtex">
              <summary class="paper-btn">BibTeX</summary>
              <pre><code>@inproceedings{liu2026nftspot,
  title={NFTSpot: Visualizing Price Patterns and Investment Opportunities in NFTs},
  author={Liu, Yu and Chen, Ruiqi and Ma, Teng},
  booktitle={2026 29th International Conference on Computer Supported Cooperative Work in Design (CSCWD)},
  year={2026},
  publisher={IEEE}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/nftspot.png" class="image-popup" title="Click to enlarge"><img src="images/nftspot.png" alt="Teaser"></a>
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
      <div class="paper-row has-teaser" data-tags="smartwatch sports">
        <div class="paper-row-main">
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
        <div class="paper-row-teaser">
          <a href="images/smartwatch_cgf.png" class="image-popup" title="Click to enlarge"><img src="images/smartwatch_cgf.png" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="smartwatch sports">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
            <span class="tag-theme" onclick="toggleFilter('sports', '🏃 Sports & Fitness')">🏃 Sports & Fitness</span>
          </div>
          <div class="paper-title">Visualizing on the Wrist: Impact of Motion, Dial Shape and Visualization Type on Smartwatch</div>
          <div class="paper-authors">Zhouxuan Xia, Fengyuan Liao, Jinyuan Du, <b>Yu Liu</b></div>
          <div class="paper-venue"><em>2025 IEEE Visualization and Visual Analytics (VIS)</em>, 2025.</div>
          <div class="paper-actions">
            <a class="paper-btn" href="https://ieeexplore.ieee.org/document/11298834/" target="_blank">Full Text</a>
            <details class="paper-bibtex">
              <summary class="paper-btn">BibTeX</summary>
              <pre><code>@inproceedings{xia2025visualizing,
  title={Visualizing on the Wrist: Impact of Motion, Dial Shape and Visualization Type on Smartwatch},
  author={Xia, Zhouxuan and Liao, Fengyuan and Du, Jinyuan and Liu, Yu},
  booktitle={2025 IEEE Visualization and Visual Analytics (VIS)},
  year={2025},
  publisher={IEEE}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/visualizing_wrist.png" class="image-popup" title="Click to enlarge"><img src="images/visualizing_wrist.png" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="multi-device">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
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
  booktitle={The China Visualization and Visual Analytics Conference (ChinaVis 2025)},
  year={2025}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/large_display_sync.png" class="image-popup" title="Click to enlarge"><img src="images/large_display_sync.png" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="maps">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-theme" onclick="toggleFilter('maps', '🗺️ Cartography & Maps')">🗺️ Cartography & Maps</span>
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
  year={2025},
  publisher={ACM},
  doi={10.1145/3769534.3769610}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/tagmap.png" class="image-popup" title="Click to enlarge"><img src="images/tagmap.png" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="cultural">
        <div class="paper-row-main">
          <div class="paper-row-tags">
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
  year={2025},
  publisher={ACM},
  doi={10.1145/3769534.3769615}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/journey_west.png" class="image-popup" title="Click to enlarge"><img src="images/journey_west.png" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="physicalization">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('physicalization', '🧱 Data Physicalization')">🧱 Data Physicalization</span>
          </div>
          <div class="paper-title">A Comparative Study of Table-Sized Physicalization and Digital Visualization</div>
          <div class="paper-authors">Yanxin Wang, Yihan Liu, Lingyun Yu, Chengtao Ji, <b>Yu Liu</b></div>
          <div class="paper-venue"><em>Journal of Visualization</em>, 2025.</div>
          <div class="paper-actions">
            <a class="paper-btn" href="https://doi.org/10.1007/s12650-025-01056-7" target="_blank">Full Text</a>
            <details class="paper-bibtex">
              <summary class="paper-btn">BibTeX</summary>
              <pre><code>@article{wang2025comparative,
  title={A Comparative Study of Table-Sized Physicalization and Digital Visualization},
  author={Wang, Yanxin and Liu, Yihan and Yu, Lingyun and Ji, Chengtao and Liu, Yu},
  journal={Journal of Visualization},
  year={2025},
  publisher={Springer},
  doi={10.1007/s12650-025-01056-7}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/Physicalization.png" class="image-popup" title="Click to enlarge"><img src="images/Physicalization.png" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="maps">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-theme" onclick="toggleFilter('maps', '🗺️ Cartography & Maps')">🗺️ Cartography & Maps</span>
            <span class="badge-award">🏆 Honorable Mention</span>
          </div>
          <div class="paper-title">MapCraft: Dissecting and Designing Custom Geo-Infographics</div>
          <div class="paper-authors">Xinyuan Zhang, Yifan Xu, Kaiwen Li, Lingyun Yu, <b>Yu Liu</b></div>
          <div class="paper-venue"><em>Journal of Visualization and ChinaVis</em>, 2024.</div>
          <div class="paper-actions">
            <a class="paper-btn" href="https://doi.org/10.1007/s12650-025-01059-4" target="_blank">Full Text</a>
            <details class="paper-bibtex">
              <summary class="paper-btn">BibTeX</summary>
              <pre><code>@article{zhang2025mapcraft,
  title={MapCraft: Dissecting and Designing Custom Geo-Infographics},
  author={Zhang, Xinyuan and Xu, Yifan and Li, Kaiwen and Yu, Lingyun and Liu, Yu},
  journal={Journal of Visualization},
  year={2025},
  publisher={Springer},
  doi={10.1007/s12650-025-01059-4}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/MapCraft.png" class="image-popup" title="Click to enlarge"><img src="images/MapCraft.png" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row" data-tags="cultural">
        <div class="paper-row-tags">
          <span class="tag-theme" onclick="toggleFilter('cultural', '🏛️ Cultural Heritage')">🏛️ Cultural Heritage</span>
        </div>
        <div class="paper-title">Jinling Fenghua: Unfolding Cultural History of the Jinling Context via Visual Storytelling</div>
        <div class="paper-authors">Anqi Xie, Yejuan Xie, <b>Yu Liu</b>, Lingyun Yu, Lijie Yao, Chengtao Ji</div>
        <div class="paper-venue"><em>2025 28th International Conference on Computer Supported Cooperative Work in Design (CSCWD)</em>, 2025.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://ieeexplore.ieee.org/document/11033436/" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{xie2025jinling,
  title={Jinling Fenghua: Unfolding Cultural History of the Jinling Context via Visual Storytelling},
  author={Xie, Anqi and Xie, Yejuan and Liu, Yu and Yu, Lingyun and Yao, Lijie and Ji, Chengtao},
  booktitle={2025 28th International Conference on Computer Supported Cooperative Work in Design (CSCWD)},
  year={2025},
  publisher={IEEE}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="smartwatch">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
          </div>
          <div class="paper-title">Nutrition Labels for Aging Eyes: Redesigning for Better Health Decisions</div>
          <div class="paper-authors">Wenya Qin, Ruiqi Chen, Yihan Liu, <b>Yu Liu</b></div>
          <div class="paper-venue"><em>2025 IEEE Smart World Congress (SWC)</em>, 2025.</div>
          <div class="paper-actions">
            <a class="paper-btn" href="https://ieeexplore.ieee.org/document/11394982/" target="_blank">Full Text</a>
            <details class="paper-bibtex">
              <summary class="paper-btn">BibTeX</summary>
              <pre><code>@inproceedings{qin2025nutrition,
  title={Nutrition Labels for Aging Eyes: Redesigning for Better Health Decisions},
  author={Qin, Wenya and Chen, Ruiqi and Liu, Yihan and Liu, Yu},
  booktitle={2025 IEEE Smart World Congress (SWC)},
  year={2025},
  publisher={IEEE}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/nutrition_labels.png" class="image-popup" title="Click to enlarge"><img src="images/nutrition_labels.png" alt="Teaser"></a>
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
      <div class="paper-row" data-tags="immersive">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('immersive', '🥽 Immersive XR')">🥽 Immersive XR</span>
        </div>
        <div class="paper-title">Experimental Analysis of Freehand Multi-object Selection Techniques in Virtual Reality Head-Mounted Displays</div>
        <div class="paper-authors">Rongkai Shi, Yawen Wei, Xiaoxuan Hu, <b>Yu Liu</b>, Yong Yue, Lingyun Yu, Hai-Ning Liang</div>
        <div class="paper-venue"><em>Proceedings of the ACM on Human-Computer Interaction (PACMHCI)</em>, ISS, 2024.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://dl.acm.org/doi/10.1145/3698129" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@article{shi2024experimental,
  title={Experimental Analysis of Freehand Multi-object Selection Techniques in Virtual Reality Head-Mounted Displays},
  author={Shi, Rongkai and Wei, Yawen and Hu, Xiaoxuan and Liu, Yu and Yue, Yong and Yu, Lingyun and Liang, Hai-Ning},
  journal={Proceedings of the ACM on Human-Computer Interaction},
  volume={8},
  number={ISS},
  pages={1--26},
  year={2024},
  publisher={ACM},
  doi={10.1145/3698129}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="smartwatch sports">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
          <span class="tag-theme" onclick="toggleFilter('sports', '🏃 Sports & Fitness')">🏃 Sports & Fitness</span>
        </div>
        <div class="paper-title">A Survey on Activity Visualization for Smartwatches</div>
        <div class="paper-authors">Zhouxuan Xia, <b>Yu Liu</b>, Fabiola Polidoro</div>
        <div class="paper-venue"><em>The 16th IEEE Pacific Visualization Symposium (PacificVis)</em>, 2024.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://ieeexplore.ieee.org/abstract/document/10543666" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{xia2024survey,
  title={A Survey on Activity Visualization for Smartwatches},
  author={Xia, Zhouxuan and Liu, Yu and Polidoro, Fabiola},
  booktitle={2024 IEEE 16th Pacific Visualization Symposium (PacificVis)},
  pages={1--10},
  year={2024},
  publisher={IEEE}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="smartwatch multi-device">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
            <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
          </div>
          <div class="paper-title">Enhancing Mobile Interaction: Practical Insights from Smartphone and Smartwatch Integration</div>
          <div class="paper-authors">Qiuyao Cheng, Xuanyao Tian, Fengyuan Liao, Tan Chen, Xinyao Chen, Zixuan Wang, <b>Yu Liu</b></div>
          <div class="paper-venue"><em>ACM International Conference on Mobile Human-Computer Interaction (MobileHCI)</em>, 2024.</div>
          <div class="paper-actions">
            <a class="paper-btn" href="https://dl.acm.org/doi/10.1145/3640471.3680451" target="_blank">Full Text</a>
            <details class="paper-bibtex">
              <summary class="paper-btn">BibTeX</summary>
              <pre><code>@inproceedings{cheng2024enhancing,
  title={Enhancing Mobile Interaction: Practical Insights from Smartphone and Smartwatch Integration},
  author={Cheng, Qiuyao and Tian, Xuanyao and Liao, Fengyuan and Chen, Tan and Chen, Xinyao and Wang, Zixuan and Liu, Yu},
  booktitle={Proceedings of the 26th International Conference on Mobile Human-Computer Interaction (MobileHCI '24)},
  year={2024},
  publisher={ACM},
  doi={10.1145/3640471.3680451}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/mobiles.png" class="image-popup" title="Click to enlarge"><img src="images/mobiles.png" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="multi-device">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
          </div>
          <div class="paper-title">CHORDination: Evaluating Visual Design Choices in Chord Diagrams for Network Data</div>
          <div class="paper-authors">Kexin Wang, Shuqi He, Wei Wang, Jiazhou Yu, <b>Yu Liu</b>, Lingyun Yu</div>
          <div class="paper-venue"><em>ACM International Symposium on Visual Information Communication and Interaction (VINCI)</em>, 2024.</div>
          <div class="paper-actions">
            <a class="paper-btn" href="https://dl.acm.org/doi/10.1145/3678698.3678707" target="_blank">Full Text</a>
            <details class="paper-bibtex">
              <summary class="paper-btn">BibTeX</summary>
              <pre><code>@inproceedings{wang2024chordination,
  title={CHORDination: Evaluating Visual Design Choices in Chord Diagrams for Network Data},
  author={Wang, Kexin and He, Shuqi and Wang, Wei and Yu, Jiazhou and Liu, Yu and Yu, Lingyun},
  booktitle={Proceedings of the 17th International Symposium on Visual Information Communication and Interaction (VINCI '24)},
  year={2024},
  publisher={ACM},
  doi={10.1145/3678698.3678707}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/chordination.jpg" class="image-popup" title="Click to enlarge"><img src="images/chordination.jpg" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="projection maps">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('projection', '📽️ Projection Augmented')">📽️ Projection Augmented</span>
            <span class="tag-theme" onclick="toggleFilter('maps', '🗺️ Cartography & Maps')">🗺️ Cartography & Maps</span>
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
        <div class="paper-row-teaser">
          <a href="images/Projectedmap.png" class="image-popup" title="Click to enlarge"><img src="images/Projectedmap.png" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="immersive">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('immersive', '🥽 Immersive XR')">🥽 Immersive XR</span>
          </div>
          <div class="paper-title">Exploring Embodied Asymmetric Two-Handed Interactions for Immersive Data Exploration</div>
          <div class="paper-authors">Haonan Yao, Lixiang Zhao, Hai-Ning Liang, <b>Yu Liu</b>, Yue Li, Lingyun Yu</div>
          <div class="paper-venue"><em>Extended Abstracts of the CHI Conference on Human Factors in Computing Systems (CHI EA)</em>, 2024.</div>
          <div class="paper-actions">
            <a class="paper-btn" href="https://dl.acm.org/doi/10.1145/3613905.3650777" target="_blank">Full Text</a>
            <details class="paper-bibtex">
              <summary class="paper-btn">BibTeX</summary>
              <pre><code>@inproceedings{yao2024exploring,
  title={Exploring Embodied Asymmetric Two-Handed Interactions for Immersive Data Exploration},
  author={Yao, Haonan and Zhao, Lixiang and Liang, Hai-Ning and Liu, Yu and Li, Yue and Yu, Lingyun},
  booktitle={Extended Abstracts of the CHI Conference on Human Factors in Computing Systems (CHI EA '24)},
  year={2024},
  publisher={ACM},
  doi={10.1145/3613905.3650777}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/two_handed_vr.jpg" class="image-popup" title="Click to enlarge"><img src="images/two_handed_vr.jpg" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row has-teaser" data-tags="smartwatch">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
          </div>
          <div class="paper-title">Enhancing Mobile Visualisation Interactivity: Insights on a Mixed-fidelity Prototyping Approach</div>
          <div class="paper-authors">Fabiola Polidoro, <b>Yu Liu</b>, Paul Craig</div>
          <div class="paper-venue"><em>Extended Abstracts of the CHI Conference on Human Factors in Computing Systems (CHI EA)</em>, 2024.</div>
          <div class="paper-actions">
            <a class="paper-btn" href="https://dl.acm.org/doi/10.1145/3613905.3650994" target="_blank">Full Text</a>
            <details class="paper-bibtex">
              <summary class="paper-btn">BibTeX</summary>
              <pre><code>@inproceedings{polidoro2024enhancing,
  title={Enhancing Mobile Visualisation Interactivity: Insights on a Mixed-fidelity Prototyping Approach},
  author={Polidoro, Fabiola and Liu, Yu and Craig, Paul},
  booktitle={Extended Abstracts of the CHI Conference on Human Factors in Computing Systems (CHI EA '24)},
  year={2024},
  publisher={ACM},
  doi={10.1145/3613905.3650994}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/sketch_a_touch.jpg" class="image-popup" title="Click to enlarge"><img src="images/sketch_a_touch.jpg" alt="Teaser"></a>
        </div>
      </div>
    </div>
    <div class="timeline-spine-col">
      <div class="timeline-year-badge">2024</div>
      <div class="timeline-track-line"></div>
    </div>
  </div>

  <!-- 2023 Year Section -->
  <div class="timeline-year-section" data-year="2023">
    <div class="timeline-content-col">
      <div class="paper-row has-teaser" data-tags="immersive">
        <div class="paper-row-main">
          <div class="paper-row-tags">
            <span class="tag-device" onclick="toggleFilter('immersive', '🥽 Immersive XR')">🥽 Immersive XR</span>
          </div>
          <div class="paper-title">MEinVR: Multimodal Interaction Techniques in Immersive Exploration</div>
          <div class="paper-authors">Ziyue Yuan, Shuqi He, <b>Yu Liu</b>, Lingyun Yu</div>
          <div class="paper-venue"><em>Visual Informatics</em>, 2023.</div>
          <div class="paper-actions">
            <a class="paper-btn" href="https://doi.org/10.1016/j.visinf.2023.06.001" target="_blank">Full Text</a>
            <details class="paper-bibtex">
              <summary class="paper-btn">BibTeX</summary>
              <pre><code>@article{yuan2023meinvr,
  title={MEinVR: Multimodal Interaction Techniques in Immersive Exploration},
  author={Yuan, Ziyue and He, Shuqi and Liu, Yu and Yu, Lingyun},
  journal={Visual Informatics},
  volume={7},
  number={3},
  pages={37--48},
  year={2023},
  publisher={Elsevier},
  doi={10.1016/j.visinf.2023.06.001}
}</code></pre>
            </details>
          </div>
        </div>
        <div class="paper-row-teaser">
          <a href="images/meinvr.jpg" class="image-popup" title="Click to enlarge"><img src="images/meinvr.jpg" alt="Teaser"></a>
        </div>
      </div>

      <div class="paper-row" data-tags="physicalization">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('physicalization', '🧱 Data Physicalization')">🧱 Data Physicalization</span>
        </div>
        <div class="paper-title">TangibleChannel: An Innovative Data Physicalization System for Visual Channel Education</div>
        <div class="paper-authors">Siqi Xie, <b>Yu Liu</b>, Lingyun Yu</div>
        <div class="paper-venue"><em>IEEE Visualization and Visual Analytics (VIS)</em>, 2023.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://ieeexplore.ieee.org/document/10322194/" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{xie2023tangiblechannel,
  title={TangibleChannel: An Innovative Data Physicalization System for Visual Channel Education},
  author={Xie, Siqi and Liu, Yu and Yu, Lingyun},
  booktitle={2023 IEEE Visualization and Visual Analytics (VIS)},
  year={2023},
  publisher={IEEE}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="immersive cultural">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('immersive', '🥽 Immersive XR')">🥽 Immersive XR</span>
          <span class="tag-theme" onclick="toggleFilter('cultural', '🏛️ Cultural Heritage')">🏛️ Cultural Heritage</span>
        </div>
        <div class="paper-title">TimeQuestAR: Unfolding Cultural Narratives via Situated Visualizations</div>
        <div class="paper-authors">Nan Xu, <b>Yu Liu</b>, Zhaoxin Zhang, Lingyun Yu</div>
        <div class="paper-venue"><em>2023 IEEE International Symposium on Mixed and Augmented Reality Adjunct (ISMAR-Adjunct)</em>, 2023.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://ieeexplore.ieee.org/document/10316410/" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{xu2023timequestar,
  title={TimeQuestAR: Unfolding Cultural Narratives via Situated Visualizations},
  author={Xu, Nan and Liu, Yu and Zhang, Zhaoxin and Yu, Lingyun},
  booktitle={2023 IEEE International Symposium on Mixed and Augmented Reality Adjunct (ISMAR-Adjunct)},
  pages={1--6},
  year={2023},
  publisher={IEEE}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="maps multi-device">
        <div class="paper-row-tags">
          <span class="tag-theme" onclick="toggleFilter('maps', '🗺️ Cartography & Maps')">🗺️ Cartography & Maps</span>
          <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
        </div>
        <div class="paper-title">A Study of Zooming, Interactive Lenses and Overview+Detail Techniques in Collaborative Map-Based Tasks</div>
        <div class="paper-authors"><b>Yu Liu</b>, Zhaoxin Zhang, Yuxin Pan, Yue Li, Hai-Ning Liang, Paul Craig, Lingyun Yu</div>
        <div class="paper-venue"><em>2023 IEEE 16th Pacific Visualization Symposium (PacificVis)</em>, 2023.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://ieeexplore.ieee.org/document/10134444/" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{liu2023study,
  title={A Study of Zooming, Interactive Lenses and Overview+Detail Techniques in Collaborative Map-Based Tasks},
  author={Liu, Yu and Zhang, Zhaoxin and Pan, Yuxin and Li, Yue and Liang, Hai-Ning and Craig, Paul and Yu, Lingyun},
  booktitle={2023 IEEE 16th Pacific Visualization Symposium (PacificVis)},
  pages={1--10},
  year={2023},
  publisher={IEEE}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="physicalization">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('physicalization', '🧱 Data Physicalization')">🧱 Data Physicalization</span>
          <span class="badge-award">🏆 Best Short Paper</span>
        </div>
        <div class="paper-title">EmotionVis: Affective Visualization with Physical Devices</div>
        <div class="paper-authors">Xinyi Huang, <b>Yu Liu</b>, Lingyun Yu</div>
        <div class="paper-venue"><em>ACM International Symposium on Visual Information Communication and Interaction (VINCI)</em>, 2023.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://dl.acm.org/doi/10.1145/3615522.3615525" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{huang2023emotionvis,
  title={EmotionVis: Affective Visualization with Physical Devices},
  author={Huang, Xinyi and Liu, Yu and Yu, Lingyun},
  booktitle={Proceedings of the 16th International Symposium on Visual Information Communication and Interaction (VINCI '23)},
  year={2023},
  publisher={ACM},
  doi={10.1145/3615522.3615525}
}</code></pre>
          </details>
        </div>
      </div>

    </div>
    <div class="timeline-spine-col">
      <div class="timeline-year-badge">2023</div>
      <div class="timeline-track-line"></div>
    </div>
  </div>

  <!-- 2022 Year Section -->
  <div class="timeline-year-section" data-year="2022">
    <div class="timeline-content-col">
      <div class="paper-row" data-tags="multi-device">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
        </div>
        <div class="paper-title">DARC: A Visual Analytics System for Multivariate Applicant Data Aggregation, Reasoning and Comparison</div>
        <div class="paper-authors">Yihan Hou, <b>Yu Liu</b>, Hao Wang, Zhaoxin Zhang, Yue Li, Hai-Ning Liang, Lingyun Yu</div>
        <div class="paper-venue"><em>Pacific Graphics (PG Short Papers)</em>, 2022.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://doi.org/10.2312/pg.20221239" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{hou2022darc,
  title={DARC: A Visual Analytics System for Multivariate Applicant Data Aggregation, Reasoning and Comparison},
  author={Hou, Yihan and Liu, Yu and Wang, Hao and Zhang, Zhaoxin and Li, Yue and Liang, Hai-Ning and Yu, Lingyun},
  booktitle={Pacific Graphics Short Papers},
  year={2022},
  doi={10.2312/pg.20221239}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="immersive">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('immersive', '🥽 Immersive XR')">🥽 Immersive XR</span>
        </div>
        <div class="paper-title">MEinVR: Multimodal Interaction Paradigms in Immersive Exploration</div>
        <div class="paper-authors">Ziyue Yuan, <b>Yu Liu</b>, Lingyun Yu</div>
        <div class="paper-venue"><em>2022 IEEE International Symposium on Mixed and Augmented Reality Adjunct (ISMAR-Adjunct)</em>, 2022.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://ieeexplore.ieee.org/document/9974327/" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{yuan2022meinvr,
  title={MEinVR: Multimodal Interaction Paradigms in Immersive Exploration},
  author={Yuan, Ziyue and Liu, Yu and Yu, Lingyun},
  booktitle={2022 IEEE International Symposium on Mixed and Augmented Reality Adjunct (ISMAR-Adjunct)},
  pages={1--5},
  year={2022},
  publisher={IEEE}
}</code></pre>
          </details>
        </div>
      </div>
    </div>
    <div class="timeline-spine-col">
      <div class="timeline-year-badge clickable-year-badge" onclick="toggleEarlierPubs()" title="Click to view/hide earlier publications (2018–2021)">2022 <span id="badgeYearArrow" class="badge-sub-arrow">▾</span></div>
      <div class="timeline-track-line"></div>
    </div>
  </div>

  <!-- Collapsible Section for Pre-2022 Publications (2018–2021) -->
  <div class="earlier-pubs-wrapper" id="earlierPubsWrapper">
    <details class="earlier-pubs-archive" id="earlierPubsArchive">
      <summary class="earlier-pubs-toggle-wrap">
        <div class="earlier-pubs-toggle-btn">
          <span class="toggle-icon">📜</span>
          <span>View Earlier Publications (2018–2021)</span>
          <span class="toggle-arrow">▾</span>
        </div>
      </summary>
      <div class="earlier-pubs-content">

  <!-- 2021 Year Section -->
  <div class="timeline-year-section" data-year="2021">
    <div class="timeline-content-col">
      <div class="paper-row" data-tags="multi-device">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
        </div>
        <div class="paper-title">A Multiple View Approach to Support Data Exploration in Co-located and Synchronous Collaboration</div>
        <div class="paper-authors"><b>Yu Liu</b>, Paul Craig</div>
        <div class="paper-venue"><em>2021 IEEE 24th International Conference on Computer Supported Cooperative Work in Design (CSCWD)</em>, 2021.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://ieeexplore.ieee.org/document/9437845/" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{liu2021multiple,
  title={A Multiple View Approach to Support Data Exploration in Co-located and Synchronous Collaboration},
  author={Liu, Yu and Craig, Paul},
  booktitle={2021 IEEE 24th International Conference on Computer Supported Cooperative Work in Design (CSCWD)},
  pages={1--6},
  year={2021},
  publisher={IEEE}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="multi-device">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
        </div>
        <div class="paper-title">Displaying Multiple User Selections in Public Multi-user Wall-mounted Large-display Information Visualisation Environments</div>
        <div class="paper-authors">Paul Craig, <b>Yu Liu</b></div>
        <div class="paper-venue"><em>2021 IEEE 24th International Conference on Computer Supported Cooperative Work in Design (CSCWD)</em>, 2021.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://ieeexplore.ieee.org/document/9437656/" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{craig2021displaying,
  title={Displaying Multiple User Selections in Public Multi-user Wall-mounted Large-display Information Visualisation Environments},
  author={Craig, Paul and Liu, Yu},
  booktitle={2021 IEEE 24th International Conference on Computer Supported Cooperative Work in Design (CSCWD)},
  pages={1--6},
  year={2021},
  publisher={IEEE}
}</code></pre>
          </details>
        </div>
      </div>
    </div>
    <div class="timeline-spine-col">
      <div class="timeline-year-badge">2021</div>
      <div class="timeline-track-line"></div>
    </div>
  </div>

  <!-- 2019 Year Section -->
  <div class="timeline-year-section" data-year="2019">
    <div class="timeline-content-col">
      <div class="paper-row" data-tags="multi-device cultural">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
          <span class="tag-theme" onclick="toggleFilter('cultural', '🏛️ Cultural Heritage')">🏛️ Cultural Heritage</span>
        </div>
        <div class="paper-title">Smart Survey Tool: A Multi Device Platform for Museum Visitor Tracking and Tracking Data Visualization</div>
        <div class="paper-authors">Paul Craig, Yiwen Wang, Joon Sik Kim, Gang Chen, <b>Yu Liu</b>, Jiabei Li, Zhiqi Gao, Guodong Du</div>
        <div class="paper-venue"><em>2019 IEEE Pacific Visualization Symposium (PacificVis)</em>, 2019.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://ieeexplore.ieee.org/document/8781581/" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{craig2019smart,
  title={Smart Survey Tool: A Multi Device Platform for Museum Visitor Tracking and Tracking Data Visualization},
  author={Craig, Paul and Wang, Yiwen and Kim, Joon Sik and Chen, Gang and Liu, Yu and Li, Jiabei and Gao, Zhiqi and Du, Guodong},
  booktitle={2019 IEEE Pacific Visualization Symposium (PacificVis)},
  pages={1--5},
  year={2019},
  publisher={IEEE}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="maps smartwatch">
        <div class="paper-row-tags">
          <span class="tag-theme" onclick="toggleFilter('maps', '🗺️ Cartography & Maps')">🗺️ Cartography & Maps</span>
          <span class="tag-device" onclick="toggleFilter('smartwatch', '⌚ Smartwatch & Mobile')">⌚ Smartwatch & Mobile</span>
        </div>
        <div class="paper-title">A Vision for Pervasive Information Visualisation to Support Passenger Navigation in Public Metro Networks</div>
        <div class="paper-authors">Paul Craig, <b>Yu Liu</b></div>
        <div class="paper-venue"><em>2019 IEEE International Conference on Pervasive Computing and Communications Workshops (PerCom Workshops)</em>, 2019.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://ieeexplore.ieee.org/document/8730811/" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{craig2019vision,
  title={A Vision for Pervasive Information Visualisation to Support Passenger Navigation in Public Metro Networks},
  author={Craig, Paul and Liu, Yu},
  booktitle={2019 IEEE International Conference on Pervasive Computing and Communications Workshops (PerCom Workshops)},
  pages={1--6},
  year={2019},
  publisher={IEEE}
}</code></pre>
          </details>
        </div>
      </div>
    </div>
    <div class="timeline-spine-col">
      <div class="timeline-year-badge">2019</div>
      <div class="timeline-track-line"></div>
    </div>
  </div>

  <!-- 2018 Year Section -->
  <div class="timeline-year-section" data-year="2018">
    <div class="timeline-content-col">
      <div class="paper-row" data-tags="multi-device">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
        </div>
        <div class="paper-title">Coordinating User Selections in Collaborative Smart-Phone Large-Display Multi-device Environments</div>
        <div class="paper-authors">Paul Craig, <b>Yu Liu</b></div>
        <div class="paper-venue"><em>International Conference on Cooperative Design, Visualization and Engineering (CDVE)</em>, 2018.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://doi.org/10.1007/978-3-030-00560-3_4" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{craig2018coordinating,
  title={Coordinating User Selections in Collaborative Smart-Phone Large-Display Multi-device Environments},
  author={Craig, Paul and Liu, Yu},
  booktitle={International Conference on Cooperative Design, Visualization and Engineering (CDVE 2018)},
  volume={11115},
  pages={28--37},
  year={2018},
  publisher={Springer},
  doi={10.1007/978-3-030-00560-3_4}
}</code></pre>
          </details>
        </div>
      </div>

      <div class="paper-row" data-tags="multi-device">
        <div class="paper-row-tags">
          <span class="tag-device" onclick="toggleFilter('multi-device', '🖥️ Multi-Device & Display')">🖥️ Multi-Device & Display</span>
        </div>
        <div class="paper-title">Toward a View Coordination Methodology for Collaborative Shared Large-Display Environments</div>
        <div class="paper-authors"><b>Yu Liu</b>, Paul Craig</div>
        <div class="paper-venue"><em>International Conference on Cooperative Design, Visualization and Engineering (CDVE)</em>, 2018.</div>
        <div class="paper-actions">
          <a class="paper-btn" href="https://doi.org/10.1007/978-3-030-00560-3_41" target="_blank">Full Text</a>
          <details class="paper-bibtex">
            <summary class="paper-btn">BibTeX</summary>
            <pre><code>@inproceedings{liu2018toward,
  title={Toward a View Coordination Methodology for Collaborative Shared Large-Display Environments},
  author={Liu, Yu and Craig, Paul},
  booktitle={International Conference on Cooperative Design, Visualization and Engineering (CDVE 2018)},
  volume={11115},
  pages={317--324},
  year={2018},
  publisher={Springer},
  doi={10.1007/978-3-030-00560-3_41}
}</code></pre>
          </details>
        </div>
      </div>
    </div>
    <div class="timeline-spine-col">
      <div class="timeline-year-badge">2018</div>
      <div class="timeline-track-line"></div>
    </div>
  </div>

      </div>
    </details>
  </div>

</div>

<script>
function toggleEarlierPubs() {
  var archive = document.getElementById('earlierPubsArchive');
  if (archive) {
    archive.open = !archive.open;
    var arrow = document.getElementById('badgeYearArrow');
    if (arrow) {
      arrow.textContent = archive.open ? '▴' : '▾';
    }
    if (archive.open) {
      archive.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
    }
  }
}

document.addEventListener('DOMContentLoaded', function() {
  var archiveEl = document.getElementById('earlierPubsArchive');
  if (archiveEl) {
    archiveEl.addEventListener('toggle', function() {
      var arrow = document.getElementById('badgeYearArrow');
      if (arrow) {
        arrow.textContent = archiveEl.open ? '▴' : '▾';
      }
    });
  }
});

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

  document.querySelectorAll('.paper-row').forEach(function(row) {
    var tags = (row.getAttribute('data-tags') || '').split(' ');
    var match = tags.indexOf(tag) !== -1;
    row.style.display = match ? '' : 'none';
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

  // Handle earlier publications archive visibility and open state when filtering
  var archive = document.getElementById('earlierPubsArchive');
  var wrapper = document.getElementById('earlierPubsWrapper');
  if (archive) {
    var hasMatchInArchive = false;
    archive.querySelectorAll('.paper-row').forEach(function(row) {
      if (row.style.display !== 'none') {
        hasMatchInArchive = true;
      }
    });
    if (hasMatchInArchive) {
      if (wrapper) wrapper.style.display = 'block';
      archive.open = true;
    } else {
      if (wrapper) wrapper.style.display = 'none';
    }
  }

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

  document.querySelectorAll('.paper-row').forEach(function(row) {
    row.style.display = '';
  });
  document.querySelectorAll('.timeline-year-section').forEach(function(section) {
    section.style.display = 'grid';
  });

  var wrapper = document.getElementById('earlierPubsWrapper');
  var archive = document.getElementById('earlierPubsArchive');
  if (wrapper) wrapper.style.display = 'block';
  if (archive) archive.open = false;
  var arrow = document.getElementById('badgeYearArrow');
  if (arrow) arrow.textContent = '▾';
}
</script>

<span class='anchor' id='teaching'></span>
<span class='anchor' id='-teaching'></span>
# <span class="heading-icon-badge">👨‍🏫</span> Teaching
- CPT001 Professional Skills in Computer Science
- CPT003 Introduction to Database


<span class='anchor' id='student-competitions'></span>
<span class='anchor' id='-honors-and-awards'></span>
# <span class="heading-icon-badge">🏆</span> Student Competitions
- *2026.06* ChinaVis Data Challenge Contest, Third Prize.
- *2024.06* ChinaVis Data Challenge Contest, Second Prize.
- *2023.06* ChinaVis Data Challenge Contest, First Prize.
- *2022.06* ChinaVis Data Challenge Contest, Second Prize.
- *2021.06* ChinaVis Data Challenge Contest, Merit Prize. 



<span class='anchor' id='educations'></span>
<span class='anchor' id='-educations'></span>
# <span class="heading-icon-badge">🎓</span> Educations
- *2018.02 - 2022.06*, Ph.D. Computer Science, University of Liverpool (UoL). 
- *2016.09 - 2017.12*, MSc. Design for Informatics, University of Edinburgh (UoE).
- *2012.09 - 2016.06*, BSc. Computer Science and Software Engineering. Taiyuan University of Technology (TYUT).

<span class='anchor' id='invited-talks'></span>
<span class='anchor' id='-invited-talks'></span>
# <span class="heading-icon-badge">🎤</span> Invited Talks
- *2023.04*, 2023 China-Japan-South Korea Visualization Forum, Seoul, Korea.

<span class='anchor' id='service'></span>
<span class='anchor' id='-service'></span>
# <span class="heading-icon-badge">🤝</span> Service
Reviewer of IEEE VIS, ACM MobileHCI, CSCW, IJHCI, ISS, IEEE VR, ISMAR, PacificVis, ChinaVis, VINCI etc.

<span class='anchor' id='work'></span>
<span class='anchor' id='-work'></span>
<span class='anchor' id='work-experience'></span>
<span class='anchor' id='internships'></span>
# <span class="heading-icon-badge">💼</span> Work Experience
- *2022.08 - Present*, Assistant Professor, [Xi'an Jiaotong-Liverpool University](https://scholar.xjtlu.edu.cn/en/persons/YuLiu02) (XJTLU), Suzhou, China.
- *2021.12 - 2022.06*, Visualization Designer, [Bytedance](https://www.bytedance.com/en/), Beijing, China.

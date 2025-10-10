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

Zhihuang Liu is a Ph.D. candidate at the College of Computer Science and Technology, National University of Defense Technology (NUDT), with an **<span style="color:#dd0000">expected graduation date of June 2026</span>**.

<!-- He has published over 10 research papers, including in *IEEE Symposium on Security and Privacy (S\&P)*, *IEEE Transactions on Information Forensics and Security (TIFS)*, and *Future Generation Computer Systems (FGCS)*. He also serves as reviewer for IJCAI, AAAI, TSMC, JPDC, etc. -->

**Research interests**: Privacy Protection, Applied Cryptography, Usable Security, Large Language Models (LLMs), and Artificial Intelligence (AI) Security.

> *<span style="color:#006600"> High self‑motivated researcher in privacy protection and applied cryptography with focus on AI security and usable security solutions.</span>*

# 🔥 News

- 2025.10: An effort on *Security Vulnerabilities in Self-Hosted LLM Services* has been submitted to WWW2026. Wish us luck!
- 2025.08: One paper has been accepted by IEEE Transactions on Circuits and Systems for Video Technology (CCF B, JCR Q1, 中科院一区TOP).
- 2025.05: A paper titled **Risk-Aware Privacy Preservation for LLM Inference** has been submitted to TIFS for consideration. Wish us luck!
- 2025.03: One paper about has been accepted by IEEE Transactions on Circuits and Systems for Video Technology (CCF B, JCR Q1, 中科院一区TOP).
- 2025.03: One paper has been accepted by IEEE Transactions on Big Data (CCF C, JCR Q1, 中科院二区).
- 2024.12: Awarded the **Ourstanding Student** of NUDT.
- 2024.12: Awarded China **National Scholarship** for PhD Students.
- 2024.09: One paper has been accepted by **IEEE Symposium on Security and Privacy (SP'25) <span style="color:#dd0000">(Top Computer Security Conference, CCF A)</span>**.
- 2024.08: One paper has been accepted by International Conference on Neural Information Processing (CCF C).
- 2024.04: One paper has been accepted by **IEEE Transactions on Information Forensics and Security <span style="color:#dd0000">(CCF A, JCR Q1, 中科院一区TOP)</span>**.
- 2023.12: One paper has been accepted by Future Generation Computer Systems (FGCS) (CCF C, JCR Q1, 中科院一区TOP).

# 📝 Selected Publications (* Corresponding author)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE SP'25</div><img src='images/SP25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Prevalence Overshadows Concerns? Understanding Chinese Users’ Privacy Awareness and Expectations Towards LLM-based Healthcare Consultation**
<span style="color:#006600"><span style="font-weight:bold">Zhihuang Liu</span>, Ling Hu, Tongqing Zhou, Yonghao Tang, Zhiping Cai*</span>
The 46th IEEE Symposium on Security and Privacy (S&P25)
[[Paper]](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a092/22K50ou6sKY)   [[Project]](http://healthllm.top/LLMHPri/encindexen/) [[Code]](https://github.com/Cristliu/LLMHealthPrivacy_UserStudy)

- This paper contributes the first user study (n=846) in China on privacy awareness and expectations in LLM-based healthcare consultations.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS</div><img src='images/TIFS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SeCoSe: Toward Searchable and Communicable Healthcare Service Seeking in Flexible and Secure EHR Sharing**
<span style="color:#006600"><span style="font-weight:bold">Zhihuang Liu</span>, Ling Hu, Zhiping Cai*, Ximeng Liu, and Yanhua Liu</span>
IEEE Transactions on Information Forensics and Security
[[Paper]](https://ieeexplore.ieee.org/document/10506668)   [[Project]](https://cristliu.github.io/) [[Code]](https://cristliu.github.io/)

- This Paper proposes a searchable and communicable proactive healthcare service seeking scheme (SeCoSe) in a blockchain-based EHR sharing system.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TBD</div><img src='images/TBD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Split Learning on Segmented Healthcare Data**
<span style="color:#006600">Ling Hu, Tongqing Zhou, <span style="font-weight:bold">Zhihuang Liu*</span>, Fang Liu, and Zhiping Cai*</span>
IEEE Transactions on Big Data
[[Paper]](https://ieeexplore.ieee.org/document/10946173)   [[Project]](https://cristliu.github.io/) [[Code]](https://cristliu.github.io/)

- This paper first investigates the privacy-preserving learning problem on segmented healthcare data. Considering the data split situation, we propose to adapt split learning to support the distributed learning process and design a novel framework STSL (i.e., Spatio-temporal Split Learning).

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">FGCS</div><img src='images/FGCS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Blockchain and trusted reputation assessment-based incentive mechanism for healthcare services**
<span style="color:#006600">Yanhua Liu, <span style="font-weight:bold">Zhihuang Liu*</span>, Qiu Zhang, Jinshu Su, Zhiping Cai, and Xiaoyan Li</span>
Future Generation Computer Systems
[[Paper]](https://www.sciencedirect.com/science/article/pii/S0167739X23004843)   [[Project]](https://cristliu.github.io/) [[Code]](https://cristliu.github.io/)

- This Paper proposes a Blockchain and trusted Reputation assessment-based Incentive mechanism for healthcare services (BtRaI).

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT</div><img src='images/TCSVT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**PPIDM: Privacy-Preserving Inference for Diffusion Model in the Cloud**
<span style="color:#006600">Zhangdong Wang, <span style="font-weight:bold">Zhihuang Liu</span>, Yuanjing Luo, Tongqing Zhou, Jiaohua Qin, and Zhiping Cai*</span>
IEEE Transactions on Circuits and Systems for Video Technology
[[Paper]](https://ieeexplore.ieee.org/document/10937222)   [[Project]](https://cristliu.github.io/) [[Code]](https://cristliu.github.io/)

- This paper proposes PPIDM (Privacy-Preserving Inference for Diffusion Models), a novel framework for diffusion model inference in cloud environments that mitigates both resource constraints and privacy risks.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TETC</div><img src='images/TETC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**A Web Back-End Database Leakage Incident Reconstruction Framework Over Unlabeled Logs**
<span style="color:#006600">Yanhua Liu, <span style="font-weight:bold">Zhihuang Liu*</span>, Ximeng Liu, and Wenzhong Guo</span>
IEEE Transactions on Emerging Topics in Computing
[[Paper]](https://ieeexplore.ieee.org/document/9861244/)   [[Project]](https://cristliu.github.io/) [[Code]](https://github.com/Cristliu/WeB-DLIR)

- This paper proposes a web back-end database leakage incident reconstruction framework (WeB-DLIR) over unlabeled logs, designed to improve the intelligence and automation of reconstructing web back-end database leakage incidents triggered by web-based attacks in unannotated logging environments.

</div>
</div>


# 🎖 Honors and Awards

- [2024.12] Outstanding Student, National University of Defense Technology. (优秀学员)
- [2024.12] National Scholarship, Ministry of Education, China. (博士研究生国家奖学金)
- [2024.08] Excellent Master Thesis, Fuzhou University. (优秀硕士论文)
- [2023.08] Special Award in Master Comprehensive Scholarship, Fuzhou University. (硕士综合学业奖学金特等奖)
- [2023.06] Excellent Graduate, Fuzhou University. (优秀毕业生)
- [2023.02] Third Prize (National), CCF Big Data & Computing Intelligence Contest. (CCF大数据与计算智能大赛全国三等奖)
- [2022.11] National Scholarship, Ministry of Education, China. (硕士研究生国家奖学金)
- [2020.12] Special Award for Outstanding New Student Scholarship, Fuzhou University. (优秀新生特等奖学金)
- [2020.10] Third Prize (National), China Collegiate Computig Contest. (中国高校计算机大赛三等奖)
- [2020.06] Excellent Graduate, Fuzhou University. (优秀毕业生)
- [2019.12] National First Prize (Team Leader & Key Contributor), CCF Big Data & Computing Intelligence Contest. (CCF大数据与计算智能大赛全国一等奖)

# 📖 Educations

- *2023.09 - now*, Ph.D. Candidate, National University of Defense Technology, Changsha, China.
- *2020.09 - 2023.06*, Master, Fuzhou University, Fuzhou, China.
- *2016.09 - 2020.06*, Bachelor, Fuzhou University, Fuzhou, China.

# 💬 Invited Talks

- *2024.09*, Excellent Doctoral Student Forum, Xiamen, Organized by Xiamen University.

# 💻 Services

## Journal Reviewer

- IEEE Transactions on Dependable and Secure Computing (**TDSC**), IEEE Transactions on Wireless Communications (**TWC**), IEEE Transactions on Systems, Man, and Cybernetics: Systems (**TSMC**)
- IEEE Internet of Things Journal (**IOTJ**), SCIENCE CHINA Information Sciences (*Chinese*), Journal of Parallel and Distributed Computing (JPDC)
- The Journal of Supercomputing, Software Quality Journal, Scientific Reports, International Journal of Machine Learning and Cybernetics

## Conference Reviewer (Program Committee)

- The Annual Conference on Neural Information Processing Systems (**NeurIPS**), The IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**), The Association for the Advancement of Artificial Intelligence (**AAAI**)
- The International Joint Conference on Artificial Intelligence (**IJCAI**), ACM International Conference on Multimedia (**MM**)

<span class='anchor' id='contact'></span>

# 📬 Contact

**Email:** lzhliu@nudt.edu.cn

**WeChat:**

<img src="/images/lzh_wechat.jpg" alt="WeChat QR Code" style="max-width:220px; margin-top:10px;">

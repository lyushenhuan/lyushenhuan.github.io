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

<head>
    <style>
        .container {
            display: flex;
        }
        .text {
            flex: 80%;
        }
        .image {
            flex: 20%;
            display: flex;
            justify-content: flex-end;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="text">
            <p>I am an Assistant Researcher in <a href='https://cies.hhu.edu.cn/'>College of Computer Science & Software Engineering</a> at <a href='https://www.hhu.edu.cn/'>Hohai University</a>. I obtained my Ph.D. degree from <a href='https://cs.nju.edu.cn/'>Department of Computer Science & Technology</a> in <a href='https://www.nju.edu.cn/main.htm'>Nanjing University</a> in Dec. 2022, where I was very fortunate to be advised by Prof. <a href='https://cs.nju.edu.cn/zhouzh/index.htm'>Zhi-Hua Zhou</a>. Before that, I received my B.Sc. degree from <a href='https://bs.ustc.edu.cn/chinese/teacher-8.html'>Department of Statistics</a> in <a href='https://www.ustc.edu.cn/'>University of Science and Technology of China</a> in Jun. 2017.<br><br>
              My research interest includes <b>ensemble learning</b> and <b>learning theory</b>.<br><br>
              <a href='papers/lyu2024cv.pdf'>[Resume]</a> & <a href='papers/吕沈欢简历.pdf'>[中文简历]</a></p>
        </div>
        <div class="image">
            <img src="images/hhu.svg" alt='sym' width="60%">
        </div>
    </div>
</body>


# 🔥 News
- <b><font color='red'> Enrolling Students: Looking for self-motivated M.Sc/Ph.D. students to work on Artificial Intelligence. <br>Feel free to send me an email with your resume and a document stating your research motivation. </font></b>
- *2024.05*: &nbsp;🎉🎉 Our paper "Confidence-Aware Contrastive Learning for Selective Classification" is accepted by the **CCF-A** international conference ICML 2024. 
- *2023.12*: &nbsp;🎉🎉 My doctoral dissertation "Research on Theoretical Analysis of Deep Forests and Extensions" was awarded the **Excellent Doctoral Dissertation of Jiangsu Association of Artificial Intelligence**. 
- *2022.12*: &nbsp;🎉🎉 Our paper "Depth is More Powerful than Width with Prediction Concatenation in Deep Forests" is accepted by the **CCF-A** international conference NeurIPS 2022 as an **Oral Presentation**. 
- *2019.12*: &nbsp;🎉🎉 Our paper "A Refined Margin Distribution Analysis for Forest Representation Learning" is accepted by the **CCF-A** international conference NeurIPS 2019. 

#  👨‍💻 Students


<b>M.Eng Students</b><br>

2023: <a href='https://tianshuangwu.github.io/'>[Tian-Shuang Wu 吴填双]</a>; <a href='https://cnkeysky.github.io/'>[Ning Chen 陈宁]</a>;<br>
2024: <a href='https://airplanecc.github.io/'>[Yi-Wei Jiang 姜怡炜]</a>;

<b>B.Eng Students</b><br>
2024: <a href='https://XJHpresident.github.io/'>[Jin-Han Xin 辛金韩]</a>;


<b>Collected Seminars</b><br>
<a href='seminar/MLDM-Seminar.html'>[ML&DM Seminar]</a>: Seminar on Machine Learning and Data Mining for my students.<br>
<a href='https://www.fai-seminar.ac.cn/'>[FAI Seminar]</a>: International Seminar on Foundational Artificial Intelligence.<br>


# 📝 Publications 


- [[ECAI 2024]](https://www.ecai2024.eu/programme/accepted-papers) The Role of Depth, Width, and Tree Size in Expressiveness of Deep Forest. [[paper]](papers/lyu2024role.pdf) [[code]](https://github.com/lyushenhuan/lyu2024role) [[bib]](papers/lyu2024role.html) <br>
**Shen-Huan Lyu**\*, Jin-Hui Wu\*, Qin-Cheng Zheng, and Baoliu Ye. (\* indicates equal contribution)<br>
In: Proceedings of the 27th European Conference on Artificial Intelligence, in press, 2024. **(CCF B)**

- [[ECAI 2024]](https://www.ecai2024.eu/programme/accepted-papers) Mask-Encoded Sparsification: Overcoming Biased Gradients for Communication-Efficient Split Learning. [[paper]](papers/zhou2024mask.pdf) [[code]](https://github.com) [[bib]](papers/zhou2024mask.html) <br>
Wenxuan Zhou, Zhihao Qu, **Shen-Huan Lyu**, Miao Cai, and Baoliu Ye.<br>
In: Proceedings of the 27th European Conference on Artificial Intelligence, in press, 2024. **(CCF B)**

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INS 2024</div><img src='images/he2024multi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
---

- [[INS 2024]](https://www.sciencedirect.com/science/article/abs/pii/S0020025524010703) Multi-Class Imbalance Problem: A Multi-Objective Solution. [[paper]](papers/he2024multi.pdf) [[code]](https://github.com/lyushenhuan/he2024multi) [[bib]](papers/he2024multi.html) <br>
Yi-Xiao He, Dan-Xuan Liu, **Shen-Huan Lyu**, Chao Qian, and Zhi-Hua Zhou.<br>
Information Sciences, in press, 2024. **(CCF B, CAS Q1)**
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/wu2024confidence.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
---

- [[ICML 2024]](https://icml.cc/virtual/2024/poster/34017) Confidence-Aware Contrastive Learning for Selective Classification. [[paper]](papers/wu2024confidence.pdf) [[code]](https://github.com/lyushenhuan/wu2024confidence) [[bib]](papers/wu2024confidence.html) <br>
Yu-Chang Wu, **Shen-Huan Lyu**, Haopu Shang, Xiangyu Wang, and Chao Qian.<br>
In: Proceedings of the 41st International Conference on Machine Learning, in press, Vienna, Austria, 2024. **(CCF A)**
</div>
</div>

- [[IWQoS 2024]](https://iwqos2024.ieee-iwqos.org/) Identifying Key Tag Distribution in Large-Scale RFID Systems. [[paper]](papers/wang2024identifying.pdf) [[bib]](papers/wang2024identifying.html) <br>
Yanyan Wang, Jia Liu, **Shen-Huan Lyu**, Zhihao Qu, Bin Tang, and Baoliu Ye.<br>
In: IEEE/ACM 32nd International Symposium on Quality of Service, in press, 2024. **(CCF B)**

- [[TKDD 2024]](https://dl.acm.org/doi/10.1145/3641108) Interpreting Deep Forest through Feature Contribution and MDI Feature Importance. [[paper]](papers/he2024interpreting.pdf) [[code]](https://github.com/heyixiao14/DFFI-code) [[bib]](papers/he2024interpreting.html) <br>
Yi-Xiao He, **Shen-Huan Lyu**, and Yuan Jiang.<br>
ACM Transactions on Knowledge Discovery from Data, in press, 2024. **(CCF B, CAS Q3)**

- [[JOS 2024]](https://www.jos.org.cn/jos/article/abstract/6841?st=search) Interaction Representations Based Deep Forest Method in Multi-Label Learning. [[paper]](papers/lyu2024interaction.pdf) [[bib]](papers/lyu2024interaction.html) <br>
**Shen-Huan Lyu**, Yi-He Chen, and Yuan Jiang.<br>
Journal of Software, 35(4):1934-1944, 2024. **(CCF A in Chinese)**

- [[AISTATS 2023]](https://proceedings.mlr.press/v206/zheng23b.html)  On the Consistency Rate of Decision Tree Learning Algorithms. [[paper]](papers/zheng2023consistency.pdf) [[code]](https://github.com/lyushenhuan/zheng2023consistency) [[bib]](papers/zheng2023consistency.html)<br>
Qin-Cheng Zheng, **Shen-Huan Lyu**, Shao-Qun Zhang, Yuan Jiang, and Zhi-Hua Zhou.<br>
In: Proceedings of the 26th International Conference on Artificial Intelligence and Statistics, pp. 7824-7848, Valencia, ES, 2023. **(CCF C)**


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022</div><img src='images/lyu2022depth.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
---

- [[NeurIPS 2022 **Oral**]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/c017e92288b5056c578bb6b0b69d9e76-Abstract-Conference.html) Depth is More Powerful than Width with Prediction Concatenation in Deep Forests. [[paper]](papers/lyu2022depth.pdf) [[bib]](papers/lyu2022depth.html) <br> 
**Shen-Huan Lyu**, Yi-Xiao He, and Zhi-Hua Zhou. <br>
In: Advances in Neural Information Processing Systems 35, pp. 29719-29732, New Orleans, Louisiana, US, 2022. **(CCF A)**
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NEUNET 2022</div><img src='images/lyu2022improving.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
---

- [[NEUNET 2022]](https://doi.org/10.1016/j.neunet.2022.03.019) Improving Generalization of Neural Networks by Leveraging Margin Distribution. [[paper]](papers/lyu2022improving.pdf) [[code]](https://github.com/lyushenhuan/lyu2022improving) [[bib]](papers/lyu2022improving.html)<br>
**Shen-Huan Lyu**, Lu Wang, and Zhi-Hua Zhou.<br>
Neural Networks, 151:48-60, 2022. **(CCF B, CAS Q1)**
</div>
</div>

- [[CJE 2022]](https://doi.org/10.1049/cje.2022.00.178) A Region-Based Analysis for the Feature Concatenation in Deep Forests. [[paper]](papers/lyu2022region.pdf) [[bib]](papers/lyu2022region.html)<br>
**Shen-Huan Lyu**, Yi-He Chen, and Zhi-Hua Zhou.<br>
Chinese Journal of Electronics, 31(6):1072-1080, 2022. **(CCF A in Chinese, CAS Q4)**

- [[ICDM 2021]](https://doi.org/10.1109/ICDM51629.2021.00118) Improving Deep Forest by Exploiting High-Order Interactions. [[paper]](papers/chen2021improving.pdf) [[code]](https://github.com/lyushenhuan/chen2021improving) [[bib]](papers/chen2021improving.html)<br>
Yi-He Chen\*, **Shen-Huan Lyu**\*, and Yuan Jiang. (\* indicates equal contribution)<br>
In: Proceedings of the 21st IEEE International Conference on Data Mining, pp. 1030-1035, Auckland, NZ, 2021. **(CCF B)**


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2019</div><img src='images/lyu2019refined.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
---

- [[NeurIPS 2019]](https://papers.nips.cc/paper/8791-a-refined-margin-distribution-analysis-for-forest-representation-learning) A Refined Margin Distribution Analysis for Forest Representation Learning. [[paper]](papers/lyu2019refined.pdf) [[code]](https://github.com/lyushenhuan/lyu2019refined) [[bib]](papers/lyu2019refined.html) <br>
**Shen-Huan Lyu**, Liang Yang, and Zhi-Hua Zhou.<br>
In: Advances in Neural Information Processing Systems 32, pp. 5531-5541, Vancouver, British Columbia, CA, 2019. **(CCF A)**
</div>
</div>

<!-- 
- \[NeurIPS 2024\] Enhance Learning Efficiency of Oblique Decision Tree via Feature Concatenation.<br>
**Shen-Huan Lyu**, Yi-Xiao He, Yanyan Wang, Zhihao Qu, and Baoliu Ye.<br>
Under Review, 2024.

- \[NeurIPS 2024\] Theoretical Investigation on Inductive Bias of Isolation Forest.<br>
Qin-Cheng Zheng, Shao-Qun Zhang, **Shen-Huan Lyu**, Yuan Jiang, and Zhi-Hua Zhou.<br>
Under Review, 2024.

- \[AAAI 2025\] Semi-Supervised Deep Forest: A Large Margin Expedition.<br>
**Shen-Huan Lyu**, Yi-Xiao He, and Baoliu Ye.<br>
Under Review, 2024.

- \[NEUNET 2024\] The Role of Depth, Width, and Tree Size in Deep Forest.<br>
**Shen-Huan Lyu**\*, Jin-Hui Wu\*, Qin-Cheng Zheng, Yuan Jiang, and Baoliu Ye. (\* indicates equal contribution)<br>
Under Review, 2024.
 -->


# 🎖 Honors and Awards
<!-- - *2024.09* The Hong Kong Scholars Program, China. -->
- *2024.07* Jiangsu Youth Science and Technology Talent Sponsorship Program, Jiangsu.
- *2023.12* Excellent Doctoral Dissertation of Jiangsu Artificial Intelligence Society, Jiangsu.
- *2023.06* The 5th Special Funding from China Postdoctoral Science Foundation, China.
- *2022.12* Jiangsu Excellent Postdoctoral Program, Jiangsu.
- *2019.10* Artificial Intelligence Scholarship in Nanjing University, Nanjing. 
- *2019.09* The First Class Academic Scholarship in Nanjing University, Nanjing. 
- *2018.09* The First Class Academic Scholarship in Nanjing University, Nanjing.
- *2017.09* Presidential Special Scholarship for first year Ph.D. Student in Nanjing University, Nanjing.
- *2016.09* The Silver Prize Scholarship for Excellent Student in University of Science and Technology of China, Hefei.

# ✨ Academic Service
**Senior Program Committee Member of Conferences:**
- IJCAI: 2021

**Program Committee Member of Conferences:**
- ICML: 2021-2024
- NeurIPS: 2020-2023
- AAAI: 2020, 2021, 2023
- IJCAI: 2020, 2022-2024
- ICLR: 2020-2023

**Reviewer for Journals:**
- Artificial Intelligence (AIJ)
- IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)
- IEEE Transactions on Knowledge and Data Engineering (TKDE)
- IEEE Transactions on Neural Networks and Learning Systems (TNNLS)
- ACM Transactions on Knowledge Discovery from Data (TKDD)
- Machine Learning (MLJ)
- Research
- Chinese Journal of Electronics (CJE)
- 软件学报 (Journal of Software, JOS)

# 📖 Educations
- *2017.09 - 2022.12*, Ph.D. in Computer Science, Nanjing University (NJU) 
- *2013.09 - 2017.06*, B.Sc. in Statistics, University of Science and Technology of China (USTC)

# 💬 Invited Talks
- *2023.11*, Deep Forest, Z-Park National Laboratory, Beijing.
- *2022.12*, Depth is More Powerful than Width, New Orleans Convention Center, Online.
- *2022.01*, Margin Distribution Neural Networks, Huawei Noah's Ark Lab, Online.

# 💻 Experiences
- *2022.12 - now*, Assistent Researcher in [Hohai University](https://www.hhu.edu.cn/), Nanjing.
- *2022.06 - 2022.08*, Machine Learning Engineer in [Huawei Noah’s Ark Lab](http://dev3.noahlab.com.hk/), Nanjing.

<br><br><br><br>
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=200&t=tt&d=f6H62vvUiuP417y0Ay_kEFkOzotDi4AXgmWyKl59wTY'></script>
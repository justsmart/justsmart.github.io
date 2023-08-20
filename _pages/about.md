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

I am currently working toward the Doctoral degree with the Harbin Institute of Technology, Shenzhen, advised by [Yong Xu (徐勇)](http://faculty.hitsz.edu.cn/xuyong) and [Jie Wen (文杰)](https://sites.google.com/view/jerry-wen-hit/home?authuser=0). I graduated from Jilin University with a bachelor’s degree in computer science and from Huazhong University of Science and Technology with a master's degree in computer science. My research interests include machine learning and computer vision, especially multi-view representation learning.

<!--My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).-->


# News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2023.07*: Our paper is accepted by ACM MM 2023! 
- *2023.06*: Our paper is accepted by TNNLS! 
- *2023.03*: Our paper is accepted by TNNLS! 
- *2023.02*: Our paper is accepted by CVPR 2023! 
- *2023.02*: We win the AAAI 2023 distinguished paper award! 
- *2022.11*: Three papers are accepted by AAAI 2023!
- *2022.06*: Our paper is accepted by ACM MM 2022!

# Publications 

## Conference Papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/DICNet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
(Oral) [DICNet: Deep Instance-Level Contrastive Network for Double Incomplete Multi-View Multi-Label Classification](https://arxiv.org/pdf/2303.08358.pdf) (CCF-A)

**Chengliang Liu**, Jie Wen, Xiaoling Luo, Chao Huang, Zhihao Wu, Yong Xu

<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
- [AAAI 2023 distinguished paper award](https://aihub.org/2023/02/11/congratulations-to-the-aaai2023-best-paper-winners/)
</div>
</div>

- [Localized and Balanced Efficient Incomplete Multi-view Clustering](), Jie Wen, Gehui Xu, **Chengliang Liu**, Lunke Fei, Chao Huang, Wei Wang, Yong Xu, **ACM MM 2023** (Corresponding author, CCF-A)

- [Highly Confident Local Structure Based Consensus Graph Learning for Incomplete Multi-view Clustering](https://openaccess.thecvf.com/content/CVPR2023/html/Wen_Highly_Confident_Local_Structure_Based_Consensus_Graph_Learning_for_Incomplete_CVPR_2023_paper.html), Jie Wen, **Chengliang Liu**, Gehui Xu, Zhihao Wu, Chao Huang, Lunke Fei, Yong Xu, **CVPR 2023** (Co-first author, CCF-A)

- (Oral) [Incomplete Multi-View Multi-Label Learning via Label-Guided Masked View-and Category-Aware Transformers](https://arxiv.org/pdf/2303.07180), **Chengliang Liu**, Jie Wen, Xiaoling Luo, Yong Xu, **AAAI 2023** (CCF-A)

- (Oral) [MVCINN: Multi-View Diabetic Retinopathy Detection Using a Deep Cross-Interaction Neural Network](https://ojs.aaai.org/index.php/AAAI/article/download/26080/25852), Xiaoling Luo, **Chengliang Liu**, Waikeung Wong, Jie Wen, Xiaopeng Jin
, Yong Xu, **AAAI 2023** (Co-first author, CCF-A)

- [Pixel-Level Anomaly Detection via Uncertainty-Aware Prototypical Transformer](https://scholar.archive.org/work/tlli7rstvzfcrivc4rnvlcclmi/access/wayback/https://dl.acm.org/doi/pdf/10.1145/3503161.3548082), Chao Huang, **Chengliang Liu**, Zheng Zhang, Zhihao Wu, Jie Wen, Qiuping Jiang, Yong Xu, **ACM MM 2022** (Co-first author, CCF-A)



## Journal Papers
- [Information Recovery-Driven Deep Incomplete Multi-view Clustering Network](https://arxiv.org/abs/2304.00429), **Chengliang Liu**, Jie Wen, Zhihao Wu, Xiaoling Luo, Chao Huang, Yong xu, IEEE Transactions on Neural Networks and Learning Systems, 2023 (CCF-B, JCR Q1, IF-14.255)

- [Deep Double Incomplete Multi-View Multi-Label Learning With Incomplete Labels and Missing Views](https://ieeexplore.ieee.org/abstract/document/10086538/), Jie Wen, **Chengliang Liu**, Shijie Deng, Yicheng Liu, Lunke Fei, Ke Yan, Yong Xu, IEEE Transactions on Neural Networks and Learning Systems, 2023 (Corresponding author, CCF-B, JCR Q1, IF-14.255)

- [Localized sparse incomplete multi-view clustering](https://arxiv.org/pdf/2208.02998), **Chengliang Liu**, Zhihao Wu, Jie Wen, Yong Xu, Chao Huang, IEEE Transactions on Multimedia, 2022 (CCF-B, JCR Q1, IF-8.182)

- [Weakly Supervised Video Anomaly Detection via Self-Guided Temporal Discriminative Transformer](https://ieeexplore.ieee.org/abstract/document/10002867/), Chao Huang, **Chengliang Liu**, Jie Wen, Lian Wu, Yong Xu, Qiuping Jiang, Yaowei Wang, IEEE Transactions on Cybernetics, 2022 (Co-first author, CCF-B, JCR Q1, IF-19.118)

# Honors and Awards
- *2023.02* [AAAI 2023 distinguished paper award](https://aihub.org/2023/02/11/congratulations-to-the-aaai2023-best-paper-winners/).

# Educations
- *2020.09 - now*, School of Computer Science of Technology, Harbin Institute of Technology, Shenzhen, China. 
- *2018.09 - 2020.06*, School of Computer Science of Technology, Huazhong University of Science and Technology, Wuhan, China. 
- *2014.09 - 2018.06*, College of Computer Science of Technology, Jilin University, Changchun, China. 

# Academic Activities
- Journal Reviewers of IEEE TNNLS, IEEE TCSVT, CAAI TRIT
- Program Committee Members of AAAI 2023, ACM MM 2022 
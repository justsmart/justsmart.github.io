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

I am currently a Post-Doctoral Fellow at The Hong Kong Polytechnic University. I got my PhD in the School of Computer Science and Technology at Harbin Institute of Technology, Shenzhen. Before that, I graduated from Jilin University with a bachelor’s degree in computer science and from Huazhong University of Science and Technology with a master's degree in computer science. My research interests include machine learning and computer vision, especially multi-view/multimodal representation learning.

<!--My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).-->


# News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2025.11*: I received the Nomination Award for CSIG Doctoral Dissertation Incentive Program (中国图象图形学会博士学位论文激励计划提名奖)!
- *2025.09*: Our paper is accepted by NeurIPS 2025! 
- *2025.05*: Our paper is accepted by ICML 2025! 
- *2025.02*: Our paper is accepted by TPAMI! 
- *2024.05*: Our paper is accepted by ICML 2024! 
- *2023.12*: Our paper is accepted by AAAI 2024! 
- *2023.09*: Our paper is accepted by NeurIPS 2023! 
- *2023.07*: Our paper is accepted by ACM MM 2023! 
- *2023.06*: Our paper is accepted by TNNLS! 
- *2023.03*: Our paper is accepted by TNNLS! 
- *2023.02*: Our paper is accepted by CVPR 2023! 
- *2023.02*: We win the AAAI 2023 distinguished paper award! 
- *2022.11*: Three papers are accepted by AAAI 2023!
- *2022.06*: Our paper is accepted by ACM MM 2022!

# Publications 
<!-- \* Co-first author  &nbsp;&nbsp;&nbsp;\# Corresponding author -->
## Conference Papers
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/DICNet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
(Oral) [DICNet: Deep Instance-Level Contrastive Network for Double Incomplete Multi-View Multi-Label Classification](https://arxiv.org/pdf/2303.08358.pdf) (CCF-A)

**Chengliang Liu**, Jie Wen, Xiaoling Luo, Chao Huang, Zhihao Wu, Yong Xu

<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
<!-- - [AAAI 2023 distinguished paper award](https://aihub.org/2023/02/11/congratulations-to-the-aaai2023-best-paper-winners/) -->
<!-- </div> -->
<!-- </div> -->
- [Hierarchical Information Aggregation for Incomplete Multimodal Alzheimer's Disease Diagnosis](), **Chengliang Liu**, Que Yuanxi, Yabo Liu, Jie Wen, Jinghua Wang, Xiaoling Luo<sup>*</sup>, **NeurIPS 2025** 

- [Learning Compact Semantic Information for Incomplete Multi-View Missing Multi-Label Classification](), Jie Wen, Yadong Liu, Zhanyan Tang, Yuting He, Yulong Chen, Mu Li, **Chengliang Liu**<sup>*</sup>, **ICML 2025** (Corresponding author)

- [Partial Multi-View Multi-Label Classification via Semantic Invariance Learning and Prototype Modeling](https://openreview.net/forum?id=5ap1MmUqO6), **Chengliang Liu**, Gehui Xu, Jie Wen<sup>*</sup>, Yabo Liu, Chao Huang, Yong Xu<sup>*</sup>, **ICML 2024**

- [Attention-Induced Embedding Imputation for Incomplete Multi-View Partial Multi-Label Classification](https://ojs.aaai.org/index.php/AAAI/article/view/29293/30438), **Chengliang Liu**, Jinlong Jia, Jie Wen<sup>*</sup>, Yabo Liu, Xiaoling Luo, Chao Huang, Yong Xu<sup>*</sup>, **AAAI 2024**  

- [Masked Two-channel Decoupling Framework for Incomplete Multi-view Weak Multi-label Learning](https://openreview.net/forum?id=U4pFV192JQ), **Chengliang Liu**, Jie Wen<sup>*</sup>, Yabo Liu, Chao Huang, Zhihao Wu, Xiaoling Luo, Yong Xu<sup>*</sup>, **NeurIPS 2023** 

- [Localized and Balanced Efficient Incomplete Multi-view Clustering](https://dl.acm.org/doi/abs/10.1145/3581783.3612545), Jie Wen, Gehui Xu, **Chengliang Liu**<sup>*</sup>, Lunke Fei, Chao Huang, Wei Wang<sup>*</sup>, Yong Xu, **ACM MM 2023** (Corresponding author)

- [Highly Confident Local Structure Based Consensus Graph Learning for Incomplete Multi-view Clustering](https://openaccess.thecvf.com/content/CVPR2023/html/Wen_Highly_Confident_Local_Structure_Based_Consensus_Graph_Learning_for_Incomplete_CVPR_2023_paper.html), Jie Wen<sup>✝</sup>, **Chengliang Liu**<sup>✝</sup>, Gehui Xu, Zhihao Wu, Chao Huang, Lunke Fei, Yong Xu<sup>*</sup>, **CVPR 2023** (Co-first author)

- (Oral) [DICNet: Deep Instance-Level Contrastive Network for Double Incomplete Multi-View Multi-Label Classification](https://arxiv.org/pdf/2303.07180), **Chengliang Liu**, Jie Wen<sup>*</sup>, Xiaoling Luo, Chao Huang, Zhihao Wu, Yong Xu<sup>*</sup>, **AAAI 2023** ([AAAI 2023 distinguished paper award](https://aihub.org/2023/02/11/congratulations-to-the-aaai2023-best-paper-winners/))

- (Oral) [Incomplete Multi-View Multi-Label Learning via Label-Guided Masked View- and Category-Aware Transformers](https://arxiv.org/pdf/2303.07180), **Chengliang Liu**, Jie Wen<sup>*</sup>, Xiaoling Luo, Yong Xu<sup>*</sup>, **AAAI 2023** 

- (Oral) [MVCINN: Multi-View Diabetic Retinopathy Detection Using a Deep Cross-Interaction Neural Network](https://ojs.aaai.org/index.php/AAAI/article/download/26080/25852), Xiaoling Luo<sup>✝</sup>, **Chengliang Liu**<sup>✝</sup>, Waikeung Wong, Jie Wen<sup>*</sup>, Xiaopeng Jin
, Yong Xu<sup>*</sup>, **AAAI 2023** (Co-first author)

- [Pixel-Level Anomaly Detection via Uncertainty-Aware Prototypical Transformer](https://scholar.archive.org/work/tlli7rstvzfcrivc4rnvlcclmi/access/wayback/https://dl.acm.org/doi/pdf/10.1145/3503161.3548082), Chao Huang<sup>✝</sup>, **Chengliang Liu**<sup>✝</sup>, Zheng Zhang<sup>*</sup>, Zhihao Wu, Jie Wen, Qiuping Jiang, Yong Xu<sup>*</sup>, **ACM MM 2022** (Co-first author)



## Journal Papers
- [Reliable Representation Learning for Incomplete Multi-View Missing Multi-Label Classification](https://arxiv.org/html/2303.17117v3), **Chengliang Liu**, Jie Wen<sup>*</sup>, Yong Xu<sup>*</sup>, Bob Zhang, Liqiang Nie, Min Zhang, IEEE Transactions on Pattern Analysis and Machine Intelligence, 2025 

- [Information Recovery-Driven Deep Incomplete Multi-view Clustering Network](https://arxiv.org/abs/2304.00429), **Chengliang Liu**, Jie Wen<sup>*</sup>, Zhihao Wu, Xiaoling Luo, Chao Huang, Yong Xu, IEEE Transactions on Neural Networks and Learning Systems, 2023 

- [Deep Double Incomplete Multi-View Multi-Label Learning With Incomplete Labels and Missing Views](https://ieeexplore.ieee.org/abstract/document/10086538/), Jie Wen, **Chengliang Liu**<sup>*</sup>, Shijie Deng, Yicheng Liu, Lunke Fei, Ke Yan, Yong Xu, IEEE Transactions on Neural Networks and Learning Systems, 2023 (Corresponding author)

- [Localized sparse incomplete multi-view clustering](https://arxiv.org/pdf/2208.02998), **Chengliang Liu**, Zhihao Wu, Jie Wen<sup>*</sup>, Yong Xu<sup>*</sup>, Chao Huang, IEEE Transactions on Multimedia, 2022 

- [Weakly Supervised Video Anomaly Detection via Self-Guided Temporal Discriminative Transformer](https://ieeexplore.ieee.org/abstract/document/10002867/), Chao Huang<sup>✝</sup>, **Chengliang Liu**<sup>✝</sup>, Jie Wen, Lian Wu, Yong Xu<sup>*</sup>, Qiuping Jiang, Yaowei Wang, IEEE Transactions on Cybernetics, 2022 (Co-first author)

# Honors and Awards
- *2025.11* Nomination Award for CSIG Doctoral Dissertation Incentive Program (中国图象图形学会博士学位论文激励计划提名奖).
- *2024.11* ACM MM 2024 Outstanding reviewer.
- *2024.06* HIT Outstanding Doctoral Dissertation Award.
- *2023.10* National Scholarship of the Ministry of Education of China.
- *2023.02* [AAAI 2023 distinguished paper award](https://aihub.org/2023/02/11/congratulations-to-the-aaai2023-best-paper-winners/).

# Educations
- School of Computer Science of Technology, Harbin Institute of Technology, Shenzhen, China. 
- School of Computer Science of Technology, Huazhong University of Science and Technology, Wuhan, China. 
- College of Computer Science of Technology, Jilin University, Changchun, China. 

# Academic Activities
- Journal Reviewers of IEEE TPAMI, TNNLS, TCSVT, TMM, TKDE, TCYB, TIP.
- Senior Program Committee member of IJCAI 2025.  
- Program Committee Members of AAAI, ACM MM, CVPR, ICML, NeurIPS, ICLR, ICCV.
             

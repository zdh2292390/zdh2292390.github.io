---
permalink: /publications/
title: "Publications"
author_profile: true
redirect_from: 
  - /publications.html
---

<style>
.publication {
    margin-bottom: 25px;
    padding: 20px;
    border-left: 4px solid #3498db;
    background-color: #f8f9fa;
    display: flex;
    align-items: flex-start;
    gap: 20px;
}
.publication-image {
    flex-shrink: 0;
    width: 150px;
    height: 150px;
    border-radius: 8px;
    object-fit: contain;
    border: 2px solid #e9ecef;
    cursor: pointer;
    transition: transform 0.2s ease;
    background-color: #f8f9fa;
}
.publication-image:hover {
    transform: scale(1.05);
}
.publication-content {
    flex: 1;
}
.publication-title {
    font-weight: bold;
    color: #2c3e50;
    margin-bottom: 8px;
    font-size: 1.1em;
}
.publication-authors {
    color: #7f8c8d;
    margin-bottom: 8px;
    font-size: 0.95em;
}
.publication-venue {
    color: #e74c3c;
    font-weight: bold;
    margin-bottom: 5px;
}
.publication-year {
    color: #95a5a6;
    font-style: italic;
}
.section {
    margin-bottom: 40px;
}
.section h3 {
    color: #2c3e50;
    border-bottom: 2px solid #3498db;
    padding-bottom: 5px;
    margin-bottom: 20px;
    font-size: 1.4em;
}
.links {
    margin-top: 8px;
}
.links a {
    color: #3498db;
    text-decoration: none;
    margin-right: 15px;
    font-size: 0.9em;
}
.links a:hover {
    text-decoration: underline;
}
h2 {
    color: #2c3e50;
    border-bottom: 2px solid #3498db;
    padding-bottom: 10px;
    margin-top: 40px;
    margin-bottom: 20px;
}
ul {
    margin-left: 20px;
    margin-bottom: 30px;
}
ul li {
    margin-bottom: 10px;
    line-height: 1.6;
}
ul li a {
    color: #3498db;
    text-decoration: none;
}
ul li a:hover {
    text-decoration: underline;
}
/* Modal styles */
.modal {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0,0,0,0.8);
    animation: fadeIn 0.3s ease;
}
.modal-content {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    max-width: 90%;
    max-height: 90%;
    background-color: white;
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0 4px 20px rgba(0,0,0,0.3);
    animation: zoomIn 0.3s ease;
}
.modal-image {
    max-width: 100%;
    max-height: 80vh;
    border-radius: 8px;
    display: block;
    margin: 0 auto;
}
.close {
    position: absolute;
    top: 10px;
    right: 20px;
    font-size: 30px;
    font-weight: bold;
    color: #aaa;
    cursor: pointer;
    z-index: 1001;
}
.close:hover {
    color: #000;
}
@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}
@keyframes zoomIn {
    from { transform: translate(-50%, -50%) scale(0.8); }
    to { transform: translate(-50%, -50%) scale(1); }
}
@media (max-width: 768px) {
    .publication {
        flex-direction: column;
        text-align: center;
    }
    .publication-image {
        width: 120px;
        height: 120px;
        margin: 0 auto;
    }
    .modal-content {
        max-width: 95%;
        padding: 15px;
    }
    .modal-image {
        max-height: 70vh;
    }
}
</style>

## Peer-reviewed conference and journal papers

<div class="section">
<h3>2025</h3>

<div class="publication">
    <img src="{{ site.baseurl }}/images/1.jpg" alt="Paper 1" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Rescorla-Wagner Steering of LLMs for Undesired Behaviors over Disproportionate Inappropriate Context</div>
        <div class="publication-authors">Rushi Wang, Jiateng Liu, Cheng Qian, Yifan Shen, Yanzhou Pan, Zhaozhuo Xu, Ahmed Abbasi, Heng Ji, <strong>Denghui Zhang</strong></div>
        <div class="publication-venue">EMNLP'25: The 2025 Conference on Empirical Methods in Natural Language Processing (Main)</div>
        <div class="publication-year">2025</div>
        <div class="links"><a href="https://oppugno-rushi.github.io/rw-steering-page/" target="_blank">[Website]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/2.jpg" alt="Paper 2" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">DEL-ToM: Inference-Time Scaling for Theory-of-Mind Reasoning via Dynamic Epistemic Logic</div>
        <div class="publication-authors">Yuheng Wu, Jianwen Xie, <strong>Denghui Zhang</strong>, Zhaozhuo Xu</div>
        <div class="publication-venue">EMNLP'25: The 2025 Conference on Empirical Methods in Natural Language Processing (Main)</div>
        <div class="publication-year">2025</div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/3.jpg" alt="Paper 3" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Profiling LLM's Copyright Infringement Risks under Adversarial Persuasive Prompting</div>
        <div class="publication-authors">Jikai Long, Ming Liu, Xiusi Chen, Jialiang Xu, Shenglan Li, Zhaozhuo Xu, <strong>Denghui Zhang</strong></div>
        <div class="publication-venue">EMNLP'25: The 2025 Conference on Empirical Methods in Natural Language Processing (Findings)</div>
        <div class="publication-year">2025</div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/4.jpg" alt="Paper 4" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">ISACL: Internal State Analyzer for Copyrighted Training Data Leakage</div>
        <div class="publication-authors">Guangwei Zhang, Qisheng Su, Jiateng Liu, Cheng Qian, Yanzhou Pan, Yanjie Fu, <strong>Denghui Zhang</strong></div>
        <div class="publication-venue">EMNLP'25: The 2025 Conference on Empirical Methods in Natural Language Processing (Findings)</div>
        <div class="publication-year">2025</div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/5.jpg" alt="Paper 5" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">SafeSwitch: Steering Unsafe LLM Behavior via Internal Activation Signals</div>
        <div class="publication-authors">Peixuan Han, Cheng Qian, Xiusi Chen, Yuji Zhang, Heng Ji, <strong>Denghui Zhang</strong></div>
        <div class="publication-venue">EMNLP'25: The 2025 Conference on Empirical Methods in Natural Language Processing (Findings)</div>
        <div class="publication-year">2025</div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/6.jpg" alt="Paper 6" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">How Large Language Models Encode Theory-of-Mind: A Study on Sparse Parameter Patterns</div>
        <div class="publication-authors">Yuheng Wu, Wentao Guo, Zirui Liu, Heng Ji, Zhaozhuo Xu, <strong>Denghui Zhang</strong></div>
        <div class="publication-venue">npj Artificial Intelligence</div>
        <div class="publication-year">2025</div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/7.jpg" alt="Paper 7" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">EscapeBench: Towards Advancing Creative Intelligence of Language Model Agents</div>
        <div class="publication-authors">Cheng Qian, Peixuan Han, Qinyu Luo, Bingxiang He, Xiusi Chen, Yuji Zhang, Hongyi Du, Jiarui Yao, Xiaocheng Yang, <strong>Denghui Zhang</strong>, Yunzhu Li, Heng Ji</div>
        <div class="publication-venue">ACL'25: Proceedings of the Association for Computational Linguistics (Main Track)</div>
        <div class="publication-year">2025</div>
        <div class="links"><a href="https://arxiv.org/pdf/2412.13549" target="_blank">[PDF]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/8.jpg" alt="Paper 8" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Iterative Online-Offline Joint Optimization is Needed to Manage Complex LLM Copyright Risks</div>
        <div class="publication-authors">Yanzhou Pan, Jiayi Chen, Jiamin Chen, ZhaoZhuo Xu, <strong>Denghui Zhang</strong></div>
        <div class="publication-venue">ICML'25: The 42nd International Conference on Machine Learning (Position Paper)</div>
        <div class="publication-year">2025</div>
        <div class="links"><a href="https://icml.cc/virtual/2025/poster/40114" target="_blank">[PDF]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/9.jpg" alt="Paper 9" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Beyond Reactive Safety: Risk-Aware LLM Alignment via Long-Horizon Simulation</div>
        <div class="publication-authors">Chenkai Sun, <strong>Denghui Zhang</strong>, ChengXiang Zhai, Heng Ji</div>
        <div class="publication-venue">ACL'25: Proceedings of the Association for Computational Linguistics (ACL Findings)</div>
        <div class="publication-year">2025</div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/10.jpg" alt="Paper 10" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">ALinFiK: Learning to Approximate Linearized Future Influence Kernel for Scalable Third-Parity LLM Data Valuation</div>
        <div class="publication-authors">Yanzhou Pan, Huawei Lin, Yide Ran, Jiamin Chen, Xiaodong Yu, Weijie Zhao, <strong>Denghui Zhang</strong>, Zhaozhuo Xu</div>
        <div class="publication-venue">NAACL'25: 2025 Annual Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics (Main)</div>
        <div class="publication-year">2025</div>
        <div class="links"><a href="https://aclanthology.org/2025.naacl-long.589.pdf" target="_blank">[PDF]</a> <a href="https://github.com/huawei-lin/RapidIn" target="_blank">[Github]</a></div>
    </div>
</div>
</div>

<div class="section">
<h3>2024</h3>

<div class="publication">
    <img src="{{ site.baseurl }}/images/11.jpg" alt="Paper 11" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Do LLMs Know to Respect Copyright Notice?</div>
        <div class="publication-authors">Jialiang Xu, Shenglan Li, Zhaozhuo Xu, <strong>Denghui Zhang</strong></div>
        <div class="publication-venue">EMNLP'24: The 2024 Conference on Empirical Methods in Natural Language Processing (Main)</div>
        <div class="publication-year">2024</div>
        <div class="links"><a href="https://aclanthology.org/2024.emnlp-main.1147/" target="_blank">[PDF]</a> <a href="https://github.com/liamjxu/NoticeBench" target="_blank">[Github]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/12.jpg" alt="Paper 12" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">FinCon: A Synthesized LLM Multi-Agent System with Conceptual Verbal Reinforcement for Enhanced Financial Decision Making</div>
        <div class="publication-authors">Yangyang Yu, Zhiyuan Yao, Haohang Li, Zhiyang Deng, Yuechen Jiang, Yupeng Cao, Zhi Chen, Jordan W. Suchow, Zhenyu Cui, Rong Liu, Zhaozhuo Xu, <strong>Denghui Zhang</strong>, Koduvayur Subbalakshmi, Guojun Xiong, Yueru He, Jimin Huang, Dong Li, Qianqian Xie</div>
        <div class="publication-venue">NeurIPS'24: The 2024 Annual Conference on Neural Information Processing Systems (Main)</div>
        <div class="publication-year">2024</div>
        <div class="links"><a href="https://openreview.net/pdf?id=dG1HwKMYbC" target="_blank">[PDF]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/13.jpg" alt="Paper 13" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">FinMem: A Performance-Enhanced LLM Trading Agent with Layered Memory and Character Design</div>
        <div class="publication-authors">Yangyang Yu, Haohang Li, Zhi Chen, Yuechen Jiang, Yang Li, <strong>Denghui Zhang</strong>, Rong Liu, Jordan W. Suchow, Khaldoun Khashanah</div>
        <div class="publication-venue">ICLR'24: International Conference on Learning Representations - Workshop on LLM Agents</div>
        <div class="publication-year">2024</div>
        <div class="links"><a href="https://arxiv.org/abs/2311.13743" target="_blank">[PDF]</a> <a href="https://github.com/pipiku915/FinMem-LLM-StockTrading/tree/main" target="_blank">[Github]</a> <a href="#">[FT]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/14.jpg" alt="Paper 14" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Self-Paced Unified Representation Learning for Hierarchical Multi-Label Classification</div>
        <div class="publication-authors">Zixuan Yuan, Hao Liu, Haoyi Zhou, <strong>Denghui Zhang</strong>, Xiao Zhang, Hao Wang, Hui Xiong</div>
        <div class="publication-venue">AAAI'24: Proceedings of the 38th AAAI Conference on Artificial Intelligence</div>
        <div class="publication-year">2024</div>
    </div>
</div>
</div>

<div class="section">
<h3>2023</h3>

<div class="publication">
    <img src="{{ site.baseurl }}/images/15.jpg" alt="Paper 15" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Graph Learning of Multifaceted Motivations for Online Political Engagement Prediction in Counter-party Social Networks</div>
        <div class="publication-authors">Manting Hu, Qingyuan Lin, <strong>Denghui Zhang</strong>, Angela Lu, Junming Liu, Hui Xiong</div>
        <div class="publication-venue">ICIS'23: 44th International Conference on Information Systems (Best Student Paper Award)</div>
        <div class="publication-year">2023</div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/16.jpg" alt="Paper 16" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">LEVER: Online Adaptive Sequence Learning Framework for High-Frequency Trading</div>
        <div class="publication-authors">Zixuan Yuan, Junming Liu, Haoyi Zhou, <strong>Denghui Zhang</strong>, Hao Liu, Nengjun Zhu, Hui Xiong</div>
        <div class="publication-venue">IEEE TKDE: IEEE Transactions on Knowledge and Data Engineering</div>
        <div class="publication-year">2023</div>
        <div class="links"><a href="#">[FT]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/17.jpg" alt="Paper 17" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Multi-Faceted Knowledge-Driven Pre-training for Product Representation Learning</div>
        <div class="publication-authors"><strong>Denghui Zhang</strong>, Yanchi Liu, Zixuan Yuan, Yanjie Fu, Haifeng Chen, Hui Xiong</div>
        <div class="publication-venue">IEEE TKDE: IEEE Transactions on Knowledge and Data Engineering</div>
        <div class="publication-year">2023</div>
        <div class="links"><a href="#">[EM]</a> <a href="#">[TM]</a></div>
    </div>
</div>
</div>

<div class="section">
<h3>2022</h3>

<div class="publication">
    <img src="{{ site.baseurl }}/images/18.jpg" alt="Paper 18" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">AlphaVC: A Reinforcement Learning-based Venture Capital Investment Strategy</div>
        <div class="publication-authors">Zixuan Yuan*, <strong>Denghui Zhang</strong>*, Hao Zhong, Shengming Zhang, Xiong Hui</div>
        <div class="publication-venue">INFORMS DS: INFORMS Workshop on Data Science 2022 (In preparation for Management Science)</div>
        <div class="publication-year">2022</div>
        <div class="links"><a href="#">[FT]</a> <a href="#">[RL]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/19.jpg" alt="Paper 19" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Acqui-hiring or Acqui-quitting: Data-driven Post-M&A Turnover Prediction via a Dual-fit GNN Model</div>
        <div class="publication-authors"><strong>Denghui Zhang</strong>, Hao Zhong, Jingyuan Yang</div>
        <div class="publication-venue">CIST'22: INFORMS Conference On Information Systems And Technology (Submitted to Information Systems Research)</div>
        <div class="publication-year">2022</div>
        <div class="links"><a href="{{ site.baseurl }}/publications/M_A_sample_denghui.pdf" target="_blank">[PDF]</a> <a href="#">[CM]</a> <a href="#">[GL]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/20.jpg" alt="Paper 20" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Towards Learning Disentangled Representations for Time Series</div>
        <div class="publication-authors">Yuening Li, Zhengzhang Chen, Daochen Zha, Mengnan Du, <strong>Denghui Zhang</strong>, Haifeng Chen, Xia Hu</div>
        <div class="publication-venue">KDD'22: Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining</div>
        <div class="publication-year">2022</div>
        <div class="links"><a href="#">[PDF]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/21.jpg" alt="Paper 21" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Learning to Walk with Dual Agents Reinforcement Learning for Knowledge Graph Reasoning</div>
        <div class="publication-authors"><strong>Denghui Zhang</strong>*, Zixuan Yuan*, Hao Liu, Xiaodong Lin, Hui Xiong</div>
        <div class="publication-venue">AAAI'22: Proceedings of the 36th AAAI Conference on Artificial Intelligence (15% acceptance rate)</div>
        <div class="publication-year">2022</div>
        <div class="links"><a href="https://arxiv.org/pdf/2112.12876" target="_blank">[PDF]</a> <a href="https://github.com/RutgersDM/DKGR/tree/master" target="_blank">[code]</a> <a href="#">[RL]</a></div>
    </div>
</div>
</div>

<div class="section">
<h3>2021</h3>

<div class="publication">
    <img src="{{ site.baseurl }}/images/22.jpg" alt="Paper 22" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Domain-oriented Language Modeling with Adaptive Hybrid Masking and Optimal Transport Alignment</div>
        <div class="publication-authors"><strong>Denghui Zhang</strong>, Zixuan Yuan, Yanchi Liu, Hao Liu, Fuzhen Zhuang, Hui Xiong, Haifeng Chen</div>
        <div class="publication-venue">KDD'21: Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (15.4% acceptance rate)</div>
        <div class="publication-year">2021</div>
        <div class="links"><a href="{{ site.baseurl }}/publications/KDD21.pdf" target="_blank">[PDF]</a> <a href="#">[TM]</a> <a href="#">[EM]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/23.jpg" alt="Paper 23" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Self-Supervised Prototype Representation Learning for Event-Based Corporate Profiling</div>
        <div class="publication-authors">Zixuan Yuan, Hao Liu, Renjun Hu, <strong>Denghui Zhang</strong>, Hui Xiong</div>
        <div class="publication-venue">AAAI'21: Proceedings of the 35th AAAI Conference on Artificial Intelligence</div>
        <div class="publication-year">2021</div>
        <div class="links"><a href="#">[FT]</a> <a href="{{ site.baseurl }}/publications/Corporate_Profiling__AAAI_2021.pdf" target="_blank">[PDF]</a> <a href="https://github.com/yuanzx33033/SePaL" target="_blank">[code]</a></div>
    </div>
</div>
</div>

<div class="section">
<h3>2020</h3>

<div class="publication">
    <img src="{{ site.baseurl }}/images/24.jpg" alt="Paper 24" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">T²-Net: A Semi-supervised Deep Model for Turbulence Forecasting</div>
        <div class="publication-authors"><strong>Denghui Zhang</strong>, Yanchi Liu, Wei Cheng, Bo Zong, Jingchao Ni, Zhengzhang Chen, Haifeng Chen, Hui Xiong</div>
        <div class="publication-venue">ICDM'20: 2020 IEEE International Conference on Data Mining</div>
        <div class="publication-year">2020</div>
        <div class="links"><a href="{{ site.baseurl }}/publications/ICDM20.pdf" target="_blank">[PDF]</a> <a href="#">[SA]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/25.jpg" alt="Paper 25" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Spatio-Temporal Dual Graph Attention Network for Query-POI Matching</div>
        <div class="publication-authors">Zixuan Yuan, Hao Liu, Yanchi Liu, <strong>Denghui Zhang</strong>, Fei Yi, Nengju Zhu, Hui Xiong</div>
        <div class="publication-venue">SIGIR'20: Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval</div>
        <div class="publication-year">2020</div>
        <div class="links"><a href="https://dl.acm.org/doi/abs/10.1145/3397271.3401159" target="_blank">[PDF]</a> <a href="#">[SA]</a></div>
    </div>
</div>
</div>

<div class="section">
<h3>2019</h3>

<div class="publication">
    <img src="{{ site.baseurl }}/images/26.jpg" alt="Paper 26" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Job2Vec: Job Title Benchmarking with Collective Multi-View Representation Learning</div>
        <div class="publication-authors"><strong>Denghui Zhang</strong>, Junming Liu, Hengshu Zhu, Yanchi Liu, Lichen Wang, Pengyang Wang, Hui Xiong</div>
        <div class="publication-venue">CIKM'19: Proceedings of the 28th ACM International Conference on Information and Knowledge Management</div>
        <div class="publication-year">2019</div>
        <div class="links"><a href="https://arxiv.org/pdf/2009.07429" target="_blank">[PDF]</a> <a href="#">[CM]</a> <a href="#">[GL]</a></div>
    </div>
</div>
</div>

<div class="section">
<h3>2018</h3>

<div class="publication">
    <img src="{{ site.baseurl }}/images/27.jpg" alt="Paper 27" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Link Prediction in Knowledge Graphs: A Hierarchy-Constrained Approach</div>
        <div class="publication-authors">Manling Li, Yuanzhuo Wang, <strong>Denghui Zhang</strong>, Yantao Jia, Xueqi Cheng</div>
        <div class="publication-venue">IEEE Transactions on Big Data</div>
        <div class="publication-year">2018</div>
        <div class="links"><a href="https://ieeexplore.ieee.org/document/8450054" target="_blank">[PDF]</a></div>
    </div>
</div>

<div class="publication">
    <img src="{{ site.baseurl }}/images/28.jpg" alt="Paper 28" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Path-Based Attention Neural Model for Fine-Grained Entity Typing</div>
        <div class="publication-authors"><strong>Denghui Zhang</strong>, Manling Li, Pengshan Cai, Yantao Jia, Yuanzhuo Wang, Xueqi Cheng</div>
        <div class="publication-venue">AAAI 2018: Proceedings of the 32nd AAAI Conference on Artificial Intelligence (abstract paper)</div>
        <div class="publication-year">2018</div>
        <div class="links"><a href="{{ site.baseurl }}/publications/PAN.pdf" target="_blank">[PDF]</a> <a href="#">[TM]</a></div>
    </div>
</div>
</div>

<div class="section">
<h3>2017</h3>

<div class="publication">
    <img src="{{ site.baseurl }}/images/29.jpg" alt="Paper 29" class="publication-image">
    <div class="publication-content">
        <div class="publication-title">Efficient Parallel Translating Embedding For Knowledge Graphs</div>
        <div class="publication-authors"><strong>Denghui Zhang</strong>, Manling Li, Yantao Jia, Yuanzhuo Wang, Xueqi Cheng</div>
        <div class="publication-venue">WI 2017: Proceedings of IEEE/WIC/ACM International Conference on Web Intelligence</div>
        <div class="publication-year">2017</div>
        <div class="links"><a href="{{ site.baseurl }}/publications/ParTransX.pdf" target="_blank">[PDF]</a> <a href="https://github.com/zdh2292390/ParTrans-X" target="_blank">[code]</a></div>
    </div>
</div>
</div>

<p><em>For a complete list of publications, please visit my <a href="https://scholar.google.com.hk/citations?user=QoovOGcAAAAJ&hl=zh-CN">Google Scholar profile</a>.</em></p>

<h2>Working papers</h2>
<ul>
    <li><strong>Acqui-hiring or Acqui-quitting: Post-M&A Turnover Prediction via a Dual-fit GNN Model</strong></li>
    <li><strong>AlphaVC: A Reinforcement Learning-based Venture Capital Investment Strategy</strong></li>
</ul>

<h2>Patents</h2>
<ul>
    <li><a href="#">US Patent App. 17/584,638</a> <strong>Multi-Faceted Knowledge-Driven Pre-training for Product Representation Learning</strong></li>
    <li><a href="#">US Patent App. 17/165,515</a> <strong>Semi-supervised deep model for turbulence forecasting</strong></li>
    <li><a href="#">US Patent App. 17/003,112</a> <strong>Multi-scale multi-granularity spatial-temporal traffic volume prediction</strong></li>
</ul>


<!-- Modal for image zoom -->
<div id="imageModal" class="modal">
    <div class="modal-content">
        <span class="close">&times;</span>
        <img id="modalImage" class="modal-image" src="" alt="">
    </div>
</div>

<script>
    // Get the modal
    var modal = document.getElementById('imageModal');
    var modalImg = document.getElementById('modalImage');
    var closeBtn = document.getElementsByClassName('close')[0];

    // Add click event listeners to all publication images
    document.addEventListener('DOMContentLoaded', function() {
        var images = document.querySelectorAll('.publication-image');
        images.forEach(function(img) {
            img.addEventListener('click', function() {
                modal.style.display = 'block';
                modalImg.src = this.src;
                modalImg.alt = this.alt;
            });
        });
    });

    // Close modal when clicking the X
    closeBtn.onclick = function() {
        modal.style.display = 'none';
    }

    // Close modal when clicking outside the image
    modal.onclick = function(event) {
        if (event.target === modal) {
            modal.style.display = 'none';
        }
    }

    // Close modal with Escape key
    document.addEventListener('keydown', function(event) {
        if (event.key === 'Escape') {
            modal.style.display = 'none';
        }
    });
</script>
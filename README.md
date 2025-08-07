<p align="center">
    <img src="training&test.png" width="90%" style="align:center;"/>
</p>

<h1 align="center">Awesome Medical-Reasoning with LLMs & MLLMs</h1>

<p align="center">
  <b>A curated list of papers, benchmarks, and resources for medical reasoning with LLMs & MLLMs</b>
</p>
<details open>
  <summary>🗂️ Table of Contents</summary>
  <ol>
    <li><a href="#survey-paper">Survey Paper</a></li>
    <li><a href="#various-modalities">Various Modalities</a></li>
    <li><a href="#training-time-techniques">Training-time Techniques</a></li>
    <li><a href="#test-time-techniques">Test-time Techniques</a></li>
    <li><a href="#applications">Applications</a></li>
    <li><a href="#evaluation--benchmarking">Evaluation & Benchmarking</a></li>
    <li><a href="#other-resources">Other Resources</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license--citation">License & Citation</a></li>
  </ol>
</details>

## Survey Paper

- **[Medical Reasoning in the Era of LLMs: A Systematic Review of Enhancement Techniques and Applications](https://arxiv.org/abs/2508.00669)**
  *Wenxuan Wang, Zizhan Ma, Meidan Ding, Shiyi Zheng, Shengyuan Liu, Jie Liu, Jiaming Ji, Wenting Chen, Xiang Li, Linlin Shen, Yixuan Yuan* Preprint'25
    - PDF: `survey-paper.pdf`

## Taxonomy
![Taxonomy](./taxonomy_figure.pdf.png)

## Various Modalities

### Reasoning over Text
1. **[Reasoning Like a Doctor: Improving Medical Dialogue Systems via Diagnostic Reasoning Process Alignment](https://arxiv.org/abs/2406.13934)** *(Kaishuai Xu, Yi Cheng, Wenjun Hou, Qiaoyu Tan, Wenjie Li).* ACL'2024  
2. **[MedReason: Eliciting Factual Medical Reasoning Steps in LLMs via Knowledge Graphs](https://arxiv.org/abs/2504.00993)** *(Juncheng Wu et al.).* 2025  
3. **[MedEx: Enhancing Medical Question-Answering with First-Order Logic Based Reasoning and Knowledge Injection](https://aclanthology.org/2025.coling-main.649/)** *(Aizan Zafar, Kshitij Mishra, Asif Ekbal).* ACL'2025  
4. **[Med-RLVR: Emerging Medical Reasoning from a 3B Base Model via Reinforcement Learning](https://arxiv.org/abs/2502.19655)** *(Sheng Zhang et al.).* 2025  
5. **[Beyond Distillation: Pushing the Limits of Medical LLM Reasoning with Minimalist Rule-Based RL](https://arxiv.org/abs/2505.17952)** *(Che Liu et al.).* 2025  
6. **[M1: Unleash the Potential of Test-Time Scaling for Medical Reasoning with Large Language Models](https://arxiv.org/abs/2504.00869)** *(Xiaoke Huang et al.).* 2025  
7. **[FineMedLM-O1: Enhancing the Medical Reasoning Ability of LLM from Supervised Fine-Tuning to Test-Time Training](https://arxiv.org/abs/2501.09213)** *(Hongzhou Yu et al.).* 2025  
8. **[MedAdapter: Efficient Test-Time Adaptation of Large Language Models Towards Medical Reasoning](https://aclanthology.org/2024.emnlp-main.1244.pdf)** *(Wenqi Shi et al.).* ACL'2024  
9. **[ArgMed-Agents: Explainable Clinical Decision Reasoning with LLM Discussion via Argumentation Schemes](https://arxiv.org/abs/2403.06294)** *(Shengxin Hong et al.).* 2024  
10. **[MedAgents: Large Language Models as Collaborators for Zero-Shot Medical Reasoning](https://aclanthology.org/2024.findings-acl.33.pdf)** *(Xiangru Tang et al.).* ACL'2024  



### Reasoning over Image
1. **[MedVLM-R1: Incentivizing Medical Reasoning Capability of Vision-Language Models (VLMs) via Reinforcement Learning](https://arxiv.org/abs/2502.19634)** *(Jiazhen Pan, Che Liu, Junde Wu, Fenglin Liu, Jiayuan Zhu, Hongwei Bran Li, Chen Chen, Cheng Ouyang, Daniel Rueckert).* 2025  
2. **[Med-R1: Reinforcement Learning for Generalizable Medical Reasoning in Vision-Language Models](https://arxiv.org/abs/2503.13939)** *(Yuxiang Lai, Jike Zhong, Ming Li, Shitian Zhao, Xiaofeng Yang).* 2025  
3. **[GMAI-VL-R1: Harnessing Reinforcement Learning for Multimodal Medical Reasoning](https://arxiv.org/abs/2504.01886)** *(Yanzhou Su, Tianbin Li, Jiyao Liu, Chenglong Ma, Junzhi Ning, Cheng Tang, Sibo Ju, Jin Ye, Pengcheng Chen, Ming Hu, Shixiang Tang, Lihao Liu, Bin Fu, Wenqi Shao, Xiaowei Hu, Xiangwen Liao, Yuanfeng Ji, Junjun He).* 2025  
4. **[MedTVT-R1: A Multimodal LLM Empowering Medical Reasoning and Diagnosis](https://arxiv.org/abs/2506.18512)** *(Yuting Zhang, Kaishen Yuan, Hao Lu, Yutao Yue, Jintai Chen, Kaishun Wu).* 2025  
5. **[MC-CoT: A Modular Collaborative CoT Framework for Zero-Shot Medical-VQA with LLM and MLLM Integration](https://arxiv.org/abs/2410.04521)** *(Lai Wei, Wenkai Wang, Xiaoyu Shen, Yu Xie, Zhihao Fan, Xiaojin Zhang, Zhongyu Wei, Wei Chen).* 2024  
6. **[Elicit and Enhance: Advancing Multimodal Reasoning in Medical Scenarios](https://arxiv.org/abs/2505.23118)** *(Linjie Mu, Zhongzhen Huang, Yakun Zhu, Xiangyu Zhao, Shaoting Zhang, Xiaofan Zhang).* 2025  
7. **[PRS-Med: Position Reasoning Segmentation with Vision-Language Model in Medical Imaging](https://arxiv.org/abs/2505.11872)** *(Quoc-Huy Trinh, Minh-Van Nguyen, Jung Peng, Ulas Bagci, Debesh Jha).* 2025  
8. **[AOR: Anatomical Ontology-Guided Reasoning for Medical Large Multimodal Model in Chest X-Ray Interpretation](https://arxiv.org/abs/2505.02830)** *(Qingqiu Li, Zihang Cui, Seongsu Bae, Jilan Xu, Runtian Yuan, Yuejie Zhang, Rui Feng, Quanli Shen, Xiaobo Zhang, Junjun He, Shujun Wang).* 2025
9. **[GEMeX-ThinkVG: Towards Thinking with Visual Grounding in Medical VQA via Reinforcement Learning](https://arxiv.org/abs/2506.17939)** *Bo Liu, Xiangyu Zhao, Along He, Yidi Chen, Huazhu Fu, Xiao-Ming Wu* 2025



### Reasoning over Code
1. **[MedAgentGym: Training LLM Agents for Code-Based Medical Reasoning at Scale](https://arxiv.org/abs/2506.04405)** *(Ran Xu et al.).* 2025  
2. **[BioCoder: A Benchmark for Bioinformatics Code Generation with Contextual Pragmatic Knowledge](https://arxiv.org/abs/2308.16458)** *(Xiangru Tang, Bill Qian, Rick Gao, Jiakang Chen, Xinyun Chen, Mark Gerstein).* 2023  
3. **[Can Large Language Models Replace Data Scientists in Biomedical Research?](https://arxiv.org/abs/2410.21591)** *(Zifeng Wang, Benjamin Danek, Ziwei Yang, Zheng Chen, Jimeng Sun).* 2024  



## Training-time Techniques

### Supervised Fine-Tuning
1. **[FineMedLM-O1: Enhancing the Medical Reasoning Ability of LLM from Supervised Fine-Tuning to Test-Time Training](https://arxiv.org/abs/2501.09213)** *(Hongzhou Yu et al.).* 2025
2. **[AOR: Anatomical Ontology-Guided Reasoning for Medical Large Multimodal Model in Chest X-Ray Interpretation](https://arxiv.org/abs/2505.02830)** *(Qingqiu Li, Zihang Cui, Seongsu Bae, Jilan Xu, Runtian Yuan, Yuejie Zhang, Rui Feng, Quanli Shen, Xiaobo Zhang, Junjun He, Shujun Wang).* 2025
3. **[Towards Expert-Level Medical Question Answering with Large Language Models](https://www.nature.com/articles/s41591-024-03423-7)** *(Karan Singhal et al.)* Nat Med 2025
4. **[HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs](https://arxiv.org/abs/2412.18925)** *(Junying Chen et al.)* 2024
5. **[MedReason: Eliciting Factual Medical Reasoning Steps in LLMs via Knowledge Graphs](https://arxiv.org/abs/2504.00993)** *(Juncheng Wu et al.).* 2025
6. **[Disentangling Reasoning and Knowledge in Medical Large Language Models](http://arxiv.org/abs/2505.11462)** *(Rahul Thapa, Qingyang Wu, Kevin Wu, Harrison Zhang, Angela Zhang, Eric Wu, Haotian Ye, Suhana Bedi, Nevin Aresh, Joseph Boen, Shriya Reddy, Ben Athiwaratkun, Shuaiwen Leon Song, James Zou)* 2025
7. **[Reasoning Like a Doctor: Improving Medical Dialogue Systems via Diagnostic Reasoning Process Alignment](https://arxiv.org/abs/2406.13934)** *(Kaishuai Xu, Yi Cheng, Wenjun Hou, Qiaoyu Tan, Wenjie Li)* 2024  
8. **[MedGround-R1: Advancing Medical Image Grounding via Spatial-Semantic Rewarded Group Relative Policy Optimization](https://arxiv.org/abs/2507.02994)** *(Huihui Xu, Yuanpeng Nie, Hualiang Wang, Ying Chen, Wei Li, Junzhi Ning, Lihao Liu, Hongqiu Wang, Lei Zhu, Jiyao Liu, Xiaomeng Li, Junjun He)* 2025
9. **[PRS-Med: Position Reasoning Segmentation with Vision-Language Model in Medical Imaging](https://arxiv.org/abs/2505.11872)** *(Quoc-Huy Trinh, Minh-Van Nguyen, Jung Peng, Ulas Bagci, Debesh Jha).* 2025


### Reinforcement Learning
1. **[Towards Expert-Level Medical Question Answering with Large Language Models](https://www.nature.com/articles/s41591-024-03423-7)** *(Karan Singhal et al.)* Nat Med 2025
2. **[HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs](https://arxiv.org/abs/2412.18925)** *(Junying Chen et al.)* 2024
3. **[Knowledge-Augmented Multimodal Clinical Rationale Generation for Disease Diagnosis with Small Language Models](https://arxiv.org/abs/2411.07611)** *(Shuai Niu, Jing Ma, Hongzhan Lin, Liang Bai, Zhihua Wang, Yida Xu, Yunya Song, Xian Yang)* ACL'25
4. **[MedGround-R1: Advancing Medical Image Grounding via Spatial-Semantic Rewarded Group Relative Policy Optimization](https://arxiv.org/abs/2507.02994)** *(Huihui Xu, Yuanpeng Nie, Hualiang Wang, Ying Chen, Wei Li, Junzhi Ning, Lihao Liu, Hongqiu Wang, Lei Zhu, Jiyao Liu, Xiaomeng Li, Junjun He)* 2025
5. **[Med-R1: Reinforcement Learning for Generalizable Medical Reasoning in Vision-Language Models](https://arxiv.org/abs/2503.13939)** *(Yuxiang Lai, Jike Zhong, Ming Li, Shitian Zhao, Xiaofeng Yang).* 2025
6. **[GMAI-VL-R1: Harnessing Reinforcement Learning for Multimodal Medical Reasoning](https://arxiv.org/abs/2504.01886)** *(Yanzhou Su, Tianbin Li, Jiyao Liu, Chenglong Ma, Junzhi Ning, Cheng Tang, Sibo Ju, Jin Ye, Pengcheng Chen, Ming Hu, Shixiang Tang, Lihao Liu, Bin Fu, Wenqi Shao, Xiaowei Hu, Xiangwen Liao, Yuanfeng Ji, Junjun He).* 2025
7. **[Beyond Distillation: Pushing the Limits of Medical LLM Reasoning with Minimalist Rule-Based RL](https://arxiv.org/abs/2505.17952)** *(Che Liu et al.).* 2025
8. **[Disentangling Reasoning and Knowledge in Medical Large Language Models](http://arxiv.org/abs/2505.11462)** *(Rahul Thapa, Qingyang Wu, Kevin Wu, Harrison Zhang, Angela Zhang, Eric Wu, Haotian Ye, Suhana Bedi, Nevin Aresh, Joseph Boen, Shriya Reddy, Ben Athiwaratkun, Shuaiwen Leon Song, James Zou)* 2025


## Test-Time Techniques

### Prompt-Based Elicitation

1. **[Large Language Models are Clinical Reasoners: Reasoning-Aware Diagnosis Framework with Prompt-Generated Rationales](https://arxiv.org/abs/2312.07399)** *(Taeyoon Kwon, Kai Tzu-iunn Ong, Dongjin Kang, Seungjun Moon, Jeong Ryong Lee, Dosik Hwang, Yongsik Sim, Beomseok Sohn, Dongha Lee, Jinyoung Yeo).* AAAI'2024
1. **[Few shot chain-of-thought driven reasoning to prompt LLMs for open-ended medical question answering](https://aclanthology.org/2024.findings-emnlp.31/)** *(Saeel Sandeep Nachane, Ojas Gramopadhye, Prateek Chanda, Ganesh Ramakrishnan, Kshitij Sharad Jadhav, Yatin Nandwani, Dinesh Raghu, Sachindra Joshi)* EMNLP'2024
1. **[Large Language Models Perform Diagnostic Reasoning](https://arxiv.org/abs/2307.08922)** *(Cheng-Kuang Wu, Wei-Lin Chen, Hsin-Hsi Chen)* arXiv’2023
1. **[CoD: Towards an Interpretable Medical Agent using Chain of Diagnosis](https://aclanthology.org/2025.findings-acl.740/)** *(Junying Chen, Chi Gui, Anningzhe Gao, Ke Ji, Xidong Wang, Xiang Wan, Benyou Wang)* ACL'2025
1. **[BP4ER: Bootstrap Prompting for Explicit Reasoning in Medical Dialogue Generation](https://aclanthology.org/2024.lrec-main.223/)** *(Yuhong He, Yongqi Zhang, Shizhu He, Jun Wan)* LREC-COLING'2024
1. **[Step-by-Step Fact Verification System for Medical Claims with Explainable Reasoning](https://aclanthology.org/2025.naacl-short.68/)** *(Juraj Vladika, Ivana Hacajova, Florian Matthes)* NAACL'2025
1. **[MC-CoT: A Modular Collaborative CoT Framework for Zero-shot Medical-VQA with LLM and MLLM Integration](https://arxiv.org/abs/2410.04521)** *(Lai Wei, Wenkai Wang, Xiaoyu Shen, Yu Xie, Zhihao Fan, Xiaojin Zhang, Zhongyu Wei, Wei Chen)* arXiv’2024
1. **[PathCoT: Chain-of-Thought Prompting for Zero-shot Pathology Visual Reasoning](https://arxiv.org/abs/2507.01029)** *(Junjie Zhou, Yingli Zuo, Shichang Feng, Peng Wan, Qi Zhu, Daoqiang Zhang, Wei Shao)* arXiv’2025

### Reasoning Selection \& Aggregation

1. **[Reasoning with Large Language Models for Medical Question Answering](https://academic.oup.com/jamia/article/31/9/1964/7938374)** *(Mary M Lucas, Justin Yang, Jon K Pomeroy, Christopher C Yang)* JAMIA’2024
1. **[m1: Unleash the Potential of Test-Time Scaling for Medical Reasoning with Large Language Models](https://arxiv.org/abs/2504.00869)** *(Xiaoke Huang, Juncheng Wu, Hui Liu, Xianfeng Tang, Yuyin Zhou)* arXiv’2025
1. **[O1 Replication Journey -- Part 3: Inference-time Scaling for Medical Reasoning](https://arxiv.org/abs/2501.06458)** *(Zhongzhen Huang, Gui Geng, Shengyi Hua, Zhen Huang, Haoyang Zou, Shaoting Zhang, Pengfei Liu, Xiaofan Zhang)* arXiv'2025
1. **[MedAdapter: Efficient Test-Time Adaptation of Large Language Models Towards Medical Reasoning](https://aclanthology.org/2024.emnlp-main.1244/)** *(Wenqi Shi, Ran Xu, Yuchen Zhuang, Yue Yu, Haotian Sun, Hang Wu, Carl Yang, May Dongmei Wang)*  EMNLP'2024

### Knowledge Enhancement

1. **[SelfRewardRAG: Enhancing Medical Reasoning with Retrieval-Augmented Generation and Self-Evaluation](https://doi.org/10.1109/ISCV60512.2024.10620139)** *(Zakaria Hammane, Fatima-Ezzahraa Ben-Bouazza, Abdelhadi Fennan)* ISCV'2024
1. **[Improving Medical Reasoning through Retrieval and Self-Reflection with Retrieval-Augmented Large Language Models](https://doi.org/10.1093/bioinformatics/btae238)** *(Minbyul Jeong, Jiwoong Sohn, Mujeen Sung, Jaewoo Kang)* Bioinformatics'2024
1. **[RARoK: Retrieval-Augmented Reasoning on Knowledge for Medical Question Answering](https://doi.org/10.1109/BIBM62325.2024.10822341)** *(Buchao Zhan, Anqi Li, Xin Yang, Dongmei He, Yucong Duan, Shankai Yan)* IEEE BIBM'2024
1. **[Guiding Clinical Reasoning with Large Language Models via Knowledge Seeds](https://doi.org/10.24963/ijcai.2024/829)** *(Jiageng Wu, Xian Wu, Jie Yang)* IJCAI'2024

### Multi-Agent Systems

1. **[MedAgents: Large Language Models as Collaborators for Zero-Shot Medical Reasoning](https://aclanthology.org/2024.findings-acl.33/)** *(Xiangru Tang, Anni Zou, Zhuosheng Zhang, Ziming Li, Yilun Zhao, Xingyao Zhang, Arman Cohan, Mark Gerstein)* ACL'2024
1. **[ArgMed-Agents: Explainable Clinical Decision Reasoning with LLM Discussion via Argumentation Schemes](https://doi.org/10.1109/BIBM62325.2024.10822109)** *(Shengxin Hong, Liang Xiao, Xin Zhang, Jianxia Chen)* IEEE BIBM'2024
1. **[MedRAX: Medical Reasoning Agent for Chest X-ray](https://arxiv.org/abs/2502.02673)** *(Adibvafa Fallahpour, Jun Ma, Alif Munim, Hongwei Lyu, Bo Wang)* arXiv'2025
1. **[Inquire, Interact, and Integrate: A Proactive Agent Collaborative Framework for Zero-Shot Multimodal Medical Reasoning](https://arxiv.org/abs/2405.11640)** *(Zishan Gu, Fenglin Liu, Changchang Yin, Ping Zhang)* arXiv’2024
1. **[Ask Patients with Patience: Enabling LLMs for Human-Centric Medical Dialogue with Grounded Reasoning](https://arxiv.org/abs/2502.07143)** *(Jiayuan Zhu, Junde Wu)* arXiv’2025
1. **[ClinicalAgent: Clinical Trial Multi-Agent System with Large Language Model-based Reasoning](https://doi.org/10.1145/3698587.3701359)** *(Ling Yue, Sixue Xing, Jintai Chen, Tianfan Fu)* BCB’2024
1. **[MedAgentGym: Training LLM Agents for Code-Based Medical Reasoning at Scale](https://arxiv.org/abs/2506.04405)** *(Ran Xu, Yuchen Zhuang, Yishan Zhong, Yue Yu, Xiangru Tang, Hang Wu, May D. Wang, Peifeng Ruan, Donghan Yang, Tao Wang, Guanghua Xiao, Carl Yang, Yang Xie, Wenqi Shi)* arXiv’2025

## Applications

### Clinical Diagnosis \& Decision Support
1. **[FineMedLM-o1: Enhancing Medical Reasoning Ability of LLM](https://arxiv.org/abs/2501.09213)** *Hongzhou Yu, Tianhao Cheng, Yingwen Wang, Wen He, Qing Wang, Ying Cheng, Yuejie Zhang, Rui Feng, Xiaobo Zhang* 2025
2. **[MedGround-R1: Advancing Medical Image Grounding via Spatial-Semantic Rewarded Group Relative Policy Optimization](https://www.arxiv.org/abs/2507.02994)** *(Huihui Xu, Yuanpeng Nie, Hualiang Wang, Ying Chen, Wei Li, Junzhi Ning, Lihao Liu, Hongqiu Wang, Lei Zhu, Jiyao Liu, Xiaomeng Li, and Junjun He)* 2025
3. **[HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs](https://arxiv.org/abs/2412.18925)** *Junying Chen, Zhenyang Cai, Ke Ji, Xidong Wang, Wanlong Liu, Rongsheng Wang, Jianye Hou, Benyou Wang* 2024
4. **[MedReason: Eliciting Factual Medical Reasoning Steps in LLMs via Knowledge Graphs](https://arxiv.org/abs/2504.00993)** *Juncheng Wu, Wenlong Deng, Xingxuan Li, Sheng Liu, Taomian Mi, Yifan Peng, Ziyang Xu, Yi Liu, Hyunjin Cho, Chang-In Choi, Yihan Cao, Hui Ren, Xiang Li, Xiaoxiao Li, Yuyin Zhou* 2025
5. **[ReasonMed: A 370K Multi-Agent Generated Dataset for Advancing Medical Reasoning](https://arxiv.org/abs/2506.09513)** *Yu Sun, Xingyu Qian, Weiwen Xu, Hao Zhang, Chenghao Xiao, Long Li, Yu Rong, Wenbing Huang, Qifeng Bai, and Tingyang Xu.* 2025

### Medical Education \& Training
1. **[MEDCO: Medical education copilots based on a multiagent framework](https://arxiv.org/abs/2408.12496)** *Hao Wei, Jianing Qiu, Haibao Yu, and Wu Yuan.* 2024
2. **[Simulated patient systems are intelligent when powered by large language model-based AI agents](https://arxiv.org/abs/2409.18924)** *Huizi Yu, Jiayan Zhou, Lingyao Li, et al.* 2024
3. **[Clinicallab: Aligning agents for multi-departmental clinical diagnostics in the real world](https://arxiv.org/abs/2406.13890)** *Weixiang Yan, Haitian Liu, Tengxiao Wu, Qian Chen, Wen Wang, Haoyuan Chai, Jiayi Wang, Weishan Zhao, Yixin Zhang, Renjun Zhang, Li Zhu, and Xuandong Zhao.* 2024
4. **[Agent hospital: A simulacrum of hospital with evolvable medical agents](https://arxiv.org/abs/2405.02957)** *Junkai Li, Siyu Wang, Meng Zhang, Weitao Li, Yunghwei Lai, Xinhui Kang, Weizhi Ma, and Yang Liu.* 2024
5. **[AI Hospital: Benchmarking large language models in a multi-agent medical interaction simulator](https://arxiv.org/abs/2402.09742)** *Zhihao Fan, Jialong Tang, Wei Chen, Siyuan Wang, Zhongyu Wei, Jun Xi, Fei Huang, and Jingren Zhou.* 2024


### Medical Imaging Analysis \& Reasoning
1. **[Image Aesthetic Reasoning: A New Benchmark for Medical Image Screening with MLLMs]()** *Zheng Sun, Yi Wei, Long Yu* 2025
2. **[AOR: Anatomical Ontology-Guided Reasoning for Medical Large Multimodal Model in Chest X-Ray Interpretation](https://arxiv.org/abs/2505.02830)** *Qingqiu Li, Zihang Cui, Seongsu Bae, Jilan Xu, Runtian Yuan, Yuejie Zhang, Rui Feng, Quanli Shen, Xiaobo Zhang, Junjun He, Shujun Wang* 2025
3. **[PRS-Med: Position Reasoning Segmentation with Vision-Language Model in Medical Imaging](https://arxiv.org/abs/2505.11872)** *Quoc-Huy Trinh, Minh-Van Nguyen, Jung Peng, Ulas Bagci, Debesh Jha* 2025
4. **[GMAI-VL-R1: Harnessing Reinforcement Learning for Multimodal Medical Reasoning](https://arxiv.org/abs/2504.01886)** *Yanzhou Su, Tianbin Li, Jiyao Liu, Chenglong Ma, Junzhi Ning, Cheng Tang, Sibo Ju, Jin Ye, Pengcheng Chen, Ming Hu, Shixiang Tang, Lihao Liu, Bin Fu, Wenqi Shao, Xiaowei Hu, Xiangwen Liao, Yuanfeng Ji, Junjun He* 2025
5. **[Med-R1: Reinforcement Learning for Generalizable Medical Reasoning in Vision-Language Models](https://arxiv.org/abs/2503.13939)** *Yuxiang Lai, Jike Zhong, Ming Li, Shitian Zhao, Xiaofeng Yang* 2025
6. **[Med-RLVR: Emerging Medical Reasoning from a 3B base model via reinforcement Learning](https://arxiv.org/abs/2502.19655)** *Sheng Zhang, Qianchu Liu, Guanghui Qin, Tristan Naumann, Hoifung Poon* 2025
7. **[MedVLM-R1: Incentivizing Medical Reasoning Capability of Vision-Language Models (VLMs) via Reinforcement Learning](https://arxiv.org/abs/2502.19634)** *Jiazhen Pan, Che Liu, Junde Wu, Fenglin Liu, Jiayuan Zhu, Hongwei Bran Li, Chen Chen, Cheng Ouyang, Daniel Rueckert* MICCAI'25
8. **[MedGround-R1: Advancing Medical Image Grounding via Spatial-Semantic Rewarded Group Relative Policy Optimization]()** *(Huihui Xu, Yuanpeng Nie, Hualiang Wang, Ying Chen, Wei Li, Junzhi Ning, Lihao Liu, Hongqiu Wang, Lei Zhu, Jiyao Liu, Xiaomeng Li, and Junjun He)* 2025

### Drug \& Molecular Discovery
1. **[DrugAgent: Automating AI-aided Drug Discovery Programming through LLM Multi-Agent Collaboration](https://arxiv.org/abs/2411.15692)** *Sizhe Liu, Yizhou Lu, Siyu Chen, Xiyang Hu, Jieyu Zhao, Yingzhou Lu, Yue Zhao* 2024
2. **[Augmenting large language models with chemistry tools](https://www.nature.com/articles/s42256-024-00832-8)** *Andres M Bran, Sam Cox, Oliver Schilter, Carlo Baldassari, Andrew D White, Philippe Schwaller* Nature Machine Intelligence 2024

### Treatment Planning
1. **[Medical World Model: Generative Simulation of Tumor Evolution for Treatment Planning](https://arxiv.org/abs/2506.02327)** *Yijun Yang, Zhao-Yang Wang, Qiuping Liu, Shuwen Sun, Kang Wang, Rama Chellappa, Zongwei Zhou, Alan Yuille, Lei Zhu, Yu-Dong Zhang, Jieneng Chen* 2025
2. **[Automated radiotherapy treatment planning guided by GPT-4Vision](https://arxiv.org/abs/2406.15609)** *Sheng Liu, Oscar Pastor-Serrano, Yizheng Chen, Matthew Gopaulchan, Weixing Liang, Mark Buyyounouski, Erqi Pollom, Quynh-Thu Le, Michael Gensheimer, Peng Dong, Yong Yang, James Zou, Lei Xing* 2024
3. **[Quantifying the reasoning abilities of LLMs on real-world clinical cases.](https://arxiv.org/abs/2503.04691)** *Pengcheng Qiu, Chaoyi Wu, Shuyu Liu, Weike Zhao, Zhuoxia Chen, Hongfei Gu, Chuanjin Peng, Ya Zhang, Yanfeng Wang, and Weidi Xie.* 2025


## Evaluation \& Benchmarking

### Answer Accuracy Assessment
1. MedQA:**[What Disease does this Patient Have? A Large-scale Open Domain Question Answering Dataset from Medical Exams](https://arxiv.org/abs/2009.13081)** *Di Jin, Eileen Pan, Nassim Oufattole, Wei-Hung Weng, Hanyi Fang, Peter Szolovits* 2020
2. **[PubMedQA: A Dataset for Biomedical Research Question Answering](https://arxiv.org/abs/1909.06146)** *Qiao Jin, Bhuwan Dhingra, Zhengping Liu, William W. Cohen, Xinghua Lu* EMNLP'2019
3. **[MedXpertQA: Benchmarking Expert-Level Medical Reasoning and Understanding](https://arxiv.org/abs/2501.18362)** *Yuxin Zuo, Shang Qu, Yifei Li, Zhangren Chen, Xuekai Zhu, Ermo Hua, Kaiyan Zhang, Ning Ding, Bowen Zhou* ICML'25
4. **[MedAgentsBench: Benchmarking Thinking Models and Agent Frameworks for Complex Medical Reasoning](https://arxiv.org/abs/2503.07459)** *Xiangru Tang, Daniel Shao, Jiwoong Sohn, Jiapeng Chen, Jiayi Zhang, Jinyu Xiang, Fang Wu, Yilun Zhao, Chenglin Wu, Wenqi Shi, Arman Cohan, Mark Gerstein* 2025
5. **[MedMCQA: A Large-scale Multi-Subject Multi-Choice Dataset for Medical domain Question Answering](https://arxiv.org/abs/2203.14371)** *Ankit Pal, Logesh Kumar Umapathi, Malaikannan Sankarasubbu* PMLR'22
6. **[Measuring Massive Multitask Language Understanding](https://arxiv.org/abs/2009.03300)** *Dan Hendrycks, Collin Burns, Steven Basart, Andy Zou, Mantas Mazeika, Dawn Song, Jacob Steinhardt* ICLR'21
### Reasoning Quality Assessment
1. MedR-Bench:**[Quantifying the reasoning abilities of LLMs on real-world clinical cases.](https://arxiv.org/abs/2503.04691)** *Pengcheng Qiu, Chaoyi Wu, Shuyu Liu, Weike Zhao, Zhuoxia Chen, Hongfei Gu, Chuanjin Peng, Ya Zhang, Yanfeng Wang, and Weidi Xie* 2025
2. RadRScore:**[ChestX-Reasoner: Advancing Radiology Foundation Models with Reasoning through Step-by-Step Verification](https://arxiv.org/abs/2504.20930)** *Ziqing Fan, Cheng Liang, Chaoyi Wu, Ya Zhang, Yanfeng Wang, Weidi Xie* 2025
3. **[HealthBench: Evaluating Large Language Models Towards Improved Human Health](https://arxiv.org/abs/2505.08775)** *OpenAI* 2025
4. **[AgentClinic: a multimodal agent benchmark to evaluate AI in simulated clinical environments](https://arxiv.org/abs/2405.07960)** *Samuel Schmidgall, Rojin Ziaei, Carl Harris, Eduardo Reis, Jeffrey Jopling, Michael Moor* 2024
5. **[Sequential Diagnosis with Language Models](https://arxiv.org/abs/2506.22405)** *MicroSoft* 2025

### Visual Interpretability Assessment
1. **[PRS-Med: Position Reasoning Segmentation with Vision-Language Model in Medical Imaging](https://arxiv.org/abs/2505.11872)** *Quoc-Huy Trinh, Minh-Van Nguyen, Jung Peng, Ulas Bagci, Debesh Jha* 2025
2. **RJUA-MedDQA
3. **[GEMeX: A Large-Scale, Groundable, and Explainable Medical VQA Benchmark for Chest X-ray Diagnosis](https://arxiv.org/abs/2411.16778)** *Bo Liu, Ke Zou, Liming Zhan, Zexin Lu, Xiaoyu Dong, Yidi Chen, Chengqiang Xie, Jiannong Cao, Xiao-Ming Wu, Huazhu Fu* ICCV'25
4. **[AOR: Anatomical Ontology-Guided Reasoning for Medical Large Multimodal Model in Chest X-Ray Interpretation](https://arxiv.org/abs/2505.02830)** *Qingqiu Li, Zihang Cui, Seongsu Bae, Jilan Xu, Runtian Yuan, Yuejie Zhang, Rui Feng, Quanli Shen, Xiaobo Zhang, Junjun He, Shujun Wang* 2025

## Other Resources



## Contributing

We welcome contributions!

1. Fork this repo \& create a branch
2. Edit the appropriate section in `README.md`
3. Follow existing format:

```markdown
1. **[Paper Title](link)** *(Authors).* Year  
```

4. Submit a Pull Request.

## License \& Citation

Licensed under **MIT License**.

If you use this resource, please cite:

```bibtex
@misc{Wang2025MedicalReasoningSurvey,
      title={Medical Reasoning in the Era of LLMs: A Systematic Review of Enhancement Techniques and Applications}, 
      author={Wenxuan Wang and Zizhan Ma and Meidan Ding and Shiyi Zheng and Shengyuan Liu and Jie Liu and Jiaming Ji and Wenting Chen and Xiang Li and Linlin Shen and Yixuan Yuan},
      year={2025},
      eprint={2508.00669},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2508.00669}, 
}
```

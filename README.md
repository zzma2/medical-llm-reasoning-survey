<h1 align="center">Awesome Medical-Reasoning LLMs</h1>

<p align="center">
  <b>A curated list of papers, benchmarks, and resources for medical reasoning in large language models (LLMs)</b>
</p>
<details>
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

- **Medical Reasoning in the Era of LLMs: A Systematic Review of Enhancement Techniques and Applications**
  *Wenxuan Wang, Zizhan Ma, Meidan Ding, Shiyi Zheng, Shengyuan Liu, Jie Liu, Jiaming Ji, Wenting Chen, Xiang Li, Linlin Shen, Yixuan Yuan* Preprint'25
    - PDF: `survey-paper.pdf`

## Various Modalities

### Reasoning over Text
1. **[Reasoning Like a Doctor: Improving Medical Dialogue Systems via Diagnostic Reasoning Process Alignment](https://arxiv.org/abs/2406.13934)** *(Kaishuai Xu, Yi Cheng, Wenjun Hou, Qiaoyu Tan, Wenjie Li).* 2024  
2. **[MedReason: Eliciting Factual Medical Reasoning Steps in LLMs via Knowledge Graphs](https://arxiv.org/abs/2504.00993)** *(Juncheng Wu et al.).* 2025  
3. **[MedEx: Enhancing Medical Question-Answering with First-Order Logic Based Reasoning and Knowledge Injection](https://aclanthology.org/2025.coling-main.649/)** *(Aizan Zafar, Kshitij Mishra, Asif Ekbal).* 2025  
4. **[Med-RLVR: Emerging Medical Reasoning from a 3B Base Model via Reinforcement Learning](https://arxiv.org/abs/2502.19655)** *(Sheng Zhang et al.).* 2025  
5. **[Beyond Distillation: Pushing the Limits of Medical LLM Reasoning with Minimalist Rule-Based RL](https://arxiv.org/abs/2505.17952)** *(Che Liu et al.).* 2025  
6. **[M1: Unleash the Potential of Test-Time Scaling for Medical Reasoning with Large Language Models](https://arxiv.org/abs/2504.00869)** *(Xiaoke Huang et al.).* 2025  
7. **[FineMedLM-O1: Enhancing the Medical Reasoning Ability of LLM from Supervised Fine-Tuning to Test-Time Training](https://arxiv.org/abs/2501.09213)** *(Hongzhou Yu et al.).* 2025  
8. **[MedAdapter: Efficient Test-Time Adaptation of Large Language Models Towards Medical Reasoning](https://aclanthology.org/2024.emnlp-main.1244.pdf)** *(Wenqi Shi et al.).* 2024  
9. **[ArgMed-Agents: Explainable Clinical Decision Reasoning with LLM Discussion via Argumentation Schemes](https://arxiv.org/abs/2403.06294)** *(Shengxin Hong et al.).* 2024  
10. **[MedAgents: Large Language Models as Collaborators for Zero-Shot Medical Reasoning](https://aclanthology.org/2024.findings-acl.33.pdf)** *(Xiangru Tang et al.).* 2024  



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



### Reinforcement Learning
    


## Test-Time Techniques

### Prompt-Based Elicitation

1. **[Large Language Models are Clinical Reasoners: Reasoning-Aware Diagnosis Framework with Prompt-Generated Rationales](https://arxiv.org/abs/2312.07399)** *(Taeyoon Kwon, Kai Tzu-iunn Ong, Dongjin Kang, Seungjun Moon, Jeong Ryong Lee, Dosik Hwang, Yongsik Sim, Beomseok Sohn, Dongha Lee, Jinyoung Yeo).* AAAI'24

### Reasoning Selection \& Aggregation



### Knowledge Enhancement



### Multi-Agent Systems



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

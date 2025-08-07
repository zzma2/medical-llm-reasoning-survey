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



### Medical Education \& Training



### Medical Imaging Analysis \& Reasoning



### Drug \& Molecular Discovery



### Treatment Planning



## Evaluation \& Benchmarking



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

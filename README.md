<div align="center">
<h1> OmniInsert: Mask-Free Video Insertion of Any Reference via Diffusion Transformer Models </h1>

<a href="https://arxiv.org/abs/2509.17627"><img src="https://img.shields.io/badge/arXiv%20paper-2509.08519-b31b1b.svg"></a>
<a href="https://phantom-video.github.io/OmniInsert/"><img src="https://img.shields.io/badge/Project_page-More_visualizations-green"></a>

[Jinshu Chen](https://openreview.net/profile?id=~Jinshu_Chen2)<sup> * </sup>, [Xinghui Li](https://github.com/Crayon-Shinchan)<sup> * &dagger; </sup>, [Xu Bai](https://openreview.net/profile?id=~Baixu1)<sup> * </sup>, [Tianxiang Ma](https://tianxiangma.github.io/), [Pengze Zhang](https://openreview.net/profile?id=%7EPengze_Zhang1), <br>[Zhuowei Chen](https://scholar.google.com/citations?user=ow1jGJkAAAAJ), [Gen Li](https://scholar.google.com/citations?user=wqA7EIoAAAAJ), [Lijie Liu](https://liulj13.github.io/), [Songtao Zhao](https://openreview.net/profile?id=~Songtao_Zhao1)<sup> &dagger; </sup>, [Bingchuan Li](https://scholar.google.com/citations?user=ac5Se6QAAAAJ)<sup> &ddagger; </sup>, [Qian He](https://scholar.google.com/citations?user=9rWWCgUAAAAJ)<br>
<sup> * </sup>Equal contribution, <sup> &dagger; </sup>Corresponding author, <sup> &ddagger; </sup>Project lead 

Intelligent Creation Lab, ByteDance

</div>

## 📃 Abstract
Recent advances in video insertion based on diffusion models are impressive. However, existing methods rely on complex control signals but struggle with subject consistency, limiting their practical applicability. In this paper, we focus on the task of <b><i>Mask-free Video Insertion</i></b>, and aim to resolve three key challenges: data scarcity, subject–scene equilibrium, and insertion harmonization. To address the data scarcity, we propose a new data pipeline <b><i>InsertPipe</i></b>, constructing diverse cross-pair data automatically. Building upon our data pipeline, we develop <b><i>OmniInsert</i></b>, a novel unified framework for mask-free video insertion from both single and multiple subject references. Specifically, to maintain subject-scene equilibrium, we introduce a simple yet effective Condition-Specific Feature Injection mechanism to distinctly inject multi-source conditions and propose a novel Progressive Training strategy that enables the model to balance feature injection from subjects and source video. Meanwhile, we design the Subject-Focused Loss to improve the detailed appearance of the subjects. To further enhance insertion harmonization, we propose an Insertive Preference Optimization methodology to optimize the model by simulating human preferences, and incorporate a Context-Aware Rephraser module during reference to seamlessly integrate the subject into the original scenes. To address the lack of a benchmark for the field, we introduce <b><i>InsertBench</i></b>, a comprehensive benchmark comprising diverse scenes with meticulously selected subjects. Evaluation on InsertBench indicates <b>OmniInsert</b> outperforms state-of-the-art closed-source commercial solutions.

<p align="center">
<img src="assets/teaser.png" width=95%>
<p>

## 🔥 Latest News

* Sep 23, 2025: We release the [Project Page](https://phantom-video.github.io/OmniInsert/) and [Technique Report](https://arxiv.org/abs/2509.17627) of **OmniInsert**.


## 📑 Todo List
- [x] Release Paper
- [ ] Release InsertBench
- [ ] Inference Codes


## ⭐ Citation

If OmniInsert is helpful, please help to ⭐ the repo.

If you find this project useful for your research, please consider citing our [paper](https://arxiv.org/abs/2509.08519).

### BibTeX
```bibtex
@misc{chen2025omniinsert,
      title={OmniInsert: Mask-Free Video Insertion of Any Reference via Diffusion Transformer Models}, 
      author={Jinshu Chen and Xinghui Li and Xu Bai and Tianxiang Ma and Pengze Zhang and Zhuowei Chen and Gen Li and Lijie Liu and Songtao Zhao and Bingchuan Li and Qian He},
      year={2025},
      eprint={2509.17627},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2509.17627}, 
}
```

## 📧 Contact
If you have any comments or questions regarding this open-source project, please open a new issue or contact [Jinshu Chen](https://openreview.net/profile?id=~Jinshu_Chen2) and [Xinghui Li](li-xh21@tsinghua.org.cn).

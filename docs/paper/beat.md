# BEAT: A Large-Scale Semantic and Emotional Multi-Modal Dataset for Conversational Gestures Synthesis

随着元宇宙的火爆以及数字人建模技术的商业化，AI 数字人驱动算法，作为数字人动画技术链的下一关键环节，获得了学界和工业界越来越广泛的兴趣和关注。其中**谈话动作生成**（由声音等控制信号生成肢体和手部动作）由于可以降低 VR Chat、虚拟直播、游戏 NPC 等场景下的驱动成本，在近两年成为研究热点。

然而，由于缺乏开源数据，现有的模型往往在由姿态检测算法提供的伪标签数据集或者单个说话人的小规模动捕数据集上进行测试。由于数据量、数据标注的缺乏和数据质量的限制，现有的算法很难生成**个性化、高手部质量、情感相关、动作-语义相关**的动作。

针对上述问题，**华为东京研究所 - Digital Human Lab** 与**东京大学**等合作进行了研究，提出了目前为止最大规模的数字人多模态数据集：**BEAT**（Body-Expression-Audio-Text），由 **76 小时**动捕设备采集的谈话数据和语义-情感标注组成。原始数据包含：

- 肢体和手部动捕数据  
- AR Kit 标准 52 维面部 blendshape 权重  
- 音频与文本  

标注数据包含：

- 8 类情感分类标签  
- 动作类型分类  
- 语义相关度打分  

在 BEAT 的基础上提出的新基线模型 **CaMN (Cascade-Motion-Network)** 采取级联神经网络结构，由 BEAT 中其余三种模态和标注作为输入，在动作生成任务上显著优于现有 SoTA (state-of-the-art) 算法。

论文《**BEAT: A Large-Scale Semantic and Emotional Multi-Modal Dataset for Conversational Gestures Synthesis**》已于 **ECCV2022** 上发表，数据集已经开源。

**作者**: Haiyang Liu, Zihao Zhu, Naoya Iwamoto, Yichen Peng, Zhengqing Li, You Zhou, Elif Bozkurt, Bo Zheng  

**单位**：Digital Human Lab - 华为东京研究所，东京大学，庆应大学，北陆先端科技大学  

**论文地址**：[https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136670605.pdf](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136670605.pdf)  

**项目主页**：[https://pantomatrix.github.io/BEAT/](https://pantomatrix.github.io/BEAT/)  

**数据集主页**：[https://pantomatrix.github.io/BEAT-Dataset/](https://pantomatrix.github.io/BEAT-Dataset/)  

**视频结果**：[https://www.youtube.com/watch?v=F6nXVTUY0KQ](https://www.youtube.com/watch?v=F6nXVTUY0KQ)


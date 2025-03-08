# Open-World Drone Active Tracking with Goal-Centered Rewards
[![Software License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![Document-en](https://img.shields.io/badge/doc-guide-blue)](https://foriccv2025.github.io/anonymous/)
[![Document-zh](https://img.shields.io/badge/文档-指引-blue)](https://foriccv2025.github.io/anonymous/zh/index.html)

![cover1](./readmeCache/cover1.png)
![cover](./readmeCache/cover.gif)

## Abstract
Drone Visual Active Tracking aims to autonomously follow a target object by controlling the motion system based on visual observations, providing a more practical solution for effective tracking in dynamic environments. However, accurate Drone Visual Active Tracking using reinforcement learning remains challenging due to the absence of a unified benchmark and the complexity of open-world environments with frequent interference. To address these issues, we pioneer a systematic solution. First, we propose **DAT**, the first open-world drone active air-to-ground tracking benchmark. It encompasses 24 city-scale environments, featuring targets with human-like behaviors and decision-making capabilities. DAT also comprehensively models 7 critical challenges in real-world scenarios. Additionally, we propose a novel reinforcement learning method called **GC-VAT**, which aims to improve the performance of drone tracking targets in complex scenarios. Specifically, we design a Goal-Centered Reward to provide precise feedback across viewpoints to the agent, enabling it to expand perception and movement range through unrestricted perspectives. Inspired by curriculum learning, we introduce a Curriculum-Based Training strategy that progressively enhances the agent tracking performance in complex environments. Besides, experiments on simulator and real-world images demonstrate the superior performance of \methodname, achieving an approximately 400\% improvement over the SOTA methods in terms of the cumulative reward metric.

## Citing
```bibtex
@article{ ,
  title={Open-World Drone Active Tracking with Goal-Centered Rewards},
  author={},
  journal={},
  year={},
  publisher={}
}
```

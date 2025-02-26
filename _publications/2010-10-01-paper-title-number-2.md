---
title: "Guiding VLM Agents with Process Rewards at Inference Time for GUI Navigation"
collection: publications
category: manuscripts
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: ''
date: 2010-10-01
venue: 'Under Review'
slidesurl: ''
paperurl: ''
citation: 'Zhiyuan Hu, Shiyun Xiong, Yifan Zhang, See-Kiong Ng, Anh Tuan Luu, Bo An, YAN Shuicheng, Bryan Hooi'
---

Recent advancements in visual language models (VLMs) have notably enhanced their capabilities in handling complex Graphical User Interface (GUI) interaction tasks. 
Despite these improvements, current frameworks often struggle to generate correct actions in challenging GUI environments.
State-of-the-art commercial VLMs are black-boxes, and fine-tuning open-source VLMs for GUI tasks requires significant resources.
 Additionally, existing trajectory-level evaluation and refinement techniques frequently fall short due to delayed feedback and local optimization issues. 
To address these challenges, we propose an approach that guides VLM agents with process supervision by a reward model during GUI navigation and control at inference time. This guidance allows the VLM agent to optimize actions at each inference step, thereby improving performance in both static and dynamic environments. In particular, our method demonstrates significant performance gains in the GUI navigation task setting, achieving a 5\% improvement in action accuracy for static environments and a around 33\% increase in task success rate in dynamic environments. With further integration of trajectory reflection and retry mechanisms, we also demonstrate even greater enhancement in task success. 

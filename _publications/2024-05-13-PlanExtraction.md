---
title: "Multi-Resolution Planar Region Extraction for Uneven Terrains"
collection: publications
permalink: /publication/2024-05-13-PlanExtraction
excerpt: "This paper studies the problem of extracting planar regions in uneven terrains from unordered point cloud measurements. Such a problem is critical in various robotic applications such as robotic perceptive locomotion. While existing approaches have shown promising results in effectively extracting planar regions from the environment, they often suffer from issues such as low computational efficiency or loss of resolution. To address these issues, we propose a multi-resolution planar region extraction strategy in this paper that balances the accuracy in boundaries and computational efficiency."
date: 2024-05-13
venue: 'the IEEE International Conference on Robotics and Automation (ICRA)'
paperurl: ''
citation: 'Yinghan Sun, Linfang Zheng, Hua Chen, Wei Zhang, "Multi-Resolution Planar Region Extraction for Uneven Terrains," 2024 International Conference on Robotics and Automation (ICRA), Yokohama, Japan, 2024'
---

This paper studies the problem of extracting planar regions in uneven terrains from unordered point cloud measurements. Such a problem is critical in various robotic applications such as robotic perceptive locomotion. While existing approaches have shown promising results in effectively extracting planar regions from the environment, they often suffer from issues such as low computational efficiency or loss of resolution. To address these issues, we propose a multi-resolution planar region extraction strategy in this paper that balances the accuracy in boundaries and computational efficiency. Our method begins with a pointwise classification preprocessing module, which categorizes all sampled points according to their local geometric properties to facilitate multi-resolution segmentation. Subsequently, we arrange the categorized points using an octree, followed by an in-depth analysis of nodes to finish multi-resolution plane segmentation. The efficiency and robustness of the proposed approach are verified via synthetic and real-world experiments, demonstrating our method's ability to generalize effectively across various uneven terrains while maintaining real-time performance, achieving frame rates exceeding 35 FPS.

**[Paper](https://arxiv.org/pdf/2311.12562.pdf)**

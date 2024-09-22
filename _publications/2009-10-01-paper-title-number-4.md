---
title: "HoughLaneNet: Lane Detection with Deep Hough Transform and Dynamic Convolution"
collection: publications
category: manuscripts
permalink: /publication/cv-lane-detection
excerpt: 'We propose a hierarchical Deep Hough Transform (DHT) approach to improve performance in detecting heavily occluded or worn lane images.'
date: 2023-11-01
venue: 'Computers & Graphics'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/pdf/2307.03494'
citation: 'Zhang, J. Q., Duan, H. B., Chen, J. L., Shamir, A., & Wang, M. (2023). HoughLaneNet: Lane detection with deep hough transform and dynamic convolution. Computers & Graphics, 116, 82-92.'
---

The task of lane detection has garnered considerable attention in the field of autonomous driving due to its complexity. Lanes can present difficulties for detection, as they can be narrow, fragmented, and often obscured by heavy traffic. However, it has been observed that the lanes have a geometrical structure that resembles a straight line, leading to improved lane detection results when utilizing this characteristic. To address this challenge, we propose a hierarchical Deep Hough Transform (DHT) approach that combines all lane features in an image into the Hough parameter space. Additionally, we refine the point selection method and incorporate a Dynamic Convolution Module to effectively differentiate between lanes in the original image. Our network architecture comprises a backbone network, either a ResNet or Pyramid Vision Transformer, a Feature Pyramid Network as the neck to extract multi-scale features, and a hierarchical DHT-based feature aggregation head to accurately segment each lane. By utilizing the lane features in the Hough parameter space, the network learns dynamic convolution kernel parameters corresponding to each lane, allowing the Dynamic Convolution Module to effectively differentiate between lane features. Subsequently, the lane features are fed into the feature decoder, which predicts the final position of the lane. Our proposed network structure demonstrates improved performance in detecting heavily occluded or worn lane images, as evidenced by our extensive experimental results, which show that our method outperforms or is on par with state-of-the-art techniques.
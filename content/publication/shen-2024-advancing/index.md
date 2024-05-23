---
title: 'Advancing High-Precision Navigation: Leveraging Homogeneous Sensors in Tightly
  Coupled PPP-RTK/IMU Integration'
authors:
- Zhiheng Shen
- Xin Li
- Xingxing Li
date: '2024-01-01'
publishDate: '2024-05-13T03:20:30.844873Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Industrial Electronics*'
doi: 10.1109/TIE.2024.3363741
abstract: As Global Navigation Satellite Systems (GNSS) and inertial measurement units (IMUs) are gradually emerging as ubiquitous, utilizing redundant sensors to achieve accurate and robust large-scale navigation holds great promise. In this article, we propose a tightly coupled precise point positioning-real-time kinematic (PPP-RTK)/IMU system with multiple homogeneous sensors to enable high-precision and high-availability vehicle navigation. In it, a stacked Kalman filter is employed to fuse raw pseudorange and carrier phase measurements from all GNSS terminals, driven by a core IMU designated randomly. In PPP-RTK processing, precise atmospheric and bias corrections from a GNSS server are leveraged to quickly resolve carrier phase ambiguity, thus ensuring centimeter-level positioning. Besides, rotation and translation constraints from redundant IMUs are imposed on the estimation pipeline to further improve the state estimation. Real-world experiments show that the proposed method can achieve an availability of 98.7% (horizontal position error < 0.1 m) in a half-open-sky case, which is far better than the state-of-the-art methods. Also, redundant sensors not only contribute significantly to the integer ambiguity resolution, but are also able to promise continuous state estimation in the case of sensor failure.
tags: 
- GNSS
- IMU
- Sensor Fusion
---

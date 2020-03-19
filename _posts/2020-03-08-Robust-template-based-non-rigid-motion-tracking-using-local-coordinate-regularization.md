---
title: "Robust Template-Based Non-Rigid Motion Tracking Using Local Coordinate Regularization"
header:
  overlay_color: "#333"
categories:
  - Layout
  - Uncategorized
tags:
  - publication
---

Wei Li, **Shang Zhao**, Xiao Xiao, James Hahn

_WACV 2020_


# Abstract
In this paper, we propose our template-based non-rigid registration algorithm to address the misalignments in the frame-to-frame motion tracking with single or multiple commodity depth cameras. We analyze the deformation in the local coordinates of neighboring nodes and use this differential representation to formulate the regularization term for the deformation field in our non-rigid registration. The local coordinate regularizations vary for each pair of neighboring nodes based on the tracking status of the surface regions. We propose our tracking strategies for different surface regions to minimize misalignments and reduce error accumulation. This method can thus preserve local geometric features and prevent undesirable distortions. Moreover, we introduce a geodesic-based correspondence estimation algorithm to align surfaces with large displacements. Finally, we demonstrate the effectiveness of our proposed method with detailed experiments.

[[PDF]](http://openaccess.thecvf.com/content_WACV_2020/papers/Li_Robust_Template-Based_Non-Rigid_Motion_Tracking_Using_Local_Coordinate_Regularization_WACV_2020_paper.pdf)
---
title: "Projects"
classes: wide
excerpt: "Highlight of my research moments"
sitemap: false
permalink: /projects/
---

## Research Projects

---
### Enhancing Medical Skill Training Through Computer Simulation and Automated Evaluation [NIH R01 Project]

> **Neonatal endotracheal intubation (ETI)** is a time-sensitive resuscitation procedure essential that requires tremendous practice of trainees before clinical exposure. However, current manikin-based training regimen is ineffective in providing satisfactory real-time procedural guidance for accurate assessment due to the lack of see-through visualization within the manikin. The training efficiency is further reduced by the limited availability of expert instructors, which inevitably results in a long learning curve for trainees. 

#### Intelligent Augmented Reality Solution (AI + AR)

<figure>
  <img src="/assets/publication_imgs/ismar2020.png" alt="AI+AR simulator">
</figure>
<b><a href="https://youtu.be/yPWMaWrGi9w">The intelligent augmented reality training framework</a></b> is a new training paradigm which integrates AR visualization with an interpretable machine learning model to address the critical issues in the current training regimen. It has the potential to improve the training efficiency as well as facilitate the development of automated medical skill training.

<figure>
  <img src="/assets/research_imgs/ar+ai_pipeline.png" alt="AI+AR pipeline">
</figure>
The hardware includes manikin-based task trainer, a HoloLens and electromagnetic motion sensors. The distributed framework is comprised of calibration module, communication module, assessment module, and visualization module The motion tracking module captures the motion of instruments. AR visualization offers superimposed see-through visualization after system calibration. The server-client framework remotely connects AR headsets and the server computer, which has the potential to support multiple AR devices simultaneously for varying educational scenarios.   

<figure>
  <img src="/assets/research_imgs/net_arch_cnn_cbam_revise.png" alt="intelligent model">
</figure>
The intelligent AR training framework used an attention-based dilated CNN for real-time performance evaluation and localization of motion regions that need more practice. Experimental results show that the attention mechanism can better identify more discriminative motion patterns during the inference. 

#### Virtual Reality Solution

<figure>
  <img src="/assets/research_imgs/vr_simulator.png" alt="Virtual reality simulator">
</figure>
<b>The virtual reality intubation training framework</b> offers immersive training experiences with real-time physics-based simulation. The user can interact with simulation by manipulating the haptic device (for laryngoscope) and an electromagnetic motion sensor (for endotracheal tube). All aspects of performance parameters can be captured and visualized during the procedure. 

<figure>
  <img src="/assets/research_imgs/vr_system_overview.png" alt="VR framework overview">
</figure>
The simulation framework consists of a main simulation module, an object representation module (object class) and an I/O device module (sensor class). The main simulation module contains the simulation functions and processes the dynamics of objects (deformable or rigid-body dynamics) and their communication with each other. Each object is decomposed into various representations where each representation is more suited toward a particular task - modeling, collision detection and visualization. These representations are linked together so they can be updated coherently. In this way, objects in the PBD layer are able to communicate with objects in the rigid-body dynamics layer. 

---
### Accurate 3D Human Body Reconstruction System for Medical Purpose [Part of NIH R21 Project]
>In the last decade, 3D modeling industry enjoyed booming development in both hardware and software. However, there is no easy access for public to high-level medical grade scan system to scan themselves and get feedback with their health data, because systems designed for medical institutions are typically expensive, immobile and require trained professionals to operate.


<figure>
  <img src="/assets/research_imgs/bodyfat_setup1.png" alt="bodyfat system setup">
</figure>
We present a cost-efficient easy to use 3D human body scan system for medical applications using entertainment level depth sensors which provide reconstruction result with high degree of accuracy and reliability. 

<figure>
  <img src="/assets/research_imgs/bodyfat_pipeline.png" alt="MoCap system setup">
</figure>
The reconstruction pipeline includes the following steps: (a) <b>Mesh preprocessing</b> generates high-resolution scan meshes from captured depth and color images. (b) <b>Skeleton inference</b> detects skeletal joint positions by multi-modality registration. (c-f) <b>Registration</b> aligns 3D body surfaces using non-rigid registration that consists of the following sub-steps: 1, we initially align partial meshes with rigid ICP with joint-based segmentation. 2, we deform partial scan meshes with regularization, including the articulated motion constraint and the global loop closure constraint. 3, the global nonrigid registration stitches the meshes to generate a watertight surface. 4, high-frequency details and texture are mapped  to the watertight surface.

---
### RGB-D Based Motion Capture System [NSF MRI Project]
>The proposed instrument is high-resolution both spatially and temporally, enabling spatial scanning at centimeter accuracies over large volumes, to millimeter accuracies over focused regions. In the temporal domain, the instrument is capable of real-time operation at 30 Hz; for sensors that operate at higher frequencies, the system still fuses data to produce a time-evolution of dense 3D model shape and appearance.

<figure>
  <img src="/assets/research_imgs/sys-cam.jpg" alt="MoCap system setup">
</figure>
The heterogeneous motion capture system includes 26 Vicon XM cameras, Velodyne LIDAR Sensor and 16 Microsoft Kinects V2. All sensor devices are registered to Vicon capture space, the global space.

<figure>
  <img src="/assets/research_imgs/VR integration.png" alt="VR integration">
</figure>
To produce rea-time captured immersive experiences, I developed VR integration module with <a href="https://www.steamvr.com/en/">OpenVR</a> and <a href="https://opencv.org/">OpenCV</a>. 

<figure>
  <img src="/assets/research_imgs/vrfusion.jpg" alt="VR integration">
</figure>
The virtual content can be rendered in real-time, offering interactions with VR system. In addition, the system also delivers real-time immersive rendering from different camera views. 



<figure>
  <img src="/assets/research_imgs/deformation_proxy.png">
</figure>
For articulated motion capture, the human skeleton can be either explicitly defined by attached markers or implicitly defined by volumetric embedded deformation graph. 

<figure>
  <img src="/assets/research_imgs/WACV20-poster-0089.png">
</figure>
The non-rigid templated-based motion tracking pipeline analyzes the deformation in the local coordinates of neighboring nodes and use this differential representation to formulate the regularization term for the deformation field in the proposed non-rigid registration. The large deformation caused by fast movements can be addressed by the proposed geodesic-based correspondence estimation and region-based surface matching algorithms. 

---


<!-- | Name                                        | Description                                           |
| ------------------------------------------- | ----------------------------------------------------- |
| [Post with Header Image][header-image-post] | A post with a large header image. |
| [HTML Tags and Formatting Post][html-tags-post] | A variety of common markup showing how the theme styles them. |
| [Syntax Highlighting Post][syntax-post] | Post displaying highlighted code. |
| [Post with a Gallery][gallery-post] | A post showing several images wrapped in `<figure>` elements. |
| [Sample Collection Page][sample-collection] | Single page from a collection. |
| [Categories Archive][categories-archive] | Posts grouped by category. |
| [Tags Archive][tags-archive] | Posts grouped by tag. |


---

Minimal Mistakes is designed, developed, and maintained by Michael Rose. Just another boring, tattooed, designer from Buffalo New York. -->
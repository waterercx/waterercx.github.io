---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Welcome to my personal website! I received my bachelor's degree from Xi'an Jiaotong University in 2022 and my master's degree in Mechanical Engineering from Xiamen University in 2025. During my master's studies, under my advisor's supervision, I worked on topology optimization of vibration control, with a commitment to multifunctional lattices and the multiscale optimization of shell-infill structures. Through this work, I gained experience in topology optimization, computational mechanics, and additive manufacturing. I plan to pursue a PhD to further explore computational mechanics and structural design, while also learning about related research areas.

# 🔬 Research

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Structural and Multidisciplinary Optimization</div><img src='images/SMO_MMI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* We propose an interface-aware topology optimization framework for multi-material structures using density penalization. The method implicitly identifies transition interfaces between different materials, incorporates prescribed interfacial properties into the material interpolation, and enables explicit control of interface thickness, providing a unified approach for the design of multi-material structures with controllable interface behavior.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Mechanical Design</div><img src='images/JMD_NIAD_TO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* We propose NIAD-TO, a scalable topology optimization framework that integrates neural-implicit representations with discrete adjoint-driven gradients. By coupling PyTorch with FEniCS/dolfin-adjoint in an end-to-end framework, the method combines flexible neural representations with accurate physics-based sensitivities and is applicable to multimaterial, multiscale, multiphysics, and nonlinear topology optimization problems.

</div>
</div>

* An improved interpolation called the Solid Isotropic Material with Variable Penalization (SIMVP) is proposed in this work, which could suppress the pseudo modes in eigenvalue optimization problems. Different from the Solid Isotropic Material with Penalization (SIMP), the penalty is set as a function of the design variable to ensure the consistency of the interpolation  between the Young's modulus and the density, which would amplify the local mode effect in low-density areas to bring incorrect results. By integrating the successive staircase function, the stiffness of the low-density is compensated, eliminating the pseudo modes. The upper diagrams compare the curves between SIMP and SIMVP in the density interpolation, it is evident that the latter implements piecewise penalties and ensures the continuity and differentiability of functions. The lower diagrams illustrate the optimization of maximum fundamental frequency using SIMP and SIMVP, the former has stuck in a local optimum solution due to pseudo modes , while the latter have not seen the same problem.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Composite Structures</div><img src='images/CS_shell_infill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* In this work, we aimed to design lattices used for various functions, such as cushioning and thermal insulation. We investigated the mechanical properties of several sandwich structures incorporating truss or minimal surface lattices, and conducted thermal insulation tests. By utilizing homogenization methods, we calculated the effective material properties, enabling large-scale simulations. We also introduced the concept of programmable metamaterials, constructing a series of lattices with continuously varying Poisson's ratios for enhanced cushioning and resilience. Using coordinate transformations and Fourier series, we developed more complex lattice designs. Additionally, we considered Additive Manufacturing (AM) and Injection Molding (IM) constraints to ensure the manufacturability during the design phase. In order to simulate the resilience of the lattices, viscoelastic materials were applied. The use of implicit functions facilitated the design of multifunctional lattices from this work, making them more adaptable to practical applications.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Structural and Multidisciplinary Optimization</div><img src='images/SMO_shell_infill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* In this work, we proposed a method for predicting the remaining useful life (RUL) of rolling bearings of rolling bearings based on a Multi-scale Convolutional Neural Network (MS-CNN). By analyzing the energy variation trends of bearing vibration signals, we categorized the bearing's entire lifespan data into normal operation and fault degradation stages, setting RUL labels based on these different stages. Variational Mode Decomposition (VMD) was adopted to process the vibration signals, generating time-frequency representations (TFR) that served as input data for the neural network. The MS-CNN was used to extract deep features from the data. Regression was employed to establish the mapping relationship between the life labels and deep features. We have compared the prediction accuracy against linear regression and Support Vector Regression (SVR). The average absolute error of the linear regression predictions is around 1%, while the SVR method yielded an average absolute error of less than 0.5%, demonstrating superior predictive performance.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Mechanical Design</div><img src='images/JMD_inverse_infill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* In this project, we designed a kind of flexible gripper for fruit catching through a simple linkage mechanism. The gripper consists of three fingers, all made from flexible materials and designed with a grid-like structure to ensure conformity around the object. To ensure the coordinated movement of the fingers for effective object grasping, we designed a central lead screw mechanism to control. The electrical control programming and wiring connections were also completed in this project. An underactuated driving method was adopted, allowing for the grasping of small fruits through shape locking.

</div>
</div>

<div class="paper-box">

  <h2 class="project-showcase-title">Flexible gripper</h2>

  <div class="paper-box-image">
  <div><img src='images/CDIO.png' alt="sym" width="100%"></div>
  </div></div>
  <div class='paper-box-text' markdown="1">
* In this project, we designed a kind of flexible gripper for fruit catching through a simple linkage mechanism. The gripper consists of three fingers, all made from flexible materials and designed with a grid-like structure to ensure conformity around the object. To ensure the coordinated movement of the fingers for effective object grasping, we designed a central lead screw mechanism to control. The electrical control programming and wiring connections were also completed in this project. An underactuated driving method was adopted, allowing for the grasping of small fruits through shape locking.

</div>
</div>

  
# 📝 Publications 


- Yilong Zhang, **Chenxu Wang**, Siqi Wang, Cunfu Wang, Gengkai Hu. [Interface-aware topology optimization for multi-material structures via density penalization](https://link.springer.com/article/10.1007/s00158-026-04395-7). _Structural and Multidisciplinary Optimization_, 69(8), 196, 2026.
- Yilong Zhang, **Chenxu Wang**, Siqi Wang, Cunfu Wang, Gengkai Hu [A Scalable Topology Optimization Framework with Neural-Implicit Representation and Adjoint-Driven Gradients](https://www.researchgate.net/publication/407202147_A_Scalable_Topology_Optimization_Framework_with_Neural-Implicit_Representation_and_Adjoint-Driven_Gradients). _Journal of Mechanical Design_, 2026. 
- **Chenxu Wang**, Yilong Zhang, Wenyuan Yu, Shun Yang, Cunfu Wang, Shikai Jing. [Topology optimization of shell–infill structures for maximum stiffness and fundamental frequency](https://www.sciencedirect.com/science/article/abs/pii/S0263822325000443). _Composite Structures_, 356, 118879, 2025.
- Yilong Zhang, **Chenxu Wang**, Wenyuan Yu, Chunyan Zhang, Shikai Jing, Cunfu Wang. [Density penalty-based interface identification in shell–infill topology optimization](https://link.springer.com/article/10.1007/s00158-024-03871-2). _Structural and Multidisciplinary Optimization_, 67(8), 144,2024.
- Cunfu Wang, **Chenxu Wang**, Wenyuan Yu, Liming Lei, Cheng Yan, Yancheng You. [Achieving self-supported enclosed voids and machinable support structures in topology optimization for additive manufacturing](https://link.springer.com/article/10.1007/s00158-024-03858-z). _Structural and Multidisciplinary Optimization_, 67(8), 142, 2024.

  
# 🎖 Honors and Awards
- *Oct. 2026*, Fujian Provincial Outstanding Master's Thesis Award
- *Apr. 2025*, School-level Scholarship, Xiamen University
- *Dec. 2024*, National Scholarship, Xiamen University
- *Dec. 2021*, University-level Scholarship, Xi'an Jiaotong University
- *Dec. 2020*, SMC Industry Scholarship, Xi'an Jiaotong University

# 📖 Educations
* *Sep. 2022 – Jun. 2025*, Master of Mechanical Engineering, Xiamen University (XMU), Xiamen, China
* *Sep. 2018 – Jun. 2022*, Bachelor of Engineering, Xi'an Jiaotong University (XJTU), Xi'an, China


# 💬 Conference
* *Apr. 2024*, The 3rd National Academic Forum for Young Scholars in Mechanical Design, Shaoshan, China: only participate
- *Apr. 2023*, The 2023 Joint Academic Annual Conference of the Mechanics Societies of Fujian and Jiangxi Provinces, Putian, China: Oral Presentation
- *Apr. 2023*, The 15th National Symposium on Structural Vibration and Dynamics & the 3rd National Workshop on Impact and Protective Engineering, Xiamen, China: only participate


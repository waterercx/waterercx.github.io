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

Welcome to my academic homepage. My name is Yilong Zhang, and I am a motivated researcher currently pursuing a Ph.D. in the Division of Marine Science and Technology at Beijing Institute of Technology (2025–present), under the supervision of <a href="https://scholar.google.com/citations?hl=zh-CN&user=rtH1n44AAAAJ" target="_blank">Prof. Gengkai Hu</a>. My current research focuses on the design and applications of zero-energy mode metamaterials. I received my B.Eng. degree in Mechanical Engineering from Changchun University of Technology in 2021. From 2021 to 2024, I pursued my master’s degree in the Department of Power Engineering at Xiamen University. During my master’s studies, my research primarily focused on topology optimization and the design of programmable Poisson’s ratio metamaterials. I was supervised by <a href="https://scholar.google.com/citations?hl=zh-CN&user=ddL-8yMAAAAJ" target="_blank">Prof. Cunfu Wang</a> and <a href="https://aerospace.xmu.edu.cn/info/1623/41443.htm" target="_blank">Prof. Huageng Luo</a>, both of whom are affiliated with the Center for Advanced Mechanical Design and Data Analysis (<a href="https://www.researchgate.net/lab/CAMDDA-Huageng-Luo" target="_blank">CAMDDA</a>). In addition, from 2024 to 2025, I worked as an Assistant Engineer at Lingyun 18, where I was responsible for mechanical and hydraulic systems.

I specialize in solid mechanics and have extensive experience in numerical simulation and topology optimization. My current research focuses on the applications of elastic waves in solid mechanics.I am always open to academic discussions and look forward to potential research collaborations. If you are interested in my research or would like to explore possible opportunities for collaboration, please feel free to contact me via email at [zyl@bit.edu.cn](mailto:zyl@bit.edu.cn).


Welcome to my personal website! I received my bachelor's degree from Xi'an Jiaotong University in 2022 and my master's degree in Mechanical Engineering from Xiamen University in 2025. During my master's studies, under my advisor's supervision, I worked on topology optimization of vibration control, with a commitment to multifunctional lattices and the multiscale optimization of shell-infill structures. Through this work, I gained experience in topology optimization, computational mechanics, and additive manufacturing. I plan to pursue a PhD to further explore computational mechanics and structural design, while also learning about related research areas.

# 🔬 Research

<h2 class="project-showcase-title">Shell-infill structure optimization</h2>
<div class='paper-box'><div class='paper-box-image'><div><img src='images/shell-infill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* We proposed a Gaussian-function-based method for modeling shell–infill structures, in which a Gaussian function maps intermediate density fields to extract the shell geometry. The modeling framework incorporates two successive density-filtering steps within density-based topology optimization. The shell thickness is controlled by the Gaussian-function parameters and the radius of the partial differential equation (PDE) filter, and we established a quantitative relationship between these parameters. The upper panel illustrates the shell–infill modeling procedure, while the middle panels show the results of minimum-compliance topology optimization, demonstrating that the method can clearly delineate the shell geometry and yield physically reasonable designs.
* In a separate line of research, we developed a multiscale topology optimization framework for shell–infill structures filled with programmable metamaterials. By combining homogenization methods with deep neural networks (DNNs) as surrogate models for predicting the effective mechanical properties of homogenized unit cells, the framework enables efficient multiscale optimization. At the macroscale, it optimizes the spatial distributions of the shell structure and infill material, while at the microscale, it optimizes the spatial distributions of the design parameters governing programmable metamaterial unit cells. The framework was further extended to a multi-objective topology optimization formulation that simultaneously minimizes structural compliance and maximizes the fundamental frequency, targeting improved static stiffness and a higher fundamental frequency. The lower panels show representative results of the multiscale, multi-objective topology optimization of shell–infill structures.

</div>
</div>

<h2 class="project-showcase-title">Frequency-based optimization</h2>
<div class='paper-box'><div class='paper-box-image'><div><img src='images/frequency.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* An improved interpolation called the Solid Isotropic Material with Variable Penalization (SIMVP) is proposed in this work, which could suppress the pseudo modes in eigenvalue optimization problems. Different from the Solid Isotropic Material with Penalization (SIMP), the penalty is set as a function of the design variable to ensure the consistency of the interpolation  between the Young's modulus and the density, which would amplify the local mode effect in low-density areas to bring incorrect results. By integrating the successive staircase function, the stiffness of the low-density is compensated, eliminating the pseudo modes. The upper diagrams compare the curves between SIMP and SIMVP in the density interpolation, it is evident that the latter implements piecewise penalties and ensures the continuity and differentiability of functions. The lower diagrams illustrate the optimization of maximum fundamental frequency using SIMP and SIMVP, the former has stuck in a local optimum solution due to pseudo modes , while the latter have not seen the same problem.

</div>
</div>


<h2 class="project-showcase-title">Lattices design</h2>
<div class='paper-box'><div class='paper-box-image'><div><img src='images/lattice.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* This project focuses on the design, modeling, and optimization of multifunctional lattices for applications such as cushioning and thermal insulation. We investigated the mechanical properties of sandwich structures incorporating truss-based or minimal-surface lattices and conducted thermal insulation tests. Homogenization methods were employed to derive effective material properties for large-scale simulations. To enhance cushioning and rebound performance, we developed programmable metamaterials with continuously tunable Poisson's ratios and generated more complex lattice architectures using coordinate transformations and Fourier series. Additive manufacturing (AM) and injection molding (IM) constraints were incorporated into the design process to ensure manufacturability, while viscoelastic material models were used to simulate the rebound response of the lattices.
* Building on these developments, we further developed an enhanced implicit modeling framework for programmable multimaterial lattices. The framework integrates implicit unit-cell representations constructed using composite periodic functions with R-function-based Boolean operations. Combined with a Heaviside mapping function, this approach enables precise control over unit-cell topology and the spatial distribution of constituent materials using a finite set of design parameters. By tailoring material arrangements, the resulting lattices can be designed to enhance auxetic behavior or negative thermal expansion. Overall, the implicit modeling framework expands the design space of multifunctional lattices and facilitates the development of structures with tailored mechanical and thermal properties.
  
</div>
</div>

<h2 class="project-showcase-title">Remaining useful life prediction</h2>
<div class='paper-box'><div class='paper-box-image'><div><img src='images/undergraduate.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* In this work, we proposed a method for predicting the remaining useful life (RUL) of rolling bearings of rolling bearings based on a Multi-scale Convolutional Neural Network (MS-CNN). By analyzing the energy variation trends of bearing vibration signals, we categorized the bearing's entire lifespan data into normal operation and fault degradation stages, setting RUL labels based on these different stages. Variational Mode Decomposition (VMD) was adopted to process the vibration signals, generating time-frequency representations (TFR) that served as input data for the neural network. The MS-CNN was used to extract deep features from the data. Regression was employed to establish the mapping relationship between the life labels and deep features. We have compared the prediction accuracy against linear regression and Support Vector Regression (SVR). The average absolute error of the linear regression predictions is around 1%, while the SVR method yielded an average absolute error of less than 0.5%, demonstrating superior predictive performance.

</div>
</div>

<h2 class="project-showcase-title">Flexible gripper</h2>
<div class='paper-box'> <div class='paper-box-image'><div><img src='images/CDIO.png' alt="sym" width="100%"></div></div>
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


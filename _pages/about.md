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

* A two-parameter voxel modeling method is proposed for the finite element analysis of triply periodic minimal surface (TPMS) structures by jointly controlling element size and minimum Jacobian. The method improves mesh convergence, numerical accuracy, and computational efficiency and also demonstrates good applicability to graded TPMS structures.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Composite Structures</div><img src='images/CS_shell_infill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* A topology optimization framework is proposed for shell–infill structures considering both structural stiffness and fundamental frequency. A Gaussian-function-based approach is introduced for shell extraction and thickness control, while a variable-penalization interpolation scheme is developed to suppress pseudo modes in eigenfrequency optimization, enabling simultaneous optimization of static and dynamic structural performance.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Structural and Multidisciplinary Optimization</div><img src='images/SMO_shell_infill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* We propose a density penalty-based topology optimization method for shell–infill structures. By penalizing both solid and void phases, structural interfaces can be identified directly during optimization, while the shell thickness can be explicitly controlled through the density penalty and filtering parameters. The method is demonstrated in both 2D and 3D shell–infill design problems.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Mechanical Design</div><img src='images/JMD_inverse_infill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* We propose a periodic composite function (PCF)-based approach for designing architected materials with programmable Poisson's ratios. The method enables compact parametric representation of microstructures with both positive and negative Poisson's ratios while maintaining connectivity between neighboring cells, providing an efficient framework for inverse design and spatially varying mechanical properties.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASME IDETC/CIE</div><img src='images/IDETC_infill_NPR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

* We introduce a periodic composite function-based representation for the parametric design of microstructures with programmable Poisson's ratios. The framework provides a compact geometric description of architected microstructures and establishes the foundation for subsequent inverse design of architected materials with spatially programmable mechanical properties.

</div>
</div>

  
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Structural and Multidisciplinary Optimization</div><img src='images/SMO_MMI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Interface-Aware Topology Optimization for Multi-Material Structures via Density Penalization](https://link.springer.com/article/10.1007/s00158-026-04395-7)

**Yilong Zhang**, Chenxu Wang, Siqi Wang, Cunfu Wang, Gengkai Hu



</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Mechanical Design</div><img src='images/JMD_NIAD_TO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Scalable Topology Optimization Framework with Neural-Implicit Representation and Adjoint-Driven Gradients](https://www.researchgate.net/publication/407202147_A_Scalable_Topology_Optimization_Framework_with_Neural-Implicit_Representation_and_Adjoint-Driven_Gradients)

**Yilong Zhang**, Chenxu Wang, Siqi Wang, Cunfu Wang, Gengkai Hu

* We propose NIAD-TO, a scalable topology optimization framework that integrates neural-implicit representations with discrete adjoint-driven gradients. By coupling PyTorch with FEniCS/dolfin-adjoint in an end-to-end framework, the method combines flexible neural representations with accurate physics-based sensitivities and is applicable to multimaterial, multiscale, multiphysics, and nonlinear topology optimization problems.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Mechanics Based Design of Structures and Machines</div><img src='images/voxel.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Improved Finite Element Modeling Method for Triply Periodic Minimal Surface Structures Based on Element Size and Minimum Jacobian](https://www.tandfonline.com/doi/full/10.1080/15397734.2025.2605536)

Siqi Wang, Chuangyu Jiang, **Yilong Zhang**, Xiaodong Zhang, Baoqiang Zhang, Huageng Luo

* A two-parameter voxel modeling method is proposed for the finite element analysis of triply periodic minimal surface (TPMS) structures by jointly controlling element size and minimum Jacobian. The method improves mesh convergence, numerical accuracy, and computational efficiency and also demonstrates good applicability to graded TPMS structures.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Composite Structures</div><img src='images/CS_shell_infill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Topology Optimization of Shell–Infill Structures for Maximum Stiffness and Fundamental Frequency](https://www.sciencedirect.com/science/article/pii/S0263822325000443)

Chenxu Wang, **Yilong Zhang**, Wenyuan Yu, Shun Yang, Cunfu Wang, Shikai Jing

* A topology optimization framework is proposed for shell–infill structures considering both structural stiffness and fundamental frequency. A Gaussian-function-based approach is introduced for shell extraction and thickness control, while a variable-penalization interpolation scheme is developed to suppress pseudo modes in eigenfrequency optimization, enabling simultaneous optimization of static and dynamic structural performance.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Structural and Multidisciplinary Optimization</div><img src='images/SMO_shell_infill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Density Penalty-Based Interface Identification in Shell–Infill Topology Optimization](https://link.springer.com/article/10.1007/s00158-024-03871-2)

**Yilong Zhang**, Chenxu Wang, Wenyuan Yu, Chunyan Zhang, Shikai Jing, Cunfu Wang

* We propose a density penalty-based topology optimization method for shell–infill structures. By penalizing both solid and void phases, structural interfaces can be identified directly during optimization, while the shell thickness can be explicitly controlled through the density penalty and filtering parameters. The method is demonstrated in both 2D and 3D shell–infill design problems.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Mechanical Design</div><img src='images/JMD_inverse_infill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Periodic Composite Function-Based Approach for Designing Architected Materials With Programmable Poisson's Ratios](https://asmedigitalcollection.asme.org/mechanicaldesign/article-abstract/146/9/091704/1195172/Periodic-Composite-Function-Based-Approach-for?redirectedFrom=fulltext)

**Yilong Zhang**, Bifa Chen, Yuxuan Du, Ye Qiao, Cunfu Wang

* We propose a periodic composite function (PCF)-based approach for designing architected materials with programmable Poisson's ratios. The method enables compact parametric representation of microstructures with both positive and negative Poisson's ratios while maintaining connectivity between neighboring cells, providing an efficient framework for inverse design and spatially varying mechanical properties.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASME IDETC/CIE</div><img src='images/IDETC_infill_NPR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Periodic Composite Function-Based Designing of Microstructures With Programmable Poisson Ratio](https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-abstract/IDETC-CIE2022/86229/V03AT03A045/1150338)

**Yilong Zhang**, Yuxuan Du, Ye Qiao, Shu Wang, Cunfu Wang

* We introduce a periodic composite function-based representation for the parametric design of microstructures with programmable Poisson's ratios. The framework provides a compact geometric description of architected microstructures and establishes the foundation for subsequent inverse design of architected materials with spatially programmable mechanical properties.

</div>
</div>


# 📝 Under Review

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/MR-GVNO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GA-VINO: A Geometry-Aware Variational Physics-informed Neural Operator for Mindlin-Reissner Plates](https://arxiv.org/abs/2606.16624)

Siqi Wang, Daobo Sun, Yizheng Wang, **Yilong Zhang**, Yabin Jin, Xiaoying Zhuang, Timon Rabczuk

- We propose MR-GVNO, a geometry-aware physics-informed neural operator that enables label-free and efficient response prediction for Mindlin–Reissner plates with irregular geometries, heterogeneous materials, and varying loads.
</div>
</div>



# 📝 Reviewer

- Journal: Discover Artificial Intelligence
<!-- - Conference: Pacific Graphics 2026 -->

# 🎖 Honors and Awards
- *Jun. 2025*, Fujian Provincial Outstanding Master's Thesis Award
- *Jun. 2024*, The Best Paper Award in <a href="https://www.researchgate.net/lab/CAMDDA-Huageng-Luo" target="_blank">CAMDDA</a>

# 📖 Educations
* *Sep. 2025 – present*, Ph.D. in Mechanics, Zhuhai Campus, Beijing Institute of Technology (BIT), Zhuhai, China
* *Sep. 2021 – Jun. 2024*, Master’s Degree in Energy and Power, School of Aerospace Engineering, Xiamen University (XMU), Xiamen, China
* *Sep. 2017 – Jun. 2021*, Bachelor’s Degree in Mechanical Engineering, School of Mechatronic Engineering, Changchun University of Technology (CCUT), Changchun, China


# 💬 Conference
* *May 2026*, The 5th China Metamaterials Conference (CMMC 2026), Jinan, China: only participate
- *Apr. 2023*, The 2023 Joint Academic Annual Conference of the Mechanics Societies of Fujian and Jiangxi Provinces, Putian, China: Oral Presentation
- *Apr. 2023*, The 15th National Symposium on Structural Vibration and Dynamics & the 3rd National Workshop on Impact and Protective Engineering, Xiamen, China: only participate
- *Nov. 2022*, The 18th China CAE Annual Conference (CCAC 2022), Xiamen, China: only participate
- *Aug. 2022*, ASME 2022 International Design Engineering Technical Conferences & Computers and Information in Engineering Conference (IDETC/CIE 2022), St. Louis, Missouri, USA: paper presentation


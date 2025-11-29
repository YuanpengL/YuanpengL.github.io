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

I'm a soon-to-graduate Ph.D. candidate at the Centre for Innovative Structures and Materials (CISM), Royal Melbourne Institute of Technology (RMIT), under the supervision of Prof. Yi Min 'Mike' Xie.

My work lies at the intersection of **architectural geometry**, **computational design**, **structural optimization**, and **digital fabrication**. The primary aim is to integrate geometric insights with computational power to create structurally efficient, aesthetically refined designs, while advancing feasible and cost-effective strategies for materialization at the architectural scale.

During my PhD at RMIT CISM, we developed computational frameworks for **approximating free-form surfaces with repetitive elements** to achieve cost-effective fabrication. These algorithms enable: (1) reducing individually the number of distinct beams, panels, or joints within a given structure through **clustering and optimization**; (2) approximating complex free-form surfaces using equivalent regular triangle panels in **mesh-growth** manner; and (3) simultaneously reducing multiple element types (including beams, joints, and panels) by **approximating free-forms surfaces using assemblies of rotational patches**. 

During my visit at EPFL GCM, we proposed a new type of **elastic gridshell composed of locally deployable rotational-surface components**, which can be prefabricated, compactly stored and transported, and rapidly deployed for efficient on-site assembly.

# News
- *2025.11*: &nbsp;New paper presented at Advances in Architectural Geometry (AAG) 2025 at MIT, Boston.
- *2025.11*: &nbsp;Led a workshop at Advances in Architectural Geometry (AAG) 2025 at MIT, Boston.

# Selected Publications 

See [GoogleScholar](https://scholar.google.com/citations?hl=en&user=neiW5ZgAAAAJ&view_op=list_works&sortby=pubdate) or [ResearchGate](https://www.researchgate.net/profile/Yuanpeng-Liu-3?ev=hdr_xprf) for my full publication list.






<div class="paper-box">
  <div class="paper-box-image"><div><a href="https://infoscience.epfl.ch/entities/publication/b6a52c0a-5416-4eab-87fa-11f04660d461" target="_blank"><img src="images/gridshell.jpg" alt="sym" width="100%"></a></div></div>
  <div class="paper-box-text" markdown="1">

**Double-Layered Elastic Gridshells with Locally Deployable Rotational-Surface Components**  

**Yuanpeng Liu**, Seiichi Suzuki, Florin Isvoranu, Mark Pauly  

*Advances in Architectural Geometry (AAG) 2025, Boston*

[paper](https://infoscience.epfl.ch/entities/publication/b6a52c0a-5416-4eab-87fa-11f04660d461)

We present a new class of elastic gridshell that are assembled from locally deployable rotational-surface components for efficient on-site assembly. 
</div>
</div>






<div class="paper-box">
  <div class="paper-box-image"><div><a href="https://dl.acm.org/doi/full/10.1145/3744707" target="_blank"><img src="images/rotPatch.jpg" alt="sym" width="100%"></a></div></div>
  <div class="paper-box-text" markdown="1">

**Free-Form Surface Approximation Using Rotational Patches**  

**Yuanpeng Liu**, Yi Min Xie, Ting-Uei Lee, Ziqi Wang, Nico Pietroni  

*ACM Transactions on Graphics, 2025 (to appear at SIGGRAPH 2026, Los Angeles)*

[paper](https://dl.acm.org/doi/full/10.1145/3744707)

We present a method to approximate free-form surfaces using assemblies of rotational patches to enable simultaneous repetition of multiple elements (such as beams, panels, and joints) for cost-effective fabrication. 
</div>
</div>







<div class="paper-box">
  <div class="paper-box-image"><div><a href="https://www.researchgate.net/profile/Yuanpeng-Liu-3/publication/383865428_Free-form_surface_approximation_using_congruent_regular_triangles/links/66de91502390e50b2c7a4ecc/Free-form-surface-approximation-using-congruent-regular-triangles.pdf" target="_blank"><video width="100%" autoplay muted loop playsinline><source src="images/meshGrowth.mp4" type="video/mp4"></video></a></div></div>
  <div class="paper-box-text" markdown="1">

**Free-form Surface Approximation Using Congruent Regular Triangles**  

**Yuanpeng Liu**, Ting-Uei Lee, Yi Min Xie

*Proceedings of International Association for Shell and Spatial Structures (IASS) 2024, Zürich*

[paper](https://www.researchgate.net/profile/Yuanpeng-Liu-3/publication/383865428_Free-form_surface_approximation_using_congruent_regular_triangles/links/66de91502390e50b2c7a4ecc/Free-form-surface-approximation-using-congruent-regular-triangles.pdf)

We present a meth growth algorithm to approximate free-form surfaces using equivalent regular triangles.
</div>
</div>






<div class="paper-box">
  <div class="paper-box-image"><div><a href="https://www.sciencedirect.com/science/article/pii/S0141029624004747#fig0005" target="_blank"><img src="images/physicalModel.jpg" alt="sym" width="100%"></a></div></div>
  <div class="paper-box-text" markdown="1">

**Clustering and Optimisation of Nodes, Beams and Panels for Cost-Effective Fabrication of Free-Form Surfaces**  

Minghao Bi, **Yuanpeng Liu**, Tao Xu, Yunzhen He, Jiaming Ma, Zicheng Zhuang, Yi Min Xie

*Engineering Structures, 2024*

[paper](https://www.sciencedirect.com/science/article/pii/S0141029624004747#fig0005)   [website](https://www.rmit.edu.au/research/centres-collaborations/centre-for-innovative-structures-and-materials/projects/optimised-pavillion)  [video](https://youtu.be/9l1Cq9cxjMk)

We build a physical prototype with repetitive panels, beams, and joints.
</div>
</div>








<div class="paper-box">
  <div class="paper-box-image"><div><a href="https://www.sciencedirect.com/science/article/pii/S0010448523001653" target="_blank"><img src="images/reduceFace.jpg" alt="sym" width="100%"></a></div></div>
  <div class="paper-box-text" markdown="1">

**Reducing the Number of Different Faces in Free-Form Surface Approximations Through Clustering and Optimization**  

**Yuanpeng Liu**, Ting-Uei Lee, Anooshe Rezaee Javan, Nico Pietroni, Yi Min Xie

*Computer-Aided Design, 2024*

[paper](https://www.sciencedirect.com/science/article/pii/S0010448523001653)  [GHPlugin](https://www.food4rhino.com/en/app/faceclusteropt)

Given an input mesh, we reduce the number of different n-gonal faces through clustering and optimization.
</div>
</div>





<div class="paper-box">
  <div class="paper-box-image"><div><a href="https://www.sciencedirect.com/science/article/pii/S0141029623004303" target="_blank"><img src="images/reduceNode.jpg" alt="sym" width="100%"></a></div></div>
  <div class="paper-box-text" markdown="1">

**Reducing the Number of Different Nodes in Space Frame Structures Through Clustering and Optimization**  

**Yuanpeng Liu**, Ting-Uei Lee, Antiopi Koronaki, Nico Pietroni, Yi Min Xie

*Engineering Structures, 2023*

[paper](https://www.sciencedirect.com/science/article/pii/S0141029623004303)

Given an input mesh, we reduce the number of different nodes through clustering and optimization.
</div>
</div>






<div class="paper-box">
  <div class="paper-box-image"><div><a href="https://royalsocietypublishing.org/doi/full/10.1098/rsos.220675" target="_blank"><img src="images/goldberg.jpg" alt="sym" width="100%"></a></div></div>
  <div class="paper-box-text" markdown="1">

**Extending Goldberg’s Method to Parametrize and Control the Geometry of Goldberg Polyhedra**  

**Yuanpeng Liu**, Ting-Uei Lee, Anooshe Rezaee Javan, Yi Min Xie

*Royal Society Open Science, 2022*

[paper](https://royalsocietypublishing.org/doi/full/10.1098/rsos.220675)

We discovered numerically a family of spherical Goldberg Polyhedra that have faces being planar with all vertices lieing on a shpere. Remaining degrees of freedom allows further reducing the number of different edges.
</div>
</div>




# Educations
- **Ph.D.**, Civil Engineering, *2022.05 - 2026.02 (expected)*, RMIT University.
- **M.Eng.** (Double Degree), Civil Engineering, *2018.09 - 2021.06*, Universitat Politècnica de Catalunya (UPC).
- **M.Eng.** (Double Degree), Civil Engineering, *2018.09 - 2021.06*, Tongji University.
- **B.Eng.**, Civil Engineering, *2014.09 - 2018.06*, Tongji University.


# Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.

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

Hi, this is Sheng. 

Machine learning | Applied AI | Scientific Software | Time-Series Modeling

I am working as a Machine Learning Developer at [UNSW](https://www.unsw.edu.au/research/wrc) with experience in applied AI, scientific software, and data-driven engineering systems. My work spans reverse osmosis software, time-series modeling, and research in medical computer vision. I enjoy building practical tools that connect machine learning with real-world technical problems.

# 🔥 News
- *2026.01*: &nbsp;🎉🎉 The developed RO System Design and Projection Software has been delivered to OriginWater, leading to a company-owned patented solution. 
- *2024.12*: &nbsp;🎉🎉 Our paper has been accepted as the Best Student Paper in ICONIP 2024 

# Projects

### [LangChain RO Knowledge Assistant](https://github.com/ShengAus/LangChain-RO-Knowledge-Assistant)
A lightweight FastAPI application for question answering over local reverse osmosis notes.

- Built a LangChain-based workflow for document loading, chunking, retrieval, query normalization, and conservative support checks.
- Integrated optional OpenAI-compatible answer generation with deterministic fallback behavior when no API key was configured.
- Used Pydantic request and response models to return answers together with supporting source files.

### [RO System Design and Projection Software](https://github.com/ShengAus/ROS_Design_Projection_Software_Demo)
Desktop reverse osmosis design and projection software for engineering workflows.
- Led the end-to-end software implementation of a reverse osmosis design and performance projection tool.
- Developed Python backend modules, engineering calculation workflows, and structured reporting outputs.
- Designed reusable program components and data structures to support system design, performance estimation, and maintainable delivery.

### MCDI Data Automation and Modelling Support
A developing R&D project in membrane capacitive deionization (MCDI), focused on data workflow automation and ML-oriented analysis.
- Contributed to early-stage data organisation and automation workflows for experimental and operational datasets.
- Supported reproducible processing pipelines to improve downstream modelling and digital-twin-oriented analysis.
- Explored how machine learning workflows could support performance modelling and future system optimisation.

### [Unsupervised dMRI Artifact Detection](https://github.com/ShengAus/UdAD)
A research project on improving the reliability of diffusion MRI data through unsupervised artifact detection.
- Developed a deep learning framework using angular resolution enhancement and cycle consistency learning.
- Focused on identifying corrupted or unreliable diffusion MRI samples without requiring manual labels.
- Later published at **AJCAI 2024**.

### [DirGeo-DTI](https://github.com/ShengAus/DirGeo_Net)
A deep learning method for estimating reliable diffusion tensor imaging metrics from only 6 diffusion gradient directions.

- Integrated diffusion-gradient encoding and geometry-constrained learning for high-angular DTI estimation.
- Evaluated on the HCP and PPMI datasets with strong overall performance against existing enhancement approaches.
- Received the **Best Student Paper** award at **ICONIP 2024**.

### [Few-Shot Thigh Muscle Segmentation](https://github.com/ShengAus/Myositis_muscle_pipline)
A few-shot learning pipeline for thigh muscle segmentation on T1-weighted MRI with minimal annotation requirements.

- Built an end-to-end imaging workflow covering DICOM-to-NIfTI conversion, thigh splitting, registration, ROI extraction, and bias correction.
- Developed automatic mask generation and refinement steps for longitudinal analysis.
- Targeted muscle extraction while excluding intra-muscular fat for practical medical imaging use.


# Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EST</div><img src='images/EST.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Identification of Key Physicochemical Characteristics Which Influence Epithelial-to-Mesenchymal Transition of Lung Cells after Exposure to Engineered and Natural Stone Dusts via a Hybrid Machine Learning Approach](https://pubs.acs.org/doi/abs/10.1021/acs.est.5c14999)

Siqi Sun, Yingying Sun, Andrew S. Kinsela, Yunyi Zhu, Nikky LaBranche, **Sheng Chen**, T. David Waite

- Investigates how engineered stone dust influence epithelial-to-mesenchymal transition (EMT), a critical biological process linked to respiratory diseases such as silicosis and COPD. We combined detailed material characterization with interpretable machine learning to uncover key drivers of dust-induced cellular responses.
- Accepted by **Environmental Science & Technology (EST)**, a leading journal in environmental science and engineering. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICONIP 2024</div><img src='images/DIRGEO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Angular Resolution via Directionality Encoding and Geometric Constraints in Brain Diffusion Tensor Imaging](https://arxiv.org/pdf/2409.07186)

**Sheng Chen**, Zihao Tang, Mariano Cabezas, Xinyi Wang, Arkiev D’Souza, Michael Barnett, Fernando Calamante, Weidong Cai, and Chenyu Wang

[**Project**](https://github.com/ShengAus/DirGeo_Net/tree/master)
- Developed a deep learning method to estimate reliable diffusion tensor imaging metrics from only 6 diffusion gradient directions by integrating diffusion-gradient encoding and geometry-constrained learning.
- More interpretable and reliable results through physical-informed deep learning methods.
- Awarded as the **Best Student Paper** in ICONIP2024
</div>
</div>

# 📖 Educations
- *2013.07 - 2025.02*, Master of Philosophy, Machine Learning / Medical Computer Vision, University of Sydney
- *2019.02 - 2023.02*, Bachelor of Advanced Computing (First Class Honours, WAM 80+), University of Sydney

# 🎖 Honors and Awards
- *2024.12* Best Student Paper in ICONIP 2024. 
- *2023.1* First class honors in USYD
- *2022,2023* Dean’s List in USYD for distinguished academic performance. 


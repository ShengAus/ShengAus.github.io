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

Hi, I’m **Sheng Chen**.

<p style="margin: 0.2em 0 1em 0;">
  AI Engineer&nbsp;|&nbsp;Agent Development&nbsp;|&nbsp;Enterprise AI&nbsp;|&nbsp;Applied Machine Learning
</p>

I am an **AI Engineer at DataReady AI**, building enterprise AI solutions on **Databricks and Snowflake**. My work spans the agent development lifecycle: tool integration, agentic workflows, evaluation and deployment. I build integrations that let customers use enterprise AI from their everyday tools, with access scoped to their identity.

Previously, I worked as a Machine Learning Developer at UNSW Sydney, applying machine learning and scientific software to industrial and environmental problems. My research background is in machine learning and medical computer vision.

<span class='anchor' id='news'></span>

# 🔥 News
- *2026.11* — Earned the **Databricks Certified Generative AI Engineer Associate** certification.
- *2026.10* — Earned the **LangChain Certified Agent Engineer** certification.
- *2026.05* — Joined **DataReady AI** as an AI Engineer.
- *2026.03* — The RO performance projection software I helped develop received **software copyright registration** in China.
- *2026.02* — Our study on stone-dust properties and lung-cell responses was published in **Environmental Science & Technology**. [Paper](https://pubs.acs.org/doi/abs/10.1021/acs.est.5c14999).
- *2025.02* — Joined **UNSW Water Research Centre** as a **Machine Learning Developer**.
- *2024.12* — Our DirGeo-DTI paper received **Best Student Paper** at **ICONIP 2024**.

<span class='anchor' id='experience'></span>

# Experience

**DataReady AI · AI Engineer**  
May 2026 – Present

Building customer-facing enterprise AI integrations, agent tooling, workflow automation and deployment pipelines across Databricks and Snowflake.

**UNSW Sydney · Machine Learning Developer**  
February 2025 – March 2026

Applied machine learning, industrial data preparation and Python engineering calculations at the Water Research Centre, working with researchers, plant operators and industry partners.

<span class='anchor' id='projects'></span>

# 💻 Projects

## Enterprise AI · DataReady AI

### Agent Tool Integration & MCP
Built self-service tool onboarding so teams can make enterprise capabilities available to agents through standard **Model Context Protocol (MCP)** interfaces. Adapted Databricks and Snowflake’s native tool services and access controls, including reviewed publication and user-delegated execution on Databricks.

### Chatbot Integration · Microsoft Teams & Slack
Delivered customer-used chatbots that bring enterprise AI into **Teams and Slack**, with queries scoped to each user’s Databricks or Snowflake identity. Implemented persistent conversation context for both channels on Databricks, supporting follow-up questions while isolating users’ histories.

### Agentic Workflow Automation
Developing a **LangGraph-based workflow builder** that turns natural-language requests into reusable automation, with schema validation and human review of generated plans. Built scenario-based agent evaluation with structural checks, an LLM judge and calibration checks; added execution traces and resource-use reports to diagnose evaluation runs.

### Agent Deployment & CI/CD
Automated application delivery on **Databricks and Snowflake** with GitHub Actions and contributed Databricks agent packaging for **MLflow serving**. Added dependency and regression checks to validate release changes.

## Applied ML & Scientific Software · UNSW Sydney

### Reverse-Osmosis Engineering Software
Implemented Python engineering calculations and sensitivity analysis for reverse-osmosis design and performance projection. Examined permeate quality and feed-pressure behaviour, documenting assumptions and limitations for engineering discussions.

### Industrial Data Preparation
Turned reverse-osmosis sensor records into modelling-ready datasets through timestamp alignment, schema and unit standardisation, outlier handling, feature engineering and resampling.

### Groundwater Response Modelling
Developed tree-based and LSTM models to study groundwater response to rainfall. Used prediction errors and time-series diagnostics to assess model quality, identify observation gaps and communicate limitations.

### MCDI Electrode Performance Analysis
Analysed charge/discharge behaviour, cycle duration, conductivity removal and energy-related indicators to compare electrode performance in membrane capacitive deionisation experiments.

## Medical Imaging Research

### [DirGeo-DTI](https://github.com/ShengAus/DirGeo_Net)
First-author research on diffusion tensor imaging using directionality encoding and geometric constraints. Received **Best Student Paper at ICONIP 2024**; the Springer proceedings appeared in 2025. [Paper](https://link.springer.com/chapter/10.1007/978-981-96-6585-3_17).

### [Unsupervised dMRI Artifact Detection](https://github.com/ShengAus/UdAD)
First-author research combining angular-resolution enhancement and cycle-consistency learning to detect diffusion MRI artifacts without manual artifact labels. Published at **AJCAI 2024**. [Paper](https://link.springer.com/chapter/10.1007/978-981-96-0351-0_31).

### Few-Shot Thigh Muscle Segmentation
First-author research on fat-free thigh muscle segmentation in T1-weighted MRI, presented at **ISBI 2023**. [Paper](https://arxiv.org/abs/2304.14053) · [Related preprocessing and segmentation pipeline](https://github.com/ShengAus/Myositis_muscle_pipline).

<span class='anchor' id='certifications'></span>

# Certifications

- **LangChain Certified Agent Engineer** — LangChain  
  October 2026 – October 2028 · [Verify credential](https://certs.langchain.com/1aec62bb-5e37-4bf2-9db4-2ae4d686b39a)
- **Databricks Certified Generative AI Engineer Associate** — Databricks Academy  
  November 2026 – November 2028 · [Verify credential](https://credentials.databricks.com/32b403b6-3b34-4fda-8a67-ce77cf03cee0)

<span class='anchor' id='publications'></span>

# 📝 Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EST 2026</div><img src='images/EST.jpg' alt="Stone-dust and lung-cell response study" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Identification of Key Physicochemical Characteristics Which Influence Epithelial-to-Mesenchymal Transition of Lung Cells after Exposure to Engineered and Natural Stone Dusts via a Hybrid Machine Learning Approach](https://pubs.acs.org/doi/abs/10.1021/acs.est.5c14999)

Siqi Sun, Yingying Sun, Andrew S. Kinsela, Yunyi Zhu, Nikky LaBranche, **Sheng Chen**, T. David Waite

Published in **Environmental Science & Technology**, 2026, 60(7), 5337–5349. A collaborative study connecting material characterisation and machine learning to investigate dust-induced cellular responses.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICONIP 2024</div><img src='images/DIRGEO.png' alt="DirGeo-DTI research overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Angular Resolution via Directionality Encoding and Geometric Constraints in Brain Diffusion Tensor Imaging](https://link.springer.com/chapter/10.1007/978-981-96-6585-3_17)

**Sheng Chen**, Zihao Tang, Mariano Cabezas, Xinyi Wang, Arkiev D’Souza, Michael Barnett, Fernando Calamante, Weidong Cai, and Chenyu Wang

**ICONIP 2024 · Best Student Paper**. Springer proceedings published in 2025, pp. 241–254. [Project](https://github.com/ShengAus/DirGeo_Net).

</div>
</div>

[View all publications on Google Scholar](https://scholar.google.com.au/citations?user=BfUKxqMAAAAJ&hl=en).

<span class='anchor' id='honors-and-awards'></span>

# 🎖 Achievements & Awards
- **Software copyright registration — RO performance projection software**, March 2026 (2026SR0511888). Contributing developer; registration held by the company.
- **Best Student Paper — ICONIP 2024**, DirGeo-DTI (first author).
- **First Class Honours — University of Sydney**, Bachelor of Advanced Computing, 2023.

<span class='anchor' id='education'></span>

# 📖 Education
- *July 2023 – February 2025* — **Master of Philosophy**, University of Sydney. Research focus: Machine Learning / Medical Computer Vision.
- *February 2019 – February 2023* — **Bachelor of Advanced Computing, First Class Honours**, University of Sydney.

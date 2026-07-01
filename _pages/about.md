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

Hi! I am **Wangjia (Jack) Zhan**, currently a **M.S. student in Computer Science at the University of Illinois Urbana-Champaign (UIUC)**. My research focuses on **large-scale machine learning** and **deep learning-based recommendation systems (DLRS)**, with particular interests in **scaling laws**, **memory-/communication-efficient model architectures**, and **efficient training/fine-tuning algorithms**.

I am a **Research Assistant supervised by Prof. Minjia Zhang (UIUC CS)**, where I study **system-aware scaling behaviors** of recommendation models and explore **embedding compression** techniques to improve efficiency while maintaining accuracy.

**Contact:** wangjia2@illinois.edu  
<!-- Optional: add links once you have them
Google Scholar: https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID
GitHub: https://github.com/YOUR_GITHUB_USERNAME
-->

<!-- Optional Scholar badge (requires GOOGLE_SCHOLAR_ID + workflow enabled) -->
<!-- <a href="https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID">
<img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a> -->

---

# 🔥 News
- *2025.08*: Started **M.S. in Computer Science** at **UIUC**.
- *2024.09*: Paper published in **IET Control Theory & Applications**.
- *2024.06*: Began **Research Assistant** role at **UIUC**, working on scaling laws and efficient DLRS.
- *2022.07*: Completed **Embedded Systems Engineering Internship** at **Microchip Technology**.

---

# 🧠 Research Interests
- Deep learning-based recommendation systems (DLRS), scaling laws
- Memory-efficient / communication-efficient model design
- Embedding compression (e.g., QR compression, caching)
- Large language models and efficient fine-tuning (local learning, zero-order optimization)
- Algorithm design and data structures

---

# 📝 Publications

<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">IET CTA 2024</div>
<img src='images/500x300.png' alt="paper" width="100%">
</div>
</div>
<div class='paper-box-text' markdown="1">

**Minimal-Cost Route Planning via Fibonacci-Heap-Typed Data Structure**  
**Wangjia Zhan**, Haohao Qiu, Bo Min, Lin Lin  
*IET Control Theory & Applications*, Sep. 2024

- Modeled minimal-cost route planning with **MDPs** and converted it into a **directed graph** framework.  
- Implemented **Edmonds’ algorithm** and improved it with a **Fibonacci heap**, reducing time complexity from **O(mn)** to **O(m + n log n)**.

</div>
</div>

---

# 🔬 Research Experience

**Research Assistant (UIUC CS)** — *Jun 2024 – Present*  
Supervised by **Prof. Minjia Zhang**  
Project: **Designing a scaling-law-friendly DLRM to enhance memory and communication efficiency**
- Verified scaling laws of DLRS using a state-of-the-art model and evaluated embedding compression techniques.
- Designed a scaling-law-aware architecture integrating **QR compression** and a **head-cache mechanism**, achieving comparable performance with **~10× lower memory consumption**.

**Research Assistant (HKU Faculty of Engineering)** — *Sep 2023 – Mar 2024*  
Supervised by **Prof. James Lam** and PhD student **Lin Lin**  
Project: **Minimal-cost route planning via data structures & MDP**
- Formulated route planning as an MDP and transformed it into a graph optimization problem.
- Developed algorithmic solutions and delivered pseudocode-driven presentations bridging theory and practice.

---

# 💻 Internships

**Algorithm Engineer Intern** — *Jun 2024 – Present*  
Coached by **Prof. Zhichao Lu (CityU HK)**  
Project: **Fine-tuning algorithms for large-scale models via scalable local learning**
- Designed scalable local learning rules leveraging self-supervised learning and data augmentation.
- Incorporated **zero-order optimization** to improve efficiency and adaptability.

**Embedded Systems Engineering Intern (Microchip Technology, Qingdao)** — *Jul 2022 – Aug 2022*  
Project: **Embedded Touch Control System with ADC acquisition and encrypted IrDA communication**
- Implemented touch key and encrypted IR communication using Timer, PWM, UART, CLC, I2C, ADC.
- Completed schematic + PCB layout in **Altium Designer**; debugged with **MPLAB**.

---

# 🎖 Honors and Awards
- Dean’s Honors List (UIUC Grainger College of Engineering), **Spring 2024**
- Dean’s Honors List (HKU Faculty of Engineering), **2022–2023**
- First Prize, National Olympiad in Informatics (Provincial), **2018**

---

# 🎓 Education
- **University of Illinois Urbana-Champaign (UIUC)** — M.S. in Computer Science, *Aug 2025 – Present*
- **University of Illinois Urbana-Champaign (UIUC)** — Exchange Student (CS), *Jan 2024 – May 2024* (GPA: 4.0/4.0)
- **The University of Hong Kong (HKU)** — B.S. in Computer Science, *Sep 2021 – Jun 2025* (cGPA: 3.792/4.3)

---

# 🛠 Technical Skills
- **Programming:** C/C++, Python
- **ML Frameworks:** PyTorch, TensorFlow
- **Systems/Tools:** Linux, git, ssh, LaTeX
- **ML Background:** Transformer, CNN, GAN, diffusion models

---

# 📚 Selected Coursework
- Data Structures & Algorithms, Algorithm Design, Operating Systems, Computer Organization
- Machine Learning, Artificial Intelligence, NLP, Deep Learning for Computer Vision, Applied Machine Learning


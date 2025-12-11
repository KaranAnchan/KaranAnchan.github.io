---
layout: default
title: Karan Anchan | AI Portfolio
---

<div align="center">
  <h1>Karan Anchan</h1>
  <h3>Master's Student in Computer Science (Artificial Intelligence)</h3>
  <p>📍 Freiburg im Breisgau, Germany</p>
  
  <p>
    <a href="mailto:kar.anchan02@gmail.com">
      <img src="https://img.shields.io/badge/Email-kar.anchan02%40gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://linkedin.com/in/karan-anchan">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://github.com/KaranAnchan">
      <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
    </a>
  </p>
</div>

---

## 👋 About Me

I am a specialized **AI Researcher & Engineer** currently pursuing my Master's at the **University of Freiburg**. My focus lies at the intersection of **Generative AI**, **Computer Vision**, and **NLP**. 

I don't just build models; I engineer end-to-end pipelines that solve real-world problems—from medical image segmentation to semantic translation systems.

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

---

## 🚀 Featured Projects

### 🏥 UNETR: 3D Abdomen Segmentation
**Stack:** `PyTorch` `MONAI` `Vision Transformers` `DICOM/NIFTI`

I architected a volumetric segmentation pipeline using the **UNETR (Vision Transformer)** architecture to identify 13 distinct abdominal organs. This project solves the challenge of capturing global context dependencies in medical imaging.

<div align="center">
  <img src="images/unetr.png" alt="UNETR Architecture" width="100%" />
  <p><em>Fig 1: The UNETR Architecture implementing Transformer Encoders for volumetric data.</em></p>
</div>

**Key Achievements:**
* 🏆 **0.8027 Mean Dice Score** achieved on the BTCV dataset.
* **Preprocessing:** Engineered robust HU windowing and isometric resampling to normalize soft-tissue density.
* **Optimization:** Solved class imbalance (e.g., small adrenal glands vs. large liver) using compound Dice-Cross Entropy loss.

<div align="center">
  <img src="images/viz.png" alt="Segmentation Visualization" width="100%" />
  <p><em>Fig 2: Actual model output showing precise segmentation of internal organs.</em></p>
</div>

[**View Project on GitHub**](https://github.com/KaranAnchan/Unetr_3D_Abdomen_Segmentation)

---

### 🗣️ Neural Machine Translation (English-to-Hindi)
**Stack:** `PyTorch` `Transformers` `Altair` `NLP`

A complete implementation of the **Transformer** architecture ("Attention Is All You Need") built from scratch. This model handles complex transliterations and formal grammar with high accuracy.

**Performance Metrics:**
* 📈 **SacreBLEU:** 62.48
* 📉 **Character Error Rate (CER):** 0.28 (28%)
* 🤖 **CHRF++:** 71.78

<div align="center">
  <img src="images/beautiful_metrics (1).png" alt="Training Metrics" width="100%" />
  <p><em>Fig 3: Training progression showing the correlation between SacreBLEU scores and error reduction over 900k steps.</em></p>
</div>

**Engineering Highlights:**
* Implemented custom attention visualization tools to debug encoder-decoder alignment.
* Reduced hallucinations in translation by optimizing the tokenizer for the IIT Bombay Corpus.

[**View Project on GitHub**](https://github.com/KaranAnchan/en-hi-nmt-transformer)

---

## 💼 Professional Experience

### **Machine Learning Intern | Wizdom Ed**
*Mangalore, India | Oct 2023 – Apr 2024*

* **RAG Pipeline Engineering:** Developed a Retrieval-Augmented Generation system using **LangChain** and **ChromaDB**. By relating LLM responses to strict curriculum data, I significantly reduced hallucinations.
* **Impact:** * 🚀 **35% increase** in student engagement via optimized data ingestion.
    * ✅ **30% boost** in positive response rates by implementing retrieval quality feedback loops.

---

## 🎓 Education

**M.Sc. Computer Science (Artificial Intelligence)** *Albert Ludwig University of Freiburg* (2025 – Present)  
* **Current Grade:** 2.5 (Gut)

**B.E. Computer Science** *N.M.A.M Institute of Technology* (2020 – 2024)  
* **Grade:** 9.33/10 CGPA (First Class with Distinction)

---
<div align="center">
  <p>© 2025 Karan Anchan. Powered by GitHub Pages.</p>
</div>

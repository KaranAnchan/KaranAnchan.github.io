---
layout: default
title: Karan Anchan | AI Portfolio
---

<div align="center" style="margin-bottom: 40px;">
  <img src="https://github.com/KaranAnchan.png" alt="Karan Anchan" width="150" height="150" style="border-radius: 50%; border: 4px solid #e1e4e8; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <h1 style="margin-top: 20px; font-size: 2.5em; border-bottom: none;">Karan Anchan</h1>
  <p style="font-size: 1.2em; color: #586069;">
    Master's Student in CS (Artificial Intelligence) <br> 
    📍 Freiburg im Breisgau, Germany
  </p>
  
  <p>
    <a href="mailto:kar.anchan02@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_Me-d14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
    <a href="https://linkedin.com/in/karan-anchan"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
    <a href="https://github.com/KaranAnchan"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
  </p>
</div>

<hr style="border: 0; height: 1px; background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0)); margin-bottom: 40px;">

<h2 align="center" style="border-bottom: none;">👋 About Me</h2>
<p align="center" style="max-width: 700px; margin: 0 auto 40px auto; line-height: 1.6;">
  I am a specialized <strong>AI Researcher & Engineer</strong> currently pursuing my Master's at the <strong>University of Freiburg</strong>. My focus lies at the intersection of <strong>Generative AI</strong>, <strong>Computer Vision</strong>, and <strong>NLP</strong>. I engineer end-to-end pipelines that solve real-world problems—from medical image segmentation to semantic translation systems.
</p>

<div align="center" style="margin-bottom: 50px;">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white">
  <img src="https://img.shields.io/badge/MONAI-5D3FD3?style=for-the-badge&logo=plus&logoColor=white">
</div>

<h2 align="center" style="border-bottom: none; margin-bottom: 30px;">🚀 Featured Projects</h2>

<div style="background-color: #f6f8fa; padding: 25px; border-radius: 10px; margin-bottom: 30px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
  <h3 style="margin-top: 0; color: #0366d6;">🏥 UNETR: 3D Abdomen Segmentation</h3>
  <p><strong>Stack:</strong> <code>PyTorch</code> <code>MONAI</code> <code>Vision Transformers</code></p>
  
  <p>I architected a volumetric segmentation pipeline using the <strong>UNETR (Vision Transformer)</strong> architecture to identify 13 distinct abdominal organs. This project solves the challenge of capturing global context dependencies in medical imaging.</p>

  <div align="center" style="margin: 20px 0;">
    <img src="images/unetr.png" alt="UNETR Architecture" width="90%" style="border-radius: 8px;">
    <br><em>Fig 1: The UNETR Architecture implementing Transformer Encoders for volumetric data.</em>
  </div>

  <p><strong>Key Achievements:</strong></p>
  <ul>
    <li>🏆 <strong>0.8027 Mean Dice Score</strong> achieved on the BTCV dataset.</li>
    <li><strong>Preprocessing:</strong> Engineered robust HU windowing and isometric resampling to normalize soft-tissue density.</li>
  </ul>
  
  <div align="center" style="margin: 20px 0;">
    <img src="images/viz.png" alt="Segmentation Visualization" width="90%" style="border-radius: 8px;">
    <br><em>Fig 2: Actual model output showing precise segmentation of internal organs.</em>
  </div>

  <p align="center">
    <a href="https://github.com/KaranAnchan/Unetr_3D_Abdomen_Segmentation" style="background-color: #2ea44f; color: white; padding: 10px 20px; text-decoration: none; border-radius: 6px; font-weight: bold;">View Project on GitHub</a>
  </p>
</div>

<div style="background-color: #f6f8fa; padding: 25px; border-radius: 10px; margin-bottom: 30px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
  <h3 style="margin-top: 0; color: #0366d6;">🗣️ Neural Machine Translation (Eng-Hi)</h3>
  <p><strong>Stack:</strong> <code>PyTorch</code> <code>Transformers</code> <code>Altair</code></p>
  
  <p>A complete implementation of the <strong>Transformer</strong> architecture ("Attention Is All You Need") built from scratch. This model handles complex transliterations and formal grammar with high accuracy.</p>

  <p><strong>Performance Metrics:</strong></p>
  <ul>
    <li>📈 <strong>SacreBLEU:</strong> 62.48</li>
    <li>📉 <strong>Character Error Rate (CER):</strong> 0.28 (28%)</li>
    <li>🤖 <strong>CHRF++:</strong> 71.78</li>
  </ul>

  <div align="center" style="margin: 20px 0;">
    <img src="images/beautiful_metrics (1).png" alt="Training Metrics" width="90%" style="border-radius: 8px;">
    <br><em>Fig 3: Training progression showing correlation between SacreBLEU scores and error reduction.</em>
  </div>

  <p align="center">
    <a href="https://github.com/KaranAnchan/en-hi-nmt-transformer" style="background-color: #2ea44f; color: white; padding: 10px 20px; text-decoration: none; border-radius: 6px; font-weight: bold;">View Project on GitHub</a>
  </p>
</div>

<h2 align="center" style="border-bottom: none; margin-bottom: 30px;">💼 Professional Experience</h2>

<div style="border-left: 4px solid #0366d6; padding-left: 20px; margin-bottom: 30px;">
  <h3>Machine Learning Intern | Wizdom Ed</h3>
  <p><em>Mangalore, India | Oct 2023 – Apr 2024</em></p>
  <p>Engineered a <strong>Retrieval-Augmented Generation (RAG)</strong> pipeline using LangChain to relate LLM responses to curriculum data.</p>
  <ul>
    <li>🚀 <strong>35% increase</strong> in student engagement via optimized data ingestion.</li>
    <li>✅ <strong>30% boost</strong> in positive response rates by implementing retrieval quality feedback loops.</li>
  </ul>
</div>

<h2 align="center" style="border-bottom: none; margin-bottom: 30px;">🎓 Education</h2>

<div style="display: flex; justify-content: space-between; margin-bottom: 20px; border-bottom: 1px solid #e1e4e8; padding-bottom: 10px;">
  <div>
    <strong>M.Sc. Computer Science (AI)</strong><br>
    Albert Ludwig University of Freiburg
  </div>
  <div style="text-align: right;">
    Apr 2025 – Present<br>
    <em>Grade: 2.5 (Gut)</em>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 20px; border-bottom: 1px solid #e1e4e8; padding-bottom: 10px;">
  <div>
    <strong>B.E. Computer Science</strong><br>
    N.M.A.M Institute of Technology
  </div>
  <div style="text-align: right;">
    Sep 2020 – Aug 2024<br>
    <em>CGPA: 9.33/10</em>
  </div>
</div>

<br>
<div align="center">
  <p style="font-size: 0.9em; color: #586069;">© 2025 Karan Anchan. Powered by GitHub Pages.</p>
</div>

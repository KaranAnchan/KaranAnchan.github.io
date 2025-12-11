---
layout: default
title: Karan Anchan | AI Portfolio
---

<style>
  body {
    font-family: "Times New Roman", Times, serif;
    font-size: 18px;
    line-height: 1.6;
    color: #24292e;
  }
  h1 {
    font-family: "Times New Roman", Times, serif;
    font-size: 3em;
    font-weight: 700;
    margin-bottom: 10px;
    letter-spacing: -0.5px;
  }
  h2 {
    font-family: "Times New Roman", Times, serif;
    font-size: 2.2em;
    font-weight: 600;
    border-bottom: 2px solid #eaecef;
    padding-bottom: 0.3em;
    margin-top: 50px;
    margin-bottom: 25px;
    color: #1b1f23;
  }
  h3 {
    font-family: "Times New Roman", Times, serif;
    font-size: 1.5em;
    font-weight: 600;
    margin-top: 0;
    margin-bottom: 5px;
    color: #0366d6; /* GitHub Blue for project titles */
  }
  .subtitle {
    font-size: 1.2em;
    color: #586069;
    font-style: italic;
  }
  .project-card {
    background-color: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    padding: 25px;
    margin-bottom: 30px;
    box-shadow: 0 3px 6px rgba(0,0,0,0.04);
  }
  .tech-stack {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; /* Keep badges standard */
    font-size: 0.9em;
    margin-bottom: 15px;
  }
  .edu-row {
    display: flex;
    justify-content: space-between;
    margin-bottom: 5px;
  }
  a.button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #24292e;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-family: -apple-system, sans-serif;
    font-size: 0.9em;
    font-weight: bold;
    margin-top: 15px;
  }
  a.button:hover {
    background-color: #0366d6;
  }
</style>

<div align="center" style="margin-bottom: 40px;">
  <img src="https://github.com/KaranAnchan.png" alt="Karan Anchan" width="160" height="160" style="border-radius: 50%; border: 4px solid #f6f8fa; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">
  
  <h1>Karan Anchan</h1>
  <div class="subtitle">
    Master's Student in Computer Science (Artificial Intelligence)<br> 
    📍 Freiburg im Breisgau, Germany
  </div>
  
  <p style="margin-top: 20px;">
    <a href="mailto:kar.anchan02@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_Me-d14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
    <a href="https://linkedin.com/in/karan-anchan"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
    <a href="https://github.com/KaranAnchan"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
  </p>
</div>

<h2>About Me</h2>
<p>
  I am a specialized <strong>AI Researcher & Engineer</strong> currently pursuing my Master's at the <strong>University of Freiburg</strong>. My focus lies at the intersection of <strong>Generative AI</strong>, <strong>Computer Vision</strong>, and <strong>NLP</strong>. I engineer end-to-end pipelines that solve real-world problems—from medical image segmentation to semantic translation systems.
</p>

<div align="center" style="margin-top: 30px; margin-bottom: 30px;">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white">
  <img src="https://img.shields.io/badge/MONAI-5D3FD3?style=for-the-badge&logo=plus&logoColor=white">
</div>

<h2>Featured Projects</h2>

<div class="project-card">
  <h3>🏥 UNETR: 3D Abdomen Segmentation</h3>
  <div class="tech-stack">
    <code>PyTorch</code> | <code>MONAI</code> | <code>Vision Transformers</code> | <code>DICOM/NIFTI</code>
  </div>
  
  <p>I architected a volumetric segmentation pipeline using the <strong>UNETR (Vision Transformer)</strong> architecture to identify 13 distinct abdominal organs. This project solves the challenge of capturing global context dependencies in medical imaging.</p>

  <div align="center" style="margin: 25px 0;">
    <img src="images/unetr.png" alt="UNETR Architecture" width="95%" style="border: 1px solid #ddd; border-radius: 4px;">
    <br><small><em>Fig 1: The UNETR Architecture implementing Transformer Encoders for volumetric data.</em></small>
  </div>

  <ul>
    <li><strong>Metric:</strong> Achieved a <strong>0.8027 Mean Dice Score</strong> on the BTCV dataset.</li>
    <li><strong>Preprocessing:</strong> Engineered robust HU windowing and isometric resampling to normalize soft-tissue density.</li>
    <li><strong>Optimization:</strong> Implemented compound Dice-Cross Entropy loss to address class imbalance.</li>
  </ul>
  
  <div align="center" style="margin: 25px 0;">
    <img src="images/viz.png" alt="Segmentation Visualization" width="95%" style="border: 1px solid #ddd; border-radius: 4px;">
    <br><small><em>Fig 2: Actual model output showing precise segmentation of internal organs.</em></small>
  </div>

  <div align="center">
    <a href="https://github.com/KaranAnchan/Unetr_3D_Abdomen_Segmentation" class="button">View Project on GitHub</a>
  </div>
</div>

<div class="project-card">
  <h3>🗣️ Neural Machine Translation (English-to-Hindi)</h3>
  <div class="tech-stack">
     <code>PyTorch</code> | <code>Transformers</code> | <code>Altair</code> | <code>NLP</code>
  </div>
  
  <p>A complete implementation of the <strong>Transformer</strong> architecture ("Attention Is All You Need") built from scratch. This model handles complex transliterations and formal grammar with high accuracy.</p>

  <div align="center" style="margin: 25px 0;">
    <img src="images/beautiful_metrics (1).png" alt="Training Metrics" width="95%" style="border: 1px solid #ddd; border-radius: 4px;">
    <br><small><em>Fig 3: Training progression showing correlation between SacreBLEU scores and error reduction.</em></small>
  </div>

  <ul>
    <li><strong>Performance:</strong> SacreBLEU: <strong>62.48</strong> | CHRF++: <strong>71.78</strong>.</li>
    <li><strong>Error Rate:</strong> Reduced Character Error Rate (CER) to <strong>0.28</strong>.</li>
    <li><strong>Engineering:</strong> Implemented custom attention visualization tools to debug encoder-decoder alignment.</li>
  </ul>

  <div align="center">
    <a href="https://github.com/KaranAnchan/en-hi-nmt-transformer" class="button">View Project on GitHub</a>
  </div>
</div>

<h2>Professional Experience</h2>

<div style="margin-bottom: 30px;">
  <div class="edu-row">
    <strong>Machine Learning Intern</strong>
    <span>Oct 2023 – Apr 2024</span>
  </div>
  <div class="subtitle" style="margin-bottom: 10px;">Wizdom Ed | Mangalore, India</div>
  
  <p>Engineered a <strong>Retrieval-Augmented Generation (RAG)</strong> pipeline using LangChain to relate LLM responses to curriculum data.</p>
  <ul>
    <li>🚀 <strong>35% increase</strong> in student engagement via optimized data ingestion workflows.</li>
    <li>✅ <strong>30% boost</strong> in positive response rates by implementing retrieval quality feedback loops.</li>
    <li>📉 <strong>25% improvement</strong> in learning outcomes by reducing hallucinations through system constraints.</li>
  </ul>
</div>

<h2>Education</h2>

<div style="margin-bottom: 25px;">
  <div class="edu-row">
    <strong>M.Sc. Computer Science (Artificial Intelligence)</strong>
    <span>Apr 2025 – Present</span>
  </div>
  <div class="subtitle">Albert Ludwig University of Freiburg</div>
  <ul>
    <li>Current Grade: <strong>2.5 (Gut)</strong></li>
  </ul>
</div>

<div>
  <div class="edu-row">
    <strong>B.E. Computer Science</strong>
    <span>Sep 2020 – Aug 2024</span>
  </div>
  <div class="subtitle">N.M.A.M Institute of Technology</div>
  <ul>
    <li>Final Grade: <strong>9.33/10 CGPA</strong> (First Class with Distinction)</li>
  </ul>
</div>

<br>
<hr>
<div align="center" style="margin-top: 30px; font-size: 0.9em; color: #586069;">
  <p>© 2025 Karan Anchan. Powered by GitHub Pages.</p>
</div>

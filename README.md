<div align="center">

<img src="assets/banniere.png" alt="Alex Armel Dahoui — AI Engineer, Full-Stack Developer, Founder of VORA" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?lines=Hello%2C+I%27m+Armel+Dahoui+%F0%9F%91%8B;AI+graduate+%E2%80%94+Medical+Imaging+%26+Deep+Learning;Brain+CT+segmentation+%E2%80%94+Dice+0.96;Founder+of+VORA+%E2%80%94+building+OkMeca&font=Fira+Code&size=24&duration=3000&pause=1000&color=7C90FF&center=true&vCenter=true&width=720" alt="Typing SVG"/>

<a href="https://www.linkedin.com/in/alex-armel-dahoui"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://armel.coredia.space"><img src="https://img.shields.io/badge/Portfolio-7C90FF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<a href="mailto:alexdahoui0@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/Vora-bj"><img src="https://img.shields.io/badge/VORA-07080D?style=for-the-badge&logo=github&logoColor=white" alt="VORA"/></a>
<a href="https://wakatime.com/@58a2586d-0503-4c1d-b94b-4bafe54c753a"><img src="https://wakatime.com/badge/user/58a2586d-0503-4c1d-b94b-4bafe54c753a.svg?style=for-the-badge" alt="WakaTime"/></a>

</div>

## ⚡ About Me

I'm an **Artificial Intelligence graduate** from IFRI – University of Abomey-Calavi (Benin), applying for a
**research master's in AI (fall 2027)**. My bachelor's thesis, graded **Très bien (highest honours)**, uses deep
learning to segment brain CT scans for the early detection of **ischemic stroke**.

I work at the crossroads of **AI research** and **production software**: I train and evaluate models, and I also
ship them inside real products used by real people, from a DICOM viewer for clinicians to apps on the App Store.

- 🔬 **Research interests** — medical image analysis, deep-learning segmentation, neuro-imaging and stroke
  imaging, learning with few annotations, model robustness and uncertainty, AI for health in low-resource settings.
- 🧠 **AI experience** — deep learning and data engineering internship at TARGECH (France, remote), AI / back-end
  developer at NOVEK AI, AI track internship at the IT department of Benin's Ministry of Foreign Affairs.
- 🚀 **Founder of [VORA](https://github.com/Vora-bj)** — a software company building SaaS platforms, mobile apps and
  AI products; currently building **OkMeca**.

## 🔬 Research

### Automatic segmentation of brain CT scans for early detection of ischemic stroke
<sub>Bachelor's thesis · 2026 · Grade: <b>Très bien</b> · Supervisors: Dr Arnaud Ahouandjinou (CAMES Associate Professor) and Dr Wahabou Taba Chabi</sub>

| Step | What I did | Result |
|---|---|---|
| **Data** | 194 annotated non-contrast brain CT scans (CNHU-HKM, Cotonou), 342 images after augmentation | Test set of 138 cases (80 healthy, 58 stroke) |
| **Segmentation** | U-Net segmenting the cerebral vascular territories (ACA, MCA, PCA) | **Dice 0.96 · IoU 0.93** |
| **Radiomics** | 19 texture features (GLCM, GLRLM) measuring inter-hemispheric asymmetry | Interpretable asymmetry markers |
| **Classification** | SVM + XGBoost + AdaBoost ensemble detecting sulcal effacement | **AUC 0.843** · accuracy 76.8 % |
| **Deployment** | Web app (Django REST, React) reading DICOM images, showing segmentation and effacement score | Usable by clinicians |

<sub>Python · TensorFlow/Keras · scikit-learn · scikit-image · OpenCV · Roboflow · Google Colab (GPU)</sub>

## 🧠 AI Projects

| Project | Field | Highlights |
|---|---|---|
| **[AI4CKD](https://github.com/Dossou2003/AI4CKD)** | Clinical ML | Predicts the stage of chronic kidney disease from clinical data, risk-factor analysis — **87 % accuracy** (XGBoost, scikit-learn) |
| **Land-law AI assistant** | NLP · multimodal | Text, audio and image chatbot on Benin's land laws, built in 48 h at the ASIN AI Hackathon 2025 (Whisper, Transformers, FAISS) |
| **UniSafe+** 🏆 | Emotion AI | Campus safety platform detecting distress with AI — **winner, AUF Hackathon 2024** (TensorFlow, React Native) |
| **RAG assistant** | LLM · RAG | Semantic search and grounded answers over an organisation's documents — **50 % less time** searching (LangChain, FAISS) |
| **[Pet image classification](https://github.com/Dossou2003/Pet-Image-Classification-Project)** | Computer vision | CNN image classifier with pretrained architectures (PyTorch) |

## 🏆 Awards

- 🥇 **Winner — AUF Hackathon (UniSafe+)**, Agence universitaire de la Francophonie, 2024
- 🥇 **Winner — Blockchain Innovators Challenge (EpargnChain)**, Africa Blockchain Institute, Tether, TON Foundation, 2024
- 🏅 **AI Hackathon "Le foncier intelligent"**, ASIN, ANDF & LuxDev, 2025

## 🚀 What I'm Building

<a href="https://okmeca.com"><img src="assets/okmeca.png" alt="OkMeca — the all-in-one platform for car repair shops" width="100%"/></a>

**OkMeca**, by VORA, is the all-in-one platform for car repair shops: quotes, live repair tracking, invoicing, stock
and payments, on mobile and web. Launching in 2026.

## 🛠️ Tech Stack

### 🧠 AI, Vision & Data
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras"/>
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
</p>

### 🌐 Software Engineering
<p align="left">
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=expo&logoColor=white" alt="React Native"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

## 📊 GitHub Activity

<p align="center"><sub>Generated every day by a GitHub Action, private repositories included.</sub></p>

<div align="center">
  <img src="https://raw.githubusercontent.com/Alex200329/Alex200329/sortie/dossou-stats.svg" alt="GitHub stats" width="49%"/>
  <img src="https://raw.githubusercontent.com/Alex200329/Alex200329/sortie/dossou-serie.svg" alt="Contribution streak" width="49%"/>
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/Alex200329/Alex200329/sortie/dossou-langages.svg" alt="Most used languages" width="49%"/>
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/Alex200329/Alex200329/sortie/dossou-contributions.svg" alt="Contributions in the last year" width="100%"/>
</div>

## 🎖️ GitHub Trophies

<div align="center">
  <img src="https://raw.githubusercontent.com/Alex200329/Alex200329/sortie/dossou-trophees.svg" alt="GitHub trophies" width="100%"/>
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Alex200329/Alex200329/sortie/dossou-snake-dark.svg"/>
  <img src="https://raw.githubusercontent.com/Alex200329/Alex200329/sortie/dossou-snake-light.svg" alt="Contribution snake" width="100%"/>
</picture>

<div align="center">
<br/>
<sub>Made with ❤️ in Cotonou</sub>
</div>

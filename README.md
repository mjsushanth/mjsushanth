# 👋 Hello, I'm Joel M  

AI enthusiast & Data Engineer | M.S. in Artificial Intelligence @ Northeastern University  

I like **AI/ML research**, **enterprise-scale data engineering**, building systems in **deep learning, NLP, and computer vision**.  

---

## Research & Academic Projects

- **FinRAG/FinSights: Production-Grade Financial Intelligence System** — Hybrid dual-path architecture combining structured queries (DuckDB/SQL dimension tables) with semantic retrieval. Processes 72M→1M sentences via stratified sampling with temporal weighting across regulatory eras. [Check this out!](https://github.com/Finsights-MLOps/FinSights/blob/main/README.md)
  - **Data Engineering Pipeline**: DuckDB stratified sampling (30+ SQL scripts) with weighted multi-objective scoring, fuzzy-matched integrations, conditional temporal stratification.
  - **Advanced RAG Engineering**: Sentence-level embeddings, **multi-query expansion with window-hopping retrieval**, citation provenance via document headers for exact traceability. Polars/Parquet logging, serverless-ready architecture.
  - Achieves $0.017/query cost, no managed DB overhead ($0.05/month vs $70-700/month). 
- **Text-to-Pose Diffusion**: Built a CLIP-conditioned diffusion model with cross-attention + anatomical loss for 3D pose generation.
  - [See Design here.](https://github.com/mjsushanth/CLIP-Conditioned-Diffusion-T2Pose-Generation/blob/main/DESIGN_README.md)
  - Has deeply researched concepts on Motion/3D data: (pose representation, N-joint hierarchical mapping, kinematic chains, pelvis-spine-extremity validation) and the architecture of **Hybrid CNN-Transformer Diffusion**, CLIP Semantic Encoding & Projection, Dual-Pass CFG and Anatomical Constraint Enforcement.
  - [See Report here.](https://github.com/mjsushanth/CLIP-Conditioned-Diffusion-T2Pose-Generation/blob/main/RESEARCH_README.md)
- **Multi-View 3D Scene Analysis**: Created a 10k+ LOC pipeline with MV scene analysis, pose-guided filtering, occlusion handling, and RANSAC validation on ETH3D. [See Design Flow.](https://github.com/mjsushanth/MultiView_Image_Analysis_CS5330/blob/main/IMPLEMENTATION_README.md) 
- **Protein Structure Prediction**: Implemented HMM, CRF, BiLSTM; CRF reached 67% accuracy on CB513 using evolutionary + context features. [See Report here.](https://github.com/mjsushanth/ML_Protein_Structure_Prediction/blob/main/Report%20-%20Protein%20Struct%20Prediction%20HMM%2C%20CRF%2C%20LSTM%2C%20ML.pdf)
- **SocrAItic Circle**: Multi-Agent Debate LLMs workflow, designed with multi-phase debate cycles, iterative refinement, YAML-driven orchestration, and judge modules.  
- **Artist Classification**: Compared SVM-SIFT-BoVW, CAEs, VAEs, and CNNs; SVM achieved 89% accuracy on 50-class dataset.

## Other works:
- Multi-vector ViT+CLIP with LoRA and ColBERT-style MaxSim retrieval [Demo Notebook.](https://github.com/mjsushanth/mlops-labs-portfolio/tree/main/Late_Interaction_MVR_PEFT_LoRA)
- An example workflow of ML-Serving using Gitub CI/CD and AWS Lambda, SAM Infrastructure. [Src Code.](https://github.com/mjsushanth/mlops-labs-portfolio/tree/main/CICD_ML_Infr_Lambda) , Notes here. [Study notes.](https://github.com/mjsushanth/Study_Notes_Obsd/blob/main/ML%20Ops%20Notes/Study%20-%20AWS%2001%20CICD%2C%20Lambda%20etc..md)
- Usage of Optuna and MLFlow using a synthetic time-series generator [Src Code.](https://github.com/mjsushanth/mlops-labs-portfolio/tree/main/MLFlow_Synth_TimeSeries_Lab)

---

## 📫 Connect with Me  
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/joemjs/)  
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:markapudi.j@northeastern.edu)  
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mjsushanth)  

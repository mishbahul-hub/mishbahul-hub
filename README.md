# Hi, I'm Mishbahul 👋

I'm a pre-final year Electrical Engineering student at **NIT Silchar** who got into machine learning through NLP. Most of what I build sits somewhere between **language models, search and translation**, with a side interest in audio.

- 🔬 Research intern on the **Indian Knowledge Systems (IKS)** internship, working on Vision Transformers for Indian folk music classification
- 📄 Co-authored a paper at **WMT 2026 (ACL)**, where our team had the best results in 4 of 5 language pairs
- 🌱 Currently going deeper on LLM agents, retrieval and evaluation
- 📫 Reach me at **islammishbahul68@gmail.com**

<p>
  <a href="https://www.linkedin.com/in/mishbahul-al-islam-353375329/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:islammishbahul68@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www2.statmt.org/wmt26/pdf/2026.wmt-1.173.pdf"><img src="https://img.shields.io/badge/WMT%202026-Paper-555555?style=flat" alt="WMT 2026 paper"></a>
</p>

---

## 🚀 Featured projects

### [JobPilot: AI job-matching agent](https://github.com/mishbahul-hub/JobPilot)
A LangGraph agent that searches, saves and rates jobs, and remembers each user's profile in Postgres. Every reply is checked in code, so it only recommends jobs a tool actually returned.

- **Hybrid search** over 900 job postings: pgvector + Postgres full-text, merged with Reciprocal Rank Fusion and reranked by an LLM. nDCG@10 went from **0.616 → 0.872**.
- **Personalisation** from an uploaded resume, plus an agent eval with an LLM judge (**100% tool-call accuracy**).
- Shipped with Docker, 45 backend tests and CI on GitHub Actions.

`Python` `LangGraph` `FastAPI` `PostgreSQL` `pgvector` `Gemini` `React` `Docker`

### [Low-resource Arabic–Asian machine translation (WMT'26)](https://github.com/mishbahul-hub/WMT-26)
Our team's system for the WMT 2026 Arabic–Asian shared task.

- Benchmarked NLLB-200, MADLAD-400 and OPUS-MT with BLEU, chrF++ and COMET.
- Fine-tuned NLLB-200-600M on 170k Arabic–Hindi pairs: BLEU **21.03 → 28.22**, beating a model 5× its size.
- Built a pivot pipeline (NLLB-200 + IndicTrans2) with QLoRA, gaining up to **6.68 BLEU**.

`PyTorch` `Hugging Face` `PEFT` `LoRA/QLoRA` `sacreBLEU` `COMET`

### Indian folk music classification (research)
Style classification on unseen recordings from the Indian Folk Music Dataset, funded by the Ministry of Education.

- Found that random segment splits leak songs into the test set, and built a leak-free song-grouped 5-fold protocol.
- Added a convolutional stem to the External-Attention ViT (EAViT), raising song macro-F1 from **65.8% → 79.6%**.
- Paper under review.

`PyTorch` `Vision Transformers` `Audio` `scikit-learn` `XGBoost`

---

## 📄 Publications

- M. Karim, F. Ahmed, **M. A. Islam**, S. R. Laskar, R. H. Laskar. *NERDS-NITS at WMT 2026: Pivot-Based and Direct Neural Machine Translation for Arabic–Asian Low-Resource Language Pairs.* Proceedings of WMT 2026 (ACL), pp. 2325–2330. [[PDF]](https://www2.statmt.org/wmt26/pdf/2026.wmt-1.173.pdf)
- *Indian Folk Music Style Classification on Unseen Recordings with a Convolutional-Stem External-Attention Transformer.* Under review.

## 🏆 Achievements

- **WMT'26 Arabic–Asian MT shared task**: best system results in 4 of 5 language pairs (Arabic to Hindi, Bengali, Urdu and Indonesian)
- **Flipkart Gridlock Hackathon 2.0**: shortlisted for Round 2 from thousands of teams, with an AI/ML traffic solution

---

## 🛠️ Tech stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**ML & NLP**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

**LLMs & agents**  
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)

**Backend, data & DevOps**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

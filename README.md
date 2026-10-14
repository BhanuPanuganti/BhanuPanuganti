# Bhanu Panuganti

<!-- Animated header -->
<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1D4ED8,100:06B6D4&height=220&section=header&text=Bhanu%20Panuganti&fontSize=48&fontColor=FFFFFF&animation=fadeIn&fontAlignY=36&desc=Applied%20AI%20%7C%20Machine%20Learning%20%7C%20Generative%20AI&descAlignY=58&descSize=17" width="100%" alt="Bhanu Panuganti — Applied AI and Machine Learning"/>

  <a href="https://github.com/BhanuPanuganti">
    <img src="https://komarev.com/ghpvc/?username=BhanuPanuganti&style=for-the-badge&color=2563EB&label=PROFILE+VIEWS" alt="Profile views"/>
  </a>
  <a href="https://github.com/BhanuPanuganti?tab=repositories">
    <img src="https://img.shields.io/badge/Explore-My%20Repositories-06B6D4?style=for-the-badge&logo=github&logoColor=white" alt="Explore repositories"/>
  </a>

  <br/>

  **Building intelligent systems that solve real-world problems.**

  *From retrieval-augmented generation and AI agents to computer vision and regional-language NLP.*

</div>

---

## About Me

Hi! I'm **Bhanu Panuganti**, an undergraduate student pursuing a B.Tech in Artificial Intelligence and Data Science at **IIIT Sri City** (2023–2027).

I'm passionate about developing practical AI systems that combine machine learning, modern language models, intelligent retrieval, and software engineering. I enjoy taking projects beyond model development by building complete applications, evaluating their performance, and deploying them for real-world use.

- Currently exploring **Generative AI, agentic systems, RAG, and AI engineering**.
- Building multi-agent applications, semantic retrieval systems, computer vision pipelines, and NLP tools.
- Interested in model evaluation, retrieval optimization, system design, and production-ready AI.
- Experienced with Python-based ML pipelines, APIs, interactive applications, and containerized deployment.
- Always interested in collaborating on meaningful AI/ML projects.

```python
class Bhanu:
    def __init__(self):
        self.education = "B.Tech AI & Data Science | IIIT Sri City"
        self.interests = [
            "Generative AI & Agentic Systems",
            "Machine Learning & Deep Learning",
            "RAG & Semantic Search",
            "Computer Vision & 3D Perception",
            "Natural Language Processing",
        ]
        self.approach = "Build → Evaluate → Improve → Deploy"

    def current_goal(self):
        return "Build reliable AI systems with measurable impact"
```

## Tech Stack

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=python,java,c,cs,r&theme=dark" alt="Python, Java, C, C sharp, and R"/>

### Machine Learning & Data Science

<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
<img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras"/>
<img src="https://img.shields.io/badge/XGBoost-189F63?style=for-the-badge" alt="XGBoost"/>
<img src="https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge" alt="LightGBM"/>
<img src="https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logoColor=black" alt="CatBoost"/>

### Generative AI & Retrieval

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
<img src="https://img.shields.io/badge/LangGraph-1D4ED8?style=for-the-badge" alt="LangGraph"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge" alt="Qdrant"/>
<img src="https://img.shields.io/badge/FAISS-1877F2?style=for-the-badge" alt="FAISS"/>
<img src="https://img.shields.io/badge/BM25%20%7C%20RRF%20%7C%20Reranking-334155?style=for-the-badge" alt="Retrieval techniques"/>
<img src="https://img.shields.io/badge/Embeddings%20%7C%20Semantic%20Search-0F766E?style=for-the-badge" alt="Embeddings and semantic search"/>

### Backend, Deployment & Tools

<img src="https://skillicons.dev/icons?i=fastapi,flask,docker,git,github,linux,postgres,mysql,redis,vscode,visualstudio&theme=dark" alt="Backend, databases, deployment, and development tools"/>

<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
<img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black" alt="Google Colab"/>
<img src="https://img.shields.io/badge/Unity-222222?style=for-the-badge&logo=unity&logoColor=white" alt="Unity"/>

</div>

## Featured Projects

A selection of projects across Generative AI, applied machine learning, computer vision, and NLP.

<table>
<tr>
<td width="50%" valign="top">

### 01. AI Indian Rail Travel Assistant

**Multi-agent AI · Hybrid RAG · FastAPI**

A conversational railway assistant that combines intent-aware agent routing, document retrieval, and timetable-based journey planning.

- LangGraph multi-agent architecture.
- Qdrant vector search with BAAI embeddings.
- BM25, Reciprocal Rank Fusion (RRF), and cross-encoder reranking.
- FastAPI backend and Streamlit interface.
- Gemini integration with Groq fallback.

**Focus:** Agent orchestration, retrieval quality, and backend engineering.

[Repository →](https://github.com/BhanuPanuganti/AI-Indian-Rail-Travel-Assistant)

</td>
<td width="50%" valign="top">

### 02. Hybrid AI Game Recommendation Engine

**Semantic Search · Embeddings · Retrieval**

A recommendation engine designed to discover games through natural-language descriptions, genres, and semantic similarity.

- Dataset containing 44K+ games.
- 768-dimensional embeddings.
- Custom NumPy-based retrieval.
- Approximately 5 ms retrieval latency in the reported setup.
- Flask, Docker, and Hugging Face Spaces.

**Focus:** Embedding-based retrieval, ranking, and efficient inference.

[Repository →](https://github.com/BhanuPanuganti/game-recommender)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 03. LiDAR-Based Pedestrian Detection

**3D Computer Vision · Deep Learning**

A point-cloud perception project exploring pedestrian detection using classical ML and deep-learning approaches.

- DBSCAN-based baseline.
- XGBoost feature-based detection with 48.9% reported recall.
- PointPillars implementation using PyTorch and OpenPCDet.
- Reported PointPillars mAP of 0.6.
- Visualization and evaluation pipeline.

**Focus:** 3D perception, point-cloud processing, and model evaluation.

[Repository →](https://github.com/BhanuPanuganti/LiDAR-based-Pedestrian-Detection)

</td>
<td width="50%" valign="top">

### 04. PII Detection & Redaction Tool

**NLP · Document Processing · Privacy**

A document-processing application for identifying and redacting personally identifiable information across common document formats.

- PDF, DOCX, and image inputs.
- Presidio and custom recognizers.
- Regular expressions and structured-identifier validation.
- Blackout and synthetic-replacement modes.

**Focus:** Practical NLP, privacy-aware processing, and document automation.

[Repository →](https://github.com/BhanuPanuganti/PII-Redaction-Tool)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 05. Telugu Document Writer Assistant

**Regional-Language NLP · Text Generation**

A Telugu writing assistant that combines statistical language modeling and neural approaches for text completion and correction.

- N-gram language models.
- HMM-based trigram transitions.
- GRU-based reranking.
- Seq2Seq LSTM with attention.
- Approximately 79% reported test accuracy for the evaluated task.

**Focus:** Regional-language NLP, language modeling, and text correction.

[Repository →](https://github.com/BhanuPanuganti/Telugu-Document-Writer-Assistant)

</td>
<td width="50%" valign="top">

### 06. AutoStream AI Sales Agent

**Agentic AI · Conversational Automation**

A conversational AI application designed to answer knowledge-base questions and support lead qualification.

- LangGraph conversation workflow.
- FastAPI backend.
- Retrieval-assisted responses.
- Structured lead-information collection.

**Focus:** Agent workflows, conversational state, and business automation.

[Repository →](https://github.com/BhanuPanuganti/autostream-agent)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 07. Eye-Tracking Wheelchair Control System

**Computer Vision · Human-Computer Interaction**

An assistive mobility project using eye tracking to translate gaze direction into wheelchair-control commands.

- More than 85% reported gaze-classification accuracy.
- Less than 100 ms reported latency.
- Calibration and blink-based mode switching.
- Safety interlocks and Unity simulation through UDP.

**Focus:** Real-time inference, assistive technology, and safety-aware interaction.

*Current work: user testing and system evaluation.*

</td>
<td width="50%" valign="top">

### 08. Brain Tumor Classification

**Deep Learning · Medical Image Classification**

A web application combining pretrained feature extraction with traditional machine-learning classifiers.

- EfficientNetB0 feature extraction.
- KNN, SVM, and Random Forest.
- Soft-voting ensemble.
- Interactive Streamlit application.

**Focus:** Transfer learning, feature engineering, ensemble learning, and deployment.

[Live demo →](https://brain-tumor-classification-epxips2eogqygyxrvyemfc.streamlit.app/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 09. Seoul Bike Rental Prediction

**Regression · Ensemble Learning**

A demand-prediction application for estimating bicycle rental demand from environmental and temporal features.

- XGBoost regression.
- Feature engineering and model evaluation.
- Reported adjusted R² of 0.952.
- Interactive Streamlit application.

**Focus:** Predictive analytics, regression, and model deployment.

</td>
<td width="50%" valign="top">

### 10. Fetal Health Classification

**Imbalanced Classification · Model Evaluation**

A classification workflow exploring approaches for predicting fetal health categories from cardiotocography data.

- Exploratory data analysis.
- Log transformation and preprocessing.
- SMOTE for class imbalance.
- Stratified validation and ensemble modeling.

**Focus:** Imbalanced learning, evaluation methodology, and responsible interpretation of medical ML results.

</td>
</tr>
</table>

> **Note:** Reported metrics reflect results from the respective project experiments. They are not directly comparable across different datasets or evaluation setups.

## Other Work & Experiments

Beyond my featured projects, I have explored:

- **MLOps Rolling-Mean Signal Pipeline:** A reproducible Python batch pipeline for OHLCV data with configurable rolling means, YAML configuration, Docker, logging, and metrics.
- **British Airways Data Science Simulation:** Customer-booking prediction and passenger/lounge-eligibility analysis through the Forage virtual experience.
- **Game Development:** Bubble Brawl 3D and Dungeon of Dharma, combining gameplay logic, interactive systems, and Unity development.
- **Machine Learning Experiments:** Feature selection, ensemble learning, imbalanced classification, and cross-validation.

## Achievements & Leadership

- **Amazon ML Summer School 2025** — Completed the machine-learning learning program.
- **Wizard of OZ — Data Science Challenge 2025** — Secured 2nd place.
- **Agentica 2.0 National Hackathon 2026** — Core organizer for the national hackathon, featuring a ₹2,00,000 prize pool.
- **IOTA Projects Club** — Domain Lead for Game Development; involved in project activities and technical sessions.

## What I'm Currently Working On

- Advancing my understanding of **LLMs, RAG evaluation, and agentic AI systems**.
- Improving retrieval quality through hybrid search, embeddings, and reranking.
- Evaluating my eye-tracking wheelchair-control system with multiple users.
- Building reliable AI applications with clear evaluation, reproducible pipelines, and deployment-ready backends.

## GitHub Analytics

<div align="center">

  <a href="https://github.com/BhanuPanuganti">
    <img height="180" src="https://github-readme-stats.vercel.app/api?username=BhanuPanuganti&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true" alt="Bhanu's GitHub statistics"/>
  </a>
  <a href="https://github.com/BhanuPanuganti">
    <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BhanuPanuganti&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Bhanu's most-used programming languages"/>
  </a>

  <br/>

  <img width="95%" src="https://github-readme-streak-stats.herokuapp.com/?user=BhanuPanuganti&theme=tokyonight&hide_border=true" alt="GitHub contribution streak"/>

  <br/>

  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=BhanuPanuganti&theme=tokyo-night&hide_border=true&area=true" alt="GitHub contribution activity graph"/>

</div>

## Let's Connect

I'm open to connecting with people working on AI/ML, Generative AI, research, and engineering projects.

<div align="center">

  <a href="https://www.linkedin.com/in/bhanu-panuganti-43a497284/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/BhanuPanuganti">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://bhanupanuganti.github.io/Bhanu-Portfolio-Main/">
    <img src="https://img.shields.io/badge/Portfolio-Explore-06B6D4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
  </a>

  <br/><br/>

  **Build thoughtfully. Evaluate rigorously. Deploy responsibly.**

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:1D4ED8,100:0F172A&height=100&section=footer" width="100%" alt=""/>

</div>

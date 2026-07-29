# TalentMatch: AI-Powered Resume–Job Matching & Recommendation Platform

TalentMatch is an AI-powered Resume–Job Matching Engine that analyzes uploaded resumes and recommends suitable job roles using a hybrid approach combining **TF-IDF**, **BERT semantic embeddings**, and **skill gap analysis**. The system provides explainable recommendations through an interactive web interface and REST APIs built with FastAPI.

---

## 📷 Hero Screenshot

![Recommendation Dashboard](assets/recommendation.png)
*Figure 12: Recommendation Dashboard*

---

## ✨ Features

- **PDF Resume Processing:** Upload PDF resumes with automatic text extraction, cleaning, and preprocessing.
- **Hybrid Similarity Engine:** Combines TF-IDF vector representations with BERT semantic embeddings for accurate job matching.
- **Skill Extraction & Gap Analysis:** Automatically identifies candidate skills and highlights skill gaps for recommended roles.
- **Explainable AI (XAI):** Provides transparent, explainable recommendations detailing why a job match was suggested.
- **FastAPI REST API:** Fully functional RESTful API endpoints complete with interactive Swagger UI documentation.
- **Interactive Dashboard:** Modern web frontend built with HTML, CSS, and JavaScript.
- **Containerized Deployment:** Ready-to-deploy with Docker and Docker Compose.

---

## 🏗️ System Architecture

![Architecture](assets/architecture.png)
*Figure 1: System Architecture*

TalentMatch follows a modular architecture where uploaded resumes are processed through preprocessing, feature extraction, semantic representation, similarity computation, and recommendation generation. The backend communicates with the AI engine through FastAPI APIs, while the frontend provides an interactive interface for users.

---

## 🔄 End-to-End Workflow

![Workflow](assets/workflow.png)
*Figure 8: Processing Pipeline Workflow*

### Processing Pipeline

1. **Resume Upload**
2. **PDF Text Extraction**
3. **Text Cleaning & Preprocessing**
4. **Skill Extraction**
5. **TF-IDF Representation**
6. **BERT Embedding Generation**
7. **Job Dataset Processing**
8. **Cosine Similarity Computation**
9. **Hybrid Score Calculation**
10. **Job Recommendation Generation**

---

## 🛠️ Technology Stack

| Category | Technologies |
| :--- | :--- |
| **AI & Machine Learning** | Sentence Transformers (BERT), TF-IDF, Cosine Similarity, Scikit-learn, Pandas |
| **Backend** | Python, FastAPI |
| **Frontend** | HTML5, CSS3, JavaScript |
| **DevOps & Tools** | Docker, Docker Compose, Git, GitHub |

---

## 📚 Subjects Covered

This project integrates concepts from multiple Computer Science domains:

- Information Retrieval
- Artificial Intelligence
- Deep Learning
- Data Science
- Full Stack Development
- Software Testing
- DevOps

---

## 📂 Project Structure

```text
resume-job-matching-engine/
│
├── backend/
├── core/
│   ├── preprocessing/
│   ├── representation/
│   ├── deep_learning/
│   ├── matching/
│   ├── recommendation/
│   ├── skills/
│   └── explainability/
│
├── frontend/
├── evaluation/
├── tests/
├── data/
├── Dockerfile
├── docker-compose.yml
└── requirements.txt
```

## 🖼️ Screenshots

### Upload Interface
![Upload UI](assets/upload-ui.png)  
*Figure 10: Resume Upload Interface*

### API Documentation (Swagger)
![Swagger](assets/swagger.png)  
*Figure 9: Swagger Interactive API Documentation*

### Recommendation API Response
![JSON Output](assets/api-response.png)  
*Figure 13: JSON API Response for Recommendation Engine*

---

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/melonpan1007/resume-job-matching-engine.git](https://github.com/melonpan1007/resume-job-matching-engine.git)
   cd resume-job-matching-engine
   
## 🚀 Run Using Docker Compose

Start the application using Docker Compose:

```bash
docker compose up --build
```

---

## 🔌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/` | Health Check |
| `POST` | `/upload-resume` | Upload PDF Resume |
| `POST` | `/recommend` | Generate Job Recommendations |
| `POST` | `/extract-skills` | Extract Skills from Resume Text |
| `POST` | `/compare-skills` | Perform Skill Gap Analysis |

---

## 👥 Team

### **Affaan Shaikh**
- Core Architecture
- Deep Learning Integration
- Similarity Engine
- Explainability
- System Integration
- Evaluation & Analytics

### **Sayali**
- TF-IDF Representation
- Feature Vectorization
- Evaluation Support
- Deep Learning Support

### **Vivan**
- Skill Extraction
- Recommendation Engine
- Frontend Development
- Backend Integration

---

## 🔮 Future Scope

- [ ] Resume improvement suggestions & actionable feedback
- [ ] Automated course recommendation engine based on skill gaps
- [ ] Live LinkedIn job post integration
- [ ] Cloud deployment (AWS / Azure / GCP)
- [ ] User authentication, user profiles, and historical tracking
- [ ] LLM-based deep resume analysis & summarization
- [ ] Multi-language resume parsing and support

---

## 📜 License & Academic Context

This project was developed as an **Academic Project** as part of the **Artificial Intelligence & Data Science** curriculum at **Bharati Vidyapeeth (Deemed to be University)**.

The project is intended for educational and research purposes.

# PARTH JAIN

+91-9479735365 | parthjain0722@gmail.com | [linkedin.com/in/jainparth22](https://linkedin.com/in/jainparth22) | [github.com/jainparth22](https://github.com/jainparth22)

## EDUCATION

**Indian Institute of Technology, Madras** — Chennai, Tamil Nadu
*BS in Data Science and Applications (Online)* | May 2023 – May 2027

**Vellore Institute of Technology** — Bhopal, Madhya Pradesh
*BTech in Computer Science and Engineering* | Jun 2023 – Jun 2027

## EXPERIENCE

### Hugging Face | Open Source Contributor — Remote

- Designed and deployed a production-grade, two-tier semantic matching engine on Hugging Face Spaces, combining exact O(N) taxonomy mapping via FlashText with dynamic semantic gap-filling using Key-BERT and BGE-small embeddings.
- Optimized inference memory footprint by 50% by sharing a single global SentenceTransformer instance between the embedding encoder and KeyBERT, preventing duplicate model loading in RAM.
- Implemented a hybrid retrieval scoring algorithm utilizing asymmetric semantic similarity (with BGE query prefixes), two-tier skill coverage (with BFS cycle-protection), and heuristic quality scoring, outperforming standard regex-based parsers.

### MPOnline Limited (Govt. of MP & TCS JV) | AI/ML & Software Engineering Intern                        
Training-focused Internship           						                                      May 2026 – July 2026 
- Completed a structured internship program covering full-stack development, MVC architecture, REST APIs, relational database design, and SQL/ER modeling.
- Developed a comprehensive full-stack project applying RESTful APIs, MVC architecture, and relational database concepts.
-	Built AI/ML pipelines involving feature engineering, model evaluation, and neural networks for Natural Language Processing tasks.

## PROJECTS

### Placement Portal System | Flask, Vue.js, SQLite, SQLAlchemy, Redis, Celery, JWT

- Developed a scalable, event-driven multi-role placement platform featuring 40+ REST APIs, utilizing a layered architecture to decouple business logic from data access, reducing administrative manual effort by an estimated 30%.
- Designed a stateless authentication middleware pipeline using JSON Web Tokens (JWT) and Role-Based Access Control (RBAC), ensuring strict data isolation and secure session management without relying on server-side session state.
- Achieved a 40% reduction in p95 API latency and a 25% boost in responsiveness under concurrent loads by implementing a cache-aside pattern with Redis and decoupling heavy background tasks via an asynchronous Celery message broker.

### Smart MCQ Solver (Deep Learning Ensemble) | PyTorch, Hugging Face, LightGBM, WandB

- Constructed a Stacking Ensemble meta-learner using LightGBM over 3 Deep Learning models (EmbeddingNN, RoBERTa, BiLSTM), achieving a Kaggle Private score of 0.75084 (MAP@3), surpassing the 0.73 cutoff by 2.8%.
- Engineered a custom BiLSTM with attention pooling over frozen RoBERTa token embeddings (768-dim), extracting rich contextual features while preventing catastrophic overfitting on a highly constrained 2,000-row dataset.
- Tracked and compared 10+ model architectures and hyperparameter configurations using Weights & Biases (WandB), optimizing the final ensemble weights based on empirical validation-to-test distribution shifts.

### Machine Learning Text Classification Pipeline | Python, Scikit-learn, TF-IDF, Stacking Ensembles

- Built an end-to-end ML pipeline for a 200,000+ record dataset, constructing a 60,000-dimensional sparse feature space combining word n-grams and character n-grams with sublinear TF-IDF scaling.
- Achieved a 0.826 Macro F1 score by designing a Stacking Ensemble with 4 diverse linear base models (LinearSVC, LR, SGD, PassiveAggressive), applying Out-Of-Fold (OOF) Stratified 3-Fold CV to generate unbiased meta-features for a Logistic Regression meta-learner.
- Mitigated extreme class imbalance (21:1 ratio) through targeted class-weight optimization and hinge-loss max-margin constraints, deliberately rejecting noisy synthetic oversampling (SMOTE) which degraded performance in high-dimensional sparse space.

## TECHNICAL SKILLS

- **Languages:** Python, SQL (PostgreSQL, SQLite), C/C++
- **Backend & System Design:** Flask, FastAPI, REST APIs, System Design (Event-Driven Architecture, Caching Strategies, Message Queues), Redis, Celery, SQLAlchemy, JSON Web Tokens (JWT), Role-Based Access Control (RBAC)
- **AI/ML Libraries & Tools:** Scikit-learn, Hugging Face (Spaces), Sentence-Transformers (BGE, SBERT), Gradio
- **AI/ML & DL Techniques:** Machine Learning Algorithms (Ensembles, SVM, Regression), Feature Engineering (TF-IDF, Dimensionality Reduction), Model Evaluation (k-fold CV, Grid/Randomized Search), Natural Language Processing (NLP), Semantic Matching, XGBoost, LightGBM
- **Tools & Platforms:** Git, Docker, Linux, AWS, Vercel, Supabase, VS Code, Jupyter Notebook

## EXTRACURRICULAR & CERTIFICATIONS

**DSA & Problem Solving:** 900+ Day Coding Streak on GeeksforGeeks; solved 100+ LeetCode problems focused on algorithms and data structures.

**AI/ML & Software Engineering Internship:** Completed an intensive dual-track program at MPOnline Limited (Govt. of MP & TCS JV), culminating in a comprehensive full-stack project utilizing MVC architecture, RESTful APIs, and relational database design (SQL/ER Diagrams). Developed end-to-end ML pipelines incorporating feature engineering, model evaluation, and neural networks for Natural Language Processing tasks.

**Certifications (AI/ML):** Machine Learning Specialization (DeepLearning.AI), NLP with Transformers using Hugging Face (IIT Madras), Machine Learning (NPTEL, IIT Kharagpur)

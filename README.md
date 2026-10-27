

##  About me 

Final-year BTech CSE @KIIT | Looking to build a career in data & Software

Started as an intern in GTM at Antbox, moved into Marketing Ops at Qapita - spent months in the data: cleaning it, structuring it, building workflows around it. That's what got me hooked on the technical side.
I've seen how business teams think and what they actually need from data and I want to be the person who builds it. Whether that's pipelines, analysis, or just making messy data usable.
Also exploring AI/ML on the side - curious about where data engineering and AI intersect.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-grey?style=for-the-badge&logo=python)
![SQL](https://img.shields.io/badge/SQL-grey?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-grey?style=for-the-badge&logo=postgresql)
![SQLite](https://img.shields.io/badge/SQLite-grey?style=for-the-badge&logo=sqlite)
![FastAPI](https://img.shields.io/badge/FastAPI-grey?style=for-the-badge&logo=fastapi)
![Pydantic](https://img.shields.io/badge/Pydantic-grey?style=for-the-badge&logo=pydantic)
![Ollama](https://img.shields.io/badge/Ollama-grey?style=for-the-badge&logo=ollama)
![Pandas](https://img.shields.io/badge/Pandas-grey?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-grey?style=for-the-badge&logo=numpy)
![PowerBI](https://img.shields.io/badge/Power_BI-grey?style=for-the-badge)
![Tableau](https://img.shields.io/badge/Tableau-grey?style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-grey?style=for-the-badge&logo=microsoft-excel)
![Airflow](https://img.shields.io/badge/Apache_Airflow-grey?style=for-the-badge&logo=apacheairflow)
![Jupyter](https://img.shields.io/badge/Jupyter-grey?style=for-the-badge&logo=jupyter)
![Git](https://img.shields.io/badge/Git-grey?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-grey?style=for-the-badge&logo=github)
![AWS](https://img.shields.io/badge/AWS-grey?style=for-the-badge&logo=amazonaws)
![C++](https://img.shields.io/badge/C++-grey?style=for-the-badge&logo=cplusplus)
![REST API](https://img.shields.io/badge/REST_APIs-grey?style=for-the-badge)




---

## Featured Projects

- **[MissionPulse](https://github.com/chikki2999/MissionPulse)**: supply chain risk analytics with PostgreSQL and Power BI
- **[Qapita Client Ops ETL Pipeline](https://github.com/chikki2999/qapita-etl-pipeline)**: automated Airflow pipeline with weekly reporting
- **[Dark Data Discovery & Insight Engine](https://github.com/chikki2999/dark-data-project)**: customer support ticket analysis with a Power BI dashboard

---

## Analytics Projects

### MissionPulse: Supply Chain Risk Analytics & Operational Intelligence

**Tech:** Python, Pandas, PostgreSQL, SQL, Power BI, Jupyter, Git

- Built an end-to-end supply chain analytics solution to identify operational risk across **32,065 logistics operations** and support data-driven intervention prioritization.
- Designed a complete analytics pipeline covering **data profiling, cleaning, feature engineering, risk scoring, PostgreSQL data modeling, SQL analytics, and Power BI visualization**.
- Engineered a composite **MissionPulse Risk Score** using disruption likelihood, ETA variation, traffic congestion, port congestion, supplier reliability, lead time, and inventory pressure.
- Built analytical tables and SQL views in **PostgreSQL** to transform processed operational data into business-ready datasets for reporting and dashboarding.
- Developed an interactive **Power BI dashboard** with executive KPIs, risk-driver analysis, risk distribution, daily risk trends, and a high-risk operational queue.
- Evaluated **machine learning approaches** for operational risk prediction and identified limitations in the available target/feature structure and model reliability.
- Chose a transparent, interpretable **risk-scoring framework** instead of forcing an ML solution that did not provide sufficient analytical value for the business use case.
- Validated key metrics across **Python, PostgreSQL, SQL outputs, and Power BI** to ensure consistency and reliability of reported results.

**Key Results:** 5,131 high-risk operations | 16.0% high-risk rate | 54.21 average risk score

🔗 **Source Code:** [github.com/chikki2999/MissionPulse](https://github.com/chikki2999/MissionPulse)

---

### Dark Data Discovery & Insight Engine

**Tech:** Python, Pandas, Excel, Power BI

- Built an end-to-end analytics pipeline to analyze **8,000+ customer support tickets** and uncover hidden customer pain points.
- Cleaned and processed unstructured text using Python, removing noise and standardizing ticket descriptions.
- Performed keyword analysis and categorized issues into business-level problem groups.
- Identified Software Bugs, Data Issues, Login Issues, Payment Issues, and Order Issues as the dominant drivers of support volume.
- Designed an interactive Power BI dashboard to visualize problem categories and support data-driven prioritization.

🔗 **Source Code:** [github.com/chikki2999/dark-data-project](https://github.com/chikki2999/dark-data-project)

---

## ETL & Automation Projects

### Qapita Client Ops ETL Pipeline

**Tech:** Python, Pandas, Apache Airflow, SQL, SQLite

- Built a 5-task automated ETL pipeline using Apache Airflow to replace manual client operations workflows from my internship at Qapita.
- Extracted client task data from a REST API and transformed it using Pandas to flag overdue items and assign priority levels.
- Loaded clean data into a SQLite database and ran SQL aggregations to auto-generate Weekly Business Review summaries.
- Implemented automated alerting for critical overdue tasks, replicating the manual reporting process that previously took hours.
- Scheduled the pipeline to run every weekday at 9am with automatic retry logic for failed tasks.

🔗 **Source Code:** [github.com/chikki2999/qapita-etl-pipeline](https://github.com/chikki2999/qapita-etl-pipeline)

---

## AI/ML Projects

### Aamrai AI Impact Analyzer

**Tech:** Python, Streamlit, NLP, RAG, ChromaDB, Sentence-Transformers, Hugging Face

- Built an end-to-end AI decision support system for analyzing the environmental and social impact of urban infrastructure projects.
- Designed a RAG-based document intelligence pipeline to process PDFs using chunking, embeddings, and semantic retrieval.
- Used Sentence-Transformers (all-MiniLM-L6-v2) to generate embeddings and ChromaDB for vector storage and retrieval.
- Developed an environmental impact engine to estimate CO₂ loss, heat increase, and canopy reduction from project inputs.
- Built an NLP-based sentiment analysis module to extract insights from citizen feedback and unstructured text data.
- Designed an AI decision layer that combines retrieved documents, environmental metrics, and sentiment signals to generate recommendations.

🔗 **Source Code:** [github.com/chikki2999/Aamrai-AI-Impact-Analyzer](https://github.com/chikki2999/Aamrai-AI-Impact-Analyzer)

---

### Facial Recognition System for Remote Hiring

**Tech:** TensorFlow, PyTorch, OpenCV, SpaCy, Hugging Face, MongoDB, AWS S3

- Developed an AI/ML-driven facial recognition and analysis system to support remote hiring workflows.
- Built a deep learning pipeline to detect, process, and analyze facial features using computer vision techniques.
- Integrated NLP tools (SpaCy, Hugging Face) to extend analysis capabilities within candidate evaluation workflows.
- Designed scalable data storage using MongoDB for structured data and AWS S3 for media handling.
- Enabled efficient processing and structured insights to assist recruiters in candidate assessment.

🔗 **Source Code:** [github.com/chikki2999/emotion-detection](https://github.com/chikki2999/emotion-detection)

---

## Beyond Academics

- **Sports & Esports:** active in multiple sports, especially swimming, and a keen follower of esports.
- **Content & Social Media:** manage small influencer accounts, handling content and collaborations.
- **Editing & Film:** strong at video editing, with a growing interest in the film industry.
- **Creative Work:** freelance artist exploring content creation.
- **Networking:** regularly attend networking events and photoshoots.

---

## 📬 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harshita-gupta-73795130a/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact.guptaharshita@gmail.com)

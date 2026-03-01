# -Autonomous-Multi-Agent-Intrusion-Detection-System
Agentic AI + RAG Intrusion Detection System

📌 Project Overview
This project presents an Autonomous Multi-Agent Intrusion Detection System (IDS) that integrates:
Agentic AI architecture


Machine Learning–based threat detection


Explainable AI (SHAP)


Retrieval-Augmented Generation (RAG) for mitigation guidance


The system detects anomalies, classifies cyber attacks, generates alerts, and provides context-aware mitigation advice.

🎯 Project Themes Covered
 Agentic AI System


 RAG (Retrieval-Augmented Generation)



🧠 Problem Statement
Traditional intrusion detection systems can detect attacks but often:
Do not operate autonomously


Do not explain decisions


Do not provide mitigation recommendations


This project builds an intelligent, modular, multi-agent cybersecurity system capable of:
Detecting abnormal network behavior


Classifying attack types


Generating contextual alerts


Providing mitigation advice using a knowledge-based RAG system



🏗 System Architecture
🔹 1. Anomaly Agent
Model: Isolation Forest


Trained on BENIGN traffic only


Detects abnormal network flows


🔹 2. Threat Classification Agent
Model: Random Forest Classifier


Classifies:


BENIGN


DDoS


PortScan


Brute Force


🔹 3. Alert Agent
Generates actionable security alerts


Prioritizes anomalies and confirmed threats


🔹 4. Planner (Orchestrator Agent)
Coordinates anomaly detection and threat classification


Produces structured reports


🔹 5. RAG Mitigation Agent
Vector Database: FAISS


Embeddings: OpenAI


Retrieves mitigation strategies from cybersecurity knowledge base


Generates context-aware mitigation advice



📊 Dataset
CIC-IDS 2017 Dataset


Filtered for:


BENIGN


DDoS


PortScan


Brute Force


⚠️ Dataset not included due to size limitations.

🚀 Features
✔ Multi-agent AI system


✔ Real-time Streamlit dashboard


✔ Explainable AI using SHAP


✔ RAG-based mitigation assistant


✔ Modular reusable IDS class


✔ Saved trained models for reuse



🛠 Tech Stack
Python


Pandas, NumPy


Scikit-learn


SHAP


Streamlit


LangChain


FAISS


OpenAI API



📂 Project Structure
Autonomous-Multi-Agent-IDS/
│
├── Final_Autonomous_Multi_Agent_IDS.ipynb
├── requirements.txt
├── README.md
│
└── models/
   ├── anomaly_detector.pkl
   ├── label_encoder.pkl
   ├── scaler.pkl
   └── threat_classifier.pkl

📈 Results
High classification performance on filtered attack types


Real-time simulation of network flows


Automated alert generation


Context-aware mitigation suggestions using RAG



🔮 Future Improvements
Integrate real-time network streaming


Deploy via Docker


Add deep learning–based IDS (LSTM/Transformer)


Integrate SOC automation tools



👨‍💻 Author
 Estifanos Balcha Biftu
 Graduated – Information Technology
 Cybersecurity & AI Systems

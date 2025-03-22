# Smart India Hackathon Workshop
# Date:20.03.25
## Register Number:212224040244
## Name:Prathiksha .R
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
```
1. Virtual Board Room Experience

Uses video conferencing or avatars for realistic interactions.

Allows multi-panelist participation with real-time scoring.

2. Comprehensive Report Generation

Generates detailed performance reports.

Highlights strengths, weaknesses, and improvement areas.

3. Mock Interview Practice Platform

Allows candidates to practice with AI-driven evaluation.

Provides feedback on speaking clarity, confidence, and technical depth.

4. Knowledge Graph for Deep Analysis

Maps scientific concepts and domain relationships.

Ensures interview questions align with DRDO standards.

5. Multi-Language Support

Enables candidates to respond in their preferred language using NLP.
```
## Proposed Solution / Architecture Diagram

![image](https://github.com/user-attachments/assets/3a193260-b15c-404e-8bc2-deef574ec9ac)

## Use Cases
![Screenshot 2025-03-12 131141](https://github.com/user-attachments/assets/c7e8b6f7-4496-40b6-b52e-91d1271f046d)


## Technology Stack
Frontend:
React.js / Angular / Vue.js → For a modern, responsive web interface. Tailwind CSS / Material UI → For a clean and structured UI/UX. WebRTC / Zoom SDK / Jitsi → For video conferencing integration.

Backend:
Python (FastAPI / Django / Flask) → For handling API requests and business logic. Node.js (Express.js) → For real-time data processing (optional). GraphQL / REST APIs → For structured data communication.

AI/NLP Models:
OpenAI GPT / BERT / T5 → For dynamic question generation. spaCy / NLTK → For text processing & NLP tasks. Hugging Face Transformers → For response evaluation and scoring. Google Speech-to-Text / OpenAI Whisper → For speech-to-text conversion. VADER / TextBlob → For sentiment analysis of candidate responses.

Database & Storage:
PostgreSQL / MySQL → For structured candidate/interview data storage. MongoDB / Firebase → For unstructured and semi-structured data. AWS S3 / Google Cloud Storage → For storing interview transcripts and video recordings.

Authentication & Security:
OAuth2 / SAML / JWT → For secure user authentication. Role-Based Access Control (RBAC) → To restrict permissions based on user roles. End-to-End Encryption (E2EE) → For secure video and data transmission.

Cloud & DevOps:
AWS / Azure / Google Cloud → For cloud hosting and scalability. Docker / Kubernetes → For containerization and microservices deployment. Prometheus / Grafana → For system monitoring and analytics.

## Dependencies
```
1. Intelligent Profile-Based Question Generation
AI analyzes candidate resumes to generate relevant questions.

Starts with ice-breakers, then moves to technical/managerial topics.

Dynamic follow-up questions based on previous answers.

2. Dynamic Difficulty Adjustment
Begins with baseline questions.

Adjusts complexity based on candidate performance.

Simplifies questions if the candidate struggles to assess knowledge depth.

3. Real-Time NLP-Based Evaluation
Uses NLP to analyze candidate responses.

Evaluates relevance, completeness, and accuracy.

Provides real-time feedback to panelists.

4. Expert Support System
AI assistant suggests follow-up questions.

Identifies knowledge gaps to guide panelists.

5. Score Normalization & Bias Mitigation
AI ensures fair scoring by detecting inconsistencies.
Provides score explanations to enhance transparency.
```

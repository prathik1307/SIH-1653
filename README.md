# Smart India Hackathon Workshop
# Date:
## Register Number:
## Name:
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1. Intelligent Profile-Based Question Generation

Leverage AI-driven profiling to analyze the candidate's submitted resume, educational background, and technical expertise.
Use this data to:
Generate relevant ice-breaking questions for rapport-building.
Tailor technical and managerial questions to match the candidate’s field (e.g., Electronics, Mechanical, Computer Science).
Adapt follow-up questions based on the complexity and accuracy of previous responses.

2. Dynamic Difficulty Adjustment

Implement an adaptive interview flow:
Start with baseline questions.
If answered well, progressively increase complexity.
If struggling, pivot to simpler questions to explore knowledge depth.
3. Real-Time NLP-Based Evaluation

Utilize Natural Language Processing (NLP) to analyze candidate responses:
Assess relevance, completeness, and technical accuracy.
Provide real-time feedback to the panel on candidate response quality.
Highlight keywords, concepts, and depth of knowledge.

4. Expert Support System

Develop an AI Assistant for Panel Members that:
Suggests follow-up questions based on candidate responses.
Identifies gaps in responses to guide panelists in probing deeper.

5. Score Normalization & Bias Mitigation

Implement a calibrated scoring system that:
Uses AI to identify inconsistencies in expert scoring.
Provides insights to panel members to maintain fairness.
Offers explanations for AI-suggested scores to improve transparency.

6. Virtual Board Room Experience

Simulate a real-life boardroom using:
Virtual Avatars or Interactive Video Conferencing.
Realistic multi-panelist interaction with simultaneous scoring.

7. Comprehensive Report Generation

Automatically generate a detailed performance report that includes:
Candidate strengths, weaknesses, and improvement areas.
Comparative scoring with other candidates for better decision-making.

8. Mock Interview Practice Platform

Create a mock interview module where candidates can practice:
AI evaluates their responses and provides guidance.
Feedback on speaking clarity, confidence, and technical depth.

9. Knowledge Graph for Deep Analysis

Develop a knowledge graph that maps:
Key scientific concepts.
Relationships between technical domains.
This ensures questions and answers align with DRDO’s requirements.

10. Multi-Language Support

Integrate multi-language NLP capabilities to ensure candidates from diverse backgrounds can respond comfortably in their preferred language.

## Proposed Solution / Architecture Diagram


## Use Cases


## Technology Stack

Frontend: React.js / Angular for UI
Backend: Node.js / Django for logic handling
AI/NLP: Python (e.g., spaCy, BERT for semantic analysis)
Database: PostgreSQL / MongoDB
Video Conferencing: WebRTC / Jitsi
Cloud Services: AWS / Azure for scalability
Security: OAuth 2.0, AES Encryption for data protection

## Dependencies

Availability of domain-specific datasets for model training.
Collaboration with RAC experts to define question relevance metrics.
Integration with existing DRDO systems for seamless data flow.

# Smart India Hackathon Workshop
# Date: 14-03-2025
## Register Number: 212224240169
## Name: Thanushree M
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1. AI-Driven Interview Panel
AI acts as a virtual interviewer and can either conduct fully automated interviews or assist human interviewers with real-time question suggestions based on the candidate’s expertise.
AI dynamically adjusts the difficulty level of questions based on the candidate’s responses.

  2. Interactive Candidate Profiling & Adaptive Questioning
Before the interview, candidates provide key details (resume, skills, expertise, projects, etc.).
AI analyzes the profile and generates relevant, tailored questions rather than using a fixed question bank.

  3. Speech & Sentiment Analysis for Candidate Responses
Speech-to-text conversion for analyzing spoken responses.
AI-driven sentiment analysis to assess confidence, hesitation, and communication skills.
Keyword-based NLP grading to check if responses match the expected technical depth.

  4. Real-Time AI Scoring & Evaluation Dashboard
AI provides real-time feedback to the interviewer on the candidate’s response quality.
Generates a quantifiable score for the candidate’s technical & managerial skills.
Final report includes strengths, weaknesses, and improvement areas for the candidate.


  5️. Gamified & Adaptive Learning Experience (Optional)
After the interview, the system provides learning recommendations based on weak areas.
AI-based mock interview mode where candidates can practice and improve their responses.



## Proposed Solution / Architecture Diagram

![WhatsApp Image 2025-03-14 at 10 21 23_45025d2c](https://github.com/user-attachments/assets/0567f0a6-781c-4057-bea7-dddf7109749e)




## Use Cases
![image](https://github.com/user-attachments/assets/10ad6ce4-76ec-474a-b9e4-9431e2984352)


## Technology Stack

#### Frontend (Web Application):

React.js / Vue.js (UI)

WebRTC (for live video interviews)

#### Backend (AI & Processing):

Python (Django/FastAPI) or Node.js (Express.js)

PostgreSQL / MongoDB (for candidate profiles & scores)

#### AI & NLP Modules:

GPT-4 / BERT (for AI-driven questioning & scoring)

Speech-to-Text APIs (Google Speech API, Whisper)

Sentiment Analysis (TensorFlow/NLP models)

#### Deployment:

AWS / Azure / GCP (Cloud hosting)

Docker & Kubernetes (Scalability)

## Dependencies

AI Model Training & Optimization

Continuous improvement required for accuracy.
Fine-tuning models (GPT-4/BERT) with domain-specific datasets.
Ongoing monitoring and bias reduction in AI-driven questioning.
Data Mapping & Collection

Estimated Time: 20-25 days.
Collecting real interview data, historical hiring success metrics, and job-role-specific competency frameworks.
Preprocessing and structuring data for AI-based question generation & evaluation.
Speech & Sentiment Analysis Integration

Estimated Time: 15-20 days.
Integrating and fine-tuning Speech-to-Text APIs (Google Speech API, Whisper).
Developing NLP-based sentiment & confidence analysis models.
Video & Communication Module Development

Estimated Time: 30 days.
Implementing WebRTC/Twilio for real-time video interviews.
Ensuring smooth recording, playback, and assessment of interview sessions.
Frontend & Backend Development

Estimated Time: 40-45 days.
Frontend: UI/UX development using React.js/Vue.js with interactive dashboards.
Backend: Setting up APIs, database structures, and AI integration.
Cloud Deployment & Scalability Planning

Estimated Time: 15-20 days.
Deploying on AWS/Azure/GCP with Docker & Kubernetes for scalability.
Load balancing & security configuration.
Budget Allocation

Revised Budget: INR 15-20 Lakhs.
Major Costs:
Advanced AI model training & fine-tuning.
Speech & sentiment analysis tools.
Cloud storage & processing costs.
Security & compliance measures.

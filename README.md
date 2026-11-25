# Hi, I'm Dhruv Kajare 👋

### Software Engineer | AI Engineer | Agentic Systems | Backend Engineering

I build intelligent software systems where **AI reasoning meets real-world engineering**.

My work spans backend architecture, AI-driven automation, multi-agent systems, machine learning pipelines, computer vision, API integrations, databases, and full-stack application development.

I enjoy taking complex problems and engineering systems that go beyond prototypes — combining intelligent decision-making, software architecture, data pipelines, integrations, and validation into functional applications.

---

### What I Build

- **Intelligent Systems:** Agentic AI workflows, LLM applications, multi-agent architectures, AI automation and decision systems.
- **Software Engineering:** Backend services, API design, system architecture, integrations, databases, application logic and engineering workflows.
- **Applied AI:** Machine learning, computer vision, NLP, OCR, voice AI and intelligent data processing.
- **Developer Systems:** Automated debugging, repository analysis, code modification workflows and software validation.

---

# 🚀 Featured Engineering Projects

## Momentum
### Agentic AI Recruitment & Real-Time Voice Interview System

> An adaptive interview intelligence system that transforms traditional question-answer interviews into dynamic, context-aware evaluation sessions.

Momentum is engineered around an agentic interview orchestration architecture that dynamically manages interview progression rather than relying on predefined question sequences.

The system interprets candidate information, job requirements, interview context and live responses to orchestrate an evolving interview session.

**Inside the system:**

- **Agentic Interview Orchestration:** A reasoning layer dynamically determines which interviewer should take the next turn, what competency should be evaluated and how the interview should progress.
- **Multi-Panel Intelligence:** Simulates distinct interviewer perspectives such as technical, HR and hiring-manager evaluations while maintaining shared interview context.
- **Adaptive Question Generation:** Generates follow-up questions based on previous responses, missing evidence, contradictions, vague explanations and the candidate's demonstrated knowledge.
- **Dynamic Interview Control:** Determines whether to explore a topic further, transition between interview stages, conclude an evaluation or initiate a system-design assessment.
- **Real-Time Voice Architecture:** Integrates speech recognition and voice synthesis into an interruptible conversational interface with controlled turn-taking.
- **Context-Aware Evaluation:** Evaluates responses against role-specific competencies, evidence and assessment criteria instead of relying solely on isolated answers.
- **System-Design Evaluation:** Extends interviews into structured problem-solving and architectural discussions.
- **Backend Orchestration:** Connects AI reasoning, interview state, candidate information, conversational workflows and application services.

**Engineering focus:** Agent orchestration, real-time communication, state management, adaptive reasoning, API integration, conversational architecture and backend systems.

**Tech Stack:** Python, FastAPI, Next.js, ElevenLabs, Groq, Gemini, Firebase, MongoDB

---

## VectoraFix
### Agentic AI Software Debugging & Automated Code Repair Engine

> An AI-driven software remediation system designed to investigate failures, trace root causes, generate targeted patches and validate software repairs through controlled engineering workflows.

VectoraFix approaches software debugging as a structured engineering pipeline rather than a single LLM-generated answer.

It coordinates repository investigation, code analysis, repair planning, isolated code modifications, independent review and verification.

**Inside the system:**

- **Incident Intelligence:** Ingests error logs, stack traces and incident evidence to identify failure symptoms and investigate potential root causes.
- **Repository Intelligence:** Inspects repository structure, source code, dependencies, relevant files and existing tests to establish engineering context.
- **Structural Code Analysis:** Uses code-aware inspection and AST-based analysis to understand relationships and identify relevant execution paths.
- **Parallel Investigation:** Enables specialized investigation workflows to analyze different aspects of a software issue.
- **Repair Planning:** Synthesizes investigation findings into a proposed repair strategy before modification.
- **Human-in-the-Loop Approval:** Introduces an approval checkpoint before code changes are executed.
- **Isolated Repair Execution:** Performs targeted modifications within disposable Docker environments to reduce the impact of repair operations on the host environment.
- **Independent Code Review:** Examines generated patches and diffs for unintended changes, scope violations and potential regressions.
- **Automated Verification:** Uses tests and verification checks to assess whether proposed fixes resolve the investigated issue.
- **GitHub Integration:** Connects repository operations, commits and push workflows through GitHub APIs.
- **Recovery-Aware Workflows:** Preserves repair artifacts to support recovery and retry when repository operations fail.

**Engineering focus:** Software debugging automation, repository analysis, multi-agent orchestration, AST-based analysis, Docker isolation, patch generation, testing, GitHub integrations and fault-aware workflows.

**Tech Stack:** Python, FastAPI, Next.js, LangGraph, LangChain, Gemini, MongoDB, Docker, GitHub API

---

## ChequeTrak
### Intelligent Cheque Processing & Verification Pipeline

> A multi-stage computer vision and OCR pipeline engineered to extract, normalize and verify information from handwritten and printed Indian bank cheques.

ChequeTrak combines specialized object detection, multiple OCR engines, image preprocessing and domain-specific verification logic to transform cheque images into structured information.

**Inside the pipeline:**

- **Specialized Field Detection:** Uses eight dedicated YOLOv8 Nano models to detect cheque fields including payee name, date, amounts, account information, signature and MICR.
- **Detection-Driven Processing:** Extracts individual regions of interest and routes them into specialized recognition workflows.
- **Primary OCR Pipeline:** Uses PaddleOCR to recognize text from detected cheque regions.
- **Fallback Recognition Architecture:** Routes challenging recognition cases through alternative OCR and transformer-based recognition using EasyOCR and TrOCR.
- **Image Processing:** Applies image preprocessing and OpenCV-based transformations to improve recognition on challenging image regions.
- **Text Normalization:** Converts extracted information into standardized formats for downstream validation.
- **Financial Data Validation:** Cross-verifies numerical amounts against amounts written in words.
- **MICR-Based Verification:** Uses MICR extraction and validation as part of cheque verification.
- **Confidence-Aware Processing:** Integrates recognition confidence and fallback workflows to improve processing reliability.
- **Structured Output:** Converts processed cheque information into structured data through a Streamlit-based interface.

<escape>**Model Performance:**</escape> Achieved approximately **0.960 mAP@0.5** across the eight cheque-field detection models.

**Engineering focus:** Computer vision, model specialization, OCR orchestration, fallback pipelines, image processing, validation logic and structured data extraction.

**Tech Stack:** Python, YOLOv8, PyTorch, PaddleOCR, EasyOCR, TrOCR, OpenCV, Streamlit, NumPy, Pandas

**Research:** Published at the 2026 2nd International Conference on Computing, Communication and Green Engineering (CCGE).

---

## AI-Driven Energy Supply Chain Resilience Platform
### Intelligent Risk Analysis & Procurement Decision System

> A decision-support architecture designed to assess energy supply-chain risks using geopolitical intelligence, supplier evaluation, maritime route analysis and AI-driven insights.

The system combines external intelligence, structured risk evaluation and LLM-powered information extraction to support procurement and supply-chain decision-making for import-dependent economies.

**Inside the system:**

- **Geopolitical Intelligence Pipeline:** Processes geopolitical information and news relevant to energy supply-chain risks.
- **Automated Intelligence Extraction:** Uses LLM-driven processing to extract structured insights from unstructured information.
- **Supplier Risk Assessment:** Evaluates supplier-related risk factors to support comparative supplier analysis.
- **Maritime Route Intelligence:** Analyzes routes and strategically important maritime chokepoints.
- **Risk-Aware Procurement:** Integrates supplier and route intelligence into procurement-oriented decision workflows.
- **Supplier Preference Engine:** Supports supplier prioritization based on contextual risk and decision factors.
- **Decision Engine:** Combines multiple sources of intelligence into structured decision-support outputs.

**Engineering focus:** AI information extraction, NLP pipelines, decision systems, data processing, risk modeling and modular backend architecture.

**Tech Stack:** Python, FastAPI, Qwen2.5, Hugging Face Transformers, Pandas, Scikit-learn, NLP

---

# 🛠️ Technical Stack

### Programming Languages

`Python` `C++` `JavaScript` `TypeScript` `SQL`

### Software & Backend Engineering

`FastAPI` `Flask` `REST APIs` `Node.js` `MongoDB` `Firebase` `Git` `GitHub API`

### AI & Machine Learning

`PyTorch` `TensorFlow` `Scikit-learn` `Hugging Face Transformers` `Machine Learning` `Deep Learning` `NLP` `Computer Vision` `Object Detection` `OCR`

### AI Systems & LLM Engineering

`Agentic AI` `LLM Applications` `Multi-Agent Systems` `Generative AI` `RAG` `Vector Search` `AI Orchestration` `Prompt Engineering` `AI Decision Systems`

### Web Development

`React.js` `Next.js` `Node.js` `HTML5` `CSS`

### Computer Vision & Data Processing

`OpenCV` `Pandas` `NumPy` `Streamlit` `Image Processing` `Data Pipelines`

---

# 📚 Research & Publication

### ChequeTrak: An Integrated Deep Learning Pipeline for Handwritten Text Extraction and Signature Region Extraction in Indian Bank Cheques

Published at the **2026 2nd International Conference on Computing, Communication and Green Engineering (CCGE)**.

Research focused on combining deep-learning-based cheque field detection, OCR architectures, handwritten text recognition and verification mechanisms into an integrated cheque processing pipeline.

---

# 🏆 Achievements

- 🥈 **2nd Prize** — Vidyavardhini National Project Symposium (VNPS25)
- 🏅 **Semifinalist** — HPCL PowerLab Innovation Challenge
  - Selected among the Top 34 teams from 40,000+ participating teams.

---

# ©️ Software Copyright Registrations

Software works registered with the **Copyright Office, Government of India**:

- Personalized Learning for Diverse Learners
- Personalized Learning App for Autistic Children

---

# 🎓 Education

**Bachelor of Engineering — Computer Engineering**

Vidyavardhini's College of Engineering & Technology  
University of Mumbai

**CGPA: 8.45 / 10**

---

# 🌐 Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/in/dhruv-kajare-b060b0260/)
- 📧 [Email](mailto:kajaredhruv3@gmail.com)
- 💻 [GitHub](https://github.com/kajaredhruv433)
- 🌐 [Portfolio](https://portfolio-tau-ruby-57.vercel.app/agentic-ai)

---

*Building systems. Engineering solutions. Exploring intelligent software.*

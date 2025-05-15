
# Persona AI

## 🔍 Overview
**Persona AI** is a lightweight web application that instantly customizes the user feed by predicting a user's persona—without any need for sign-in. By asking a few simple questions such as age, education, and experience, it creates a personalized feed tailored to the user's profile.

## 🌟 Features
- No login or sign-up required  
- Smart persona prediction (e.g., Beginner, Worker, etc.)  
- Dynamically generated and personalized content feed  
- Lightweight and fast front-end experience

## 🛠️ Tech Stack
- HTML  
- CSS  
- JavaScript  
- Flask (Python)

## 🚀 Getting Started

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Faizulmd13/persona-ai.git
   cd persona-ai
   ```

2. Run the app (you may need to set up a virtual environment and install Flask):
   ```bash
   pip install flask
   python app.py
   ```

3. Open `localhost:5000` in your browser to use the application.

## 💡 How It Works
Once the project is running, users are prompted to enter basic information like age, education, experience, and occupation. Clicking the "Predict Persona" button uses AI to identify the user's persona and serve a customized page based on that persona.

## ✅ Project Status
- ✔️ Project is complete
- 🔜 Future improvements include expanding persona types and generalizing its use across multiple domains and web applications.

---

# 📄 Abstract & Final Report

## Abstract
The Persona AI project aims to transform digital marketing and educational user experiences by leveraging artificial intelligence, behavioral data, multilingual NLP, and explainable personalization techniques. In Phase 5, the system is fully prepared for demonstration, documentation, and handover. This phase presents the AI system's dynamic persona detection, real-time recommendation engine, voice and multilingual capabilities, and its ability to handle high user load securely. This document includes all essential technical documentation, feedback integration, system architecture, codebase highlights, and plans for future scalability. Screenshots of the working prototype, code samples, and ERP integration diagrams are included.

---

## 1. Project Demonstration

### Overview
The Persona AI system will be presented to academic and technical stakeholders in a real-time demo environment, showcasing its ability to detect personas, adapt content, handle multilingual queries, and maintain data privacy.

### Demonstration Details
- **System Walkthrough**: From user onboarding to content display, demonstrating how the platform customizes homepages based on persona (Beginner, Professional, Freelancer, etc.).
- **Persona Switching**: Real-time change in user persona and how it reshapes the interface and content blocks dynamically.
- **Multilingual UI and Voice Demo**: Interface toggling between English and regional languages (e.g., Tamil, Hindi), with real-time voice-to-text interaction support.
- **Explainable AI Engine**: Content blocks display “Why recommended?” tags based on behavioral history and AI decisions.
- **Performance Metrics**: Demonstrate system load testing results, speed under multiple concurrent users, and PWA responsiveness.
- **Security & Privacy**: Showcase cookie management, local persona storage, encryption policies, and how users control their own data.

### Outcome
Stakeholders will observe how the AI system operates in real time, validating the success of multilingual expansion, persona blending logic, and privacy-first architecture.

---

## 2. Project Documentation

### Overview
This section provides full technical documentation of the Persona AI platform for replication, scaling, or future development.

### Documentation Sections
- **System Architecture**: Layered diagrams showing backend API flow, Supabase integration, persona classification logic, and PWA frontend interactions.
- **AI Model Explanation**: Structure and training flow of the persona prediction model, including labeled datasets and model performance graphs.
- **Codebase Documentation**:
  - **Frontend**: React/Next.js components for persona-specific pages and content loaders.
  - **Backend**: API calls to Supabase, authentication, voice and language processors.
  - **AI Model**: Code used for training and integrating persona detection with the content engine.
- **User Guide**: Instructions for platform users—how to register, view personalized content, use multilingual voice input, and give feedback.
- **Admin Guide**: Admin portal overview, persona management, system configuration, and how to monitor feedback analytics.
- **Testing Reports**: Screenshots and reports from UX tests, latency benchmarks, voice model accuracy, and security compliance checklists.

### Outcome
A full knowledge base is created to support future developers, system integrators, and stakeholders.

---

## 3. Feedback and Final Adjustments

### Overview
Feedback from mentors, users (students, professionals, retired persons), and demonstration observers was collected and analyzed.

### Steps Taken
- **Feedback Collection**: Real-time observation and structured feedback forms during demonstration sessions.
- **Usability Enhancements**: Tooltips added to icons, increased font contrast for seniors, and smoother persona transition animations.
- **AI Refinements**: Improved classification of freelancers vs. professionals based on feedback and updated training data.
- **Testing Revalidation**: Regression testing done after final updates to confirm stability and improvements.

### Outcome
The system was fine-tuned for better accessibility, classification accuracy, and user experience.

---

## 4. Final Project Report Submission

### Overview
This comprehensive final report outlines all project phases, key milestones, encountered challenges, and outcomes.

### Report Sections
- **Executive Summary**: High-level goals—AI-based personalization, scalable multilingual support, secure real-time adaptation.
- **Phase Breakdown**:
  - **Phase 1**: Problem Definition and Target Personas
  - **Phase 2**: AI Innovation and UI Prototypes
  - **Phase 3**: MVP Development and Initial Testing
  - **Phase 4**: Performance Tuning, PWA Scalability, Security Compliance
  - **Phase 5**: Demonstration, Documentation, and Handover
- **Challenges & Solutions**:
  - Real-time personalization at scale → Solved with client-side caching and indexed data.
  - Multilingual voice input → Handled using regional training datasets.
  - Feedback interpretation → Resolved via weighted feedback scores and UI flags.
- **Project Outcomes**:
  - Functional, scalable AI-driven content engine.
  - Trusted, explainable UX.
  - Full PWA compatibility and ERP readiness.

---

## 5. Project Handover and Future Works

### Overview
The final handover delivers not only the project deliverables but also a roadmap for future work, ensuring longevity and scalability of Persona AI.

### Handover Details
- **Deliverables**:
  - Full annotated codebase (frontend, backend, model).
  - Training scripts and model weights.
  - Final report, test logs, deployment scripts.
  - Diagrams: ERP integration plans, user flow, persona mapping.
  - Screenshots of working modules, multilingual demo, and source code annotations.

### Next Steps for Future Development
- **Multilingual Expansion**: Extend from two languages to eight+ regional and global languages with AI-powered translation handling.
- **Real-Time Behavior Tracking**: Integrate passive behavior monitoring (scroll depth, click maps) to evolve personas without explicit input.
- **ERP & CRM Integrations**:
  - Academic Use: Integrate with LMS and academic ERP for learning path suggestions.
  - Marketing Use: Connect with tools like HubSpot, Salesforce for lead-specific content suggestions.
- **Gamification & Personal Analytics**: Build user dashboards showing learning progression, engagement stats, and persona evolution over time.
- **AI Model Self-Training**: Enable periodic retraining using stored anonymized data to stay relevant with user trends.
- **Expanded Persona Classes**: Introduce sub-personas and hybrid personas (e.g., “Working Professional + Upskiller”).
- **Privacy-Centric Enhancements**: Zero-data retention mode, opt-out modules, consent-first analytics.

### Outcome
The project is formally handed over with rich documentation and a forward-looking roadmap, enabling academic teams or developers to scale the system, add features, or deploy it in different sectors.
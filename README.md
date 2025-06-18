
# PrepOn – AI-Powered Placement Preparation Platform  
**Try it here**: [Coming Soon]  
**Demo Video**: [Demo Link](https://drive.google.com/file/d/1-KbrT1z64TkyKWxw8mXiSct-2RR0cw6L/view?usp=drivesdk)

## 🌐 Project Overview

**PrepOn** is a full-stack AI-powered web platform built with the MERN stack and Next.js App Router, designed to streamline placement preparation for students. It integrates mock interviews with real-time transcription and feedback, NLP-powered resume building with ATS scoring, job and contest aggregation, and a community-driven support ecosystem—all in one place.

## 🚀 Key Features

- **AI-Powered Mock Interviews**  
  Conduct live or recorded mock interviews with real-time transcription using OpenAI Whisper or similar. NLP evaluates responses on fluency, tone, and content.

- **Resume Builder + ATS Checker**  
  Structured resume generation with real-time NLP feedback and ATS score prediction for improving job match.

- **Job & Contest Aggregation**  
  Automatically scrape or fetch jobs, internships, and coding contests using APIs or cron jobs, filtered by user preferences.

- **Previous Year Questions (PYQs) Repository**  
  Access and contribute to a categorized database of company-specific interview questions.

- **Leaderboard & Gamification**  
  Rank users based on performance metrics such as interview quality, resume improvement, and contributions.

- **1:1 Expert Consultations**  
  Book sessions with industry experts, integrated with payment and scheduling tools.

- **Community Forum**  
  Engage in domain-based discussions, share experiences, and seek peer support.

- **Graphical Dashboard & Notifications**  
  Personalized dashboard showing analytics, job alerts, upcoming events, and push/email notifications.

## 🧠 AI & Machine Learning

- **Speech-to-Text**: OpenAI Whisper / Google STT API  
- **NLP Feedback**: GPT, spaCy, HuggingFace Transformers  
- **Computer Vision**: OpenCV for posture and eye-contact detection during interviews  
- **ATS Matching**: Resume vs. Job Description semantic matching using embeddings

## 💻 Technologies Used

### **Frontend**
- Next.js App Router (React Framework)
- Tailwind CSS
- Shadcn/UI components
- Lucide-react icons

### **Backend**
- Node.js & Express.js (via API routes or standalone)
- MongoDB Atlas (with Mongoose or Prisma)
- OpenAI API, Whisper STT, spaCy, HuggingFace
- Stripe for payments
- Calendly/Google Calendar for scheduling

### **Other Tools & Libraries**
- React Query / SWR
- React Hook Form
- Zustand / React Context for state management
- Docker & Kubernetes (for scaling microservices)
- Sentry, Prometheus, ELK Stack (monitoring)

## 🗂️ Folder Structure (Next.js App Router)

```
/app
  /auth           --> Sign-in / Sign-up
  /dashboard      --> User dashboard
  /mock-interview --> Live / Recorded interview modules
  /resume-builder --> Resume form + ATS checker
  /job-alerts     --> Aggregated job listings
  /pyqs           --> Interview questions repo
  /leaderboard    --> Rankings
  /community      --> Forum threads
  /consultation   --> Expert booking
  /admin          --> User/content moderation
/components
/lib              --> DB, AI/NLP, CV services
/utils            --> Helpers & validators
/public           --> Static assets
```

## 📈 Future Enhancements

- **Mobile App** with React Native or Expo  
- **Predictive Analytics** for interview success likelihood  
- **Custom Video Interview System** (WebRTC)  
- **Peer-to-Peer Practice Matchmaking**  
- **Gamified Certifications and Badges**  
- **Advanced AI Resume & Interview Trainers**  
- **Localization & Multi-language Support**

## 👨‍💻 Team

1. **Rachit Kumar** (Team Lead – Machine Learning & AI Chatbot)  
2. **Aryan Raj** (Frontend & Backend)  
3. **Arya Shantanu** (Frontend & Database)  
4. **Trinetra Kumar** (Backend)

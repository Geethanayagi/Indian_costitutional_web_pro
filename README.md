# Indian_costitutional_web_pro

## 📌 Overview
**Sansthaein Aur Samvidhan** is an interactive, gamified learning platform designed to make the Indian Constitution easy to understand and engaging for all age groups.  
It simplifies complex constitutional text using **AI-powered summarization** and teaches through **3D interactive games**.  
A secondary platform tracks user progress similar to **Duolingo**, allowing learning through PDFs, videos, badges, and leaderboards.

---

## 🚀 Features

### 🎯 Constitution Learning Platform
- **3D Games built with Three.js**
    - Spin the Wheel
    - Memory Card Match
    - Snake & Ladder
    - Monopoly-style Roleplay
- Age-based difficulty levels
- Multi-language support
- Simplified constitutional articles

### 📚 Learning Progress & Tracking Platform
- Duolingo-style learning journey
- PDFs and video lessons
- Earn XP points and badges
- Leaderboards for competition

### 🤖 AI-Powered Learning
- **BART Model** for simplifying complex constitutional articles.
- **RAG (Retrieval-Augmented Generation)** for interactive Q&A grounded in actual constitutional content.
- **MongoDB** for storing original, simplified, and multilingual versions of articles.

---

## 🛠️ Tech Stack

**Frontend:**
- [Three.js](https://threejs.org/) — 3D game rendering
- HTML / CSS / JavaScript

**Backend:**
- [Node.js](https://nodejs.org/) with Express.js — API services

**Database:**
- [MongoDB](https://www.mongodb.com/) — Unstructured data storage
- Vector embeddings for RAG search

**AI/ML:**
- BART — Summarization & simplification
- Sentence-BERT — Vector embeddings for retrieval
- RAG pipeline — Context-aware answers

---

## 🏗️ System Architecture
```plaintext
User -> Frontend (Three.js UI / Learning Platform) -> Backend APIs (Node.js/Express)
 -> MongoDB (Articles, User Data, Game Metadata) -> AI Layer (BART + RAG)

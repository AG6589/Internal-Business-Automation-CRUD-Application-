# Iron Lady Assignment: Internal Business Automation

https://drive.google.com/file/d/1ZSRDEzAMW3_BQW8qjdgc9koMcEJOiQPf/view?usp=sharing

Welcome to the submission repository for the **Iron Lady Internal Business Automation** assignment. This project is divided into two key components aimed at streamlining lead management and enhancing customer engagement through AI.

## 📂 Repository Structure

The project is organized into two main directories:

### 1. [Task 1: AI Assistant Logic](./task1-ai-assistant)
- **Goal**: Define the logic, prompt engineering, and strategy for an AI agent that generates personalized follow-up messages.
- **Contents**: 
  - `AI_PROMPT.txt`: The core system prompt defining the AI's persona and rules.
  - Documentation explaining the input constraints and integration strategy.
- **Key Feature**: Designed to adapt its tone (Professional, Friendly, Persuasive) based on the lead's status and background.

### 2. [Task 2: Internal CRM Application](./task2-internal-crm)
- **Goal**: A fully tailored web application for managing leads and leveraging the AI logic from Task 1.
- **Contents**: A **React + Vite** application implementing a functional Dashboard.
- **Key Features**:
  - **Lead Table**: View, sort, and filter potential clients.
  - **CRUD Operations**: Add, Edit, and Delete leads seamlessly.
  - **AI Message Generator**: A UI tool that uses simulated AI logic to draft messages instantly.
  - **Analytics**: Visual stats for quick insights.

---

## 🚀 Quick Start Guide

To run the main CRUD application (Task 2):

1. **Navigate to the CRM directory**:
   ```bash
   cd task2-internal-crm
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Start the Development Server**:
   ```bash
   npm run dev
   ```

4. **Access the App**:
   Open your browser to the local URL provided (usually `http://localhost:5173`).

---

## 🛠️ Technology Stack

- **Frontend Framework**: React 19
- **Build Tool**: Vite
- **Styling**: Modern CSS3 (Glassmorphism design system)
- **Language**: JavaScript (ES6+)
- **State Management**: React Hooks
- **Version Control**: Git

## 📌 Development Notes

- The AI generation in the web app currently uses a determinist simulation (`aiService.js`) based on the logic defined in Task 1. It creates realistic, context-aware responses without requiring a live OpenAI API key for this demo.
- The UI is built with a "Premium" aesthetic in mind, utilizing glassmorphism and smooth animations.


https://ag6589.github.io/Internal-Business-Automation-CRUD-Application-/
---

**Author**: Arin Gupta
**Submission For**: Iron Lady Assignment

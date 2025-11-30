# CareerForge AI 💼🚀
### A Google Gemini Powered Career Concierge

## 🏆 Project Overview
**Track:** Concierge Agents
**Goal:** To democratize career coaching by providing an autonomous agent that not only optimizes resumes against ATS algorithms but conducts realistic mock interviews.

## ⚠️ Problem
Job seekers struggle with two main issues:
1. **The ATS Black Hole:** Resumes get rejected because they lack specific keywords found in the Job Description (JD).
2. **Interview Anxiety:** Candidates rarely get to practice technical questions specific to the role before the real thing.

## 💡 Solution
CareerForge AI is a **Multi-Agent System** built with the **Google AI Agent Developer Kit (ADK)**. It utilizes:
- **Agent 1 (The Auditor):** Extracts keywords and uses a **Custom Tool** (Python Code) to mathematically score the resume match.
- **Agent 2 (The Interviewer):** A stateful agent that remembers conversation history to conduct a deep-dive mock interview.

## ⚙️ Architecture
- **Model:** Google Gemini 1.5 Flash
- **Framework:** Google ADK (Agent Developer Kit)
- **Key Features:** 
  - `LlmAgent` for persona management.
  - `InMemorySessionService` for maintaining interview context.
  - `Tools` for deterministic ATS scoring.

## 🚀 How to Run
1. Open the Notebook file `career_forge.ipynb`.
2. Ensure you have your Google API Key (or Kaggle Secret).
3. Run the cells to initialize the `CareerForgeApp`.
4. Input your Resume and target Job Description.


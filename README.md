# 🧠 AI Revision Assistant for Students

A simple AI agent designed to help college students revise efficiently for exams by generating short, structured revision questions based on any given topic.

---

## 📌 Use Case

**Title:** AI Agent to Help Students Revise for Exams  
**Target User:** College students preparing for Computer Science subjects like DSA, DBMS, OOPs, and CN.  
**Problem Solved:** Many students feel overwhelmed while revising. This agent provides short, topic-specific revision questions to improve active recall and make revision less stressful.

---

## 🧱 4-Layer Prompt Architecture

### 1. 🔍 Input Understanding
**Prompt:**  
> Identify the subject and topic the student wants to revise. If unclear, ask for clarification.  
**Format:**  
`Subject: [Subject] | Topic: [Topic]`

---

### 2. 🧠 State Tracker
**Prompt:**  
> Maintain a session-based list of ✅ Revised Topics and ⏳ Pending Topics. Update based on student input.

---

### 3. 🧩 Task Planner
**Prompt:**  
> Generate 3 questions of increasing difficulty for the given subject and topic:  
> - 1 Easy (basic concept)  
> - 1 Medium (application or short logic)  
> - 1 Hard (conceptual/deeper understanding)  

---

### 4. 🗣️ Output Generator
**Prompt:**  
> Format the questions using markdown with friendly tone.  
```markdown
🧠 **Revision Questions for [Topic]**
1. [Easy Question]  
2. [Medium Question]  
3. [Hard/Conceptual Question]

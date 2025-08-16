# Task 05: Descriptive Statistics and Large Language Models

## 📘 Overview

This project explores the capabilities of Large Language Models (LLMs) like ChatGPT in understanding and interpreting structured sports data using natural language questions. The dataset used is from the **2025 Syracuse University Women’s Lacrosse** team and includes individual player statistics, team performance, and season summaries.

---

## 🗓️ Task Structure

The project is split into two periods:

### 🟩 **Period 1 (July 1–31)**: Descriptive Statistics
- Focused on basic retrieval questions (e.g., most goals, highest assists).
- Evaluated LLM’s ability to interpret structured tabular data.
- Observed high accuracy for direct metric-based questions.

### 🟦 **Period 2 (Aug 1–15)**: Judgment-Based Reasoning
- Focused on complex prompts (e.g., coaching strategy, most improved player).
- Required defining abstract metrics like consistency or impact.
- LLM evaluated on reasoning, inference, and creativity.

---

## 📊 Dataset Summary

The dataset was manually extracted from the official SU Athletics page:  
🔗 [2025 Women's Lacrosse Stats](https://cuse.com/sports/2013/1/16/WLAX_0116134638)

> ❗ Note: The raw dataset is **not included** in this repository per project guidelines.

A representative subset of 10 players was used with fields:
- Games Played (GP)
- Goals (G)
- Assists (A)
- Points (G + A)
- Shots (SH)
- Shooting Percentage (SH%)
- Draw Controls (DC)
- Turnovers (TO)

---

## 💬 Natural Language Questions

We asked 10 total prompts:

| #  | Question Topic                                  | Type         |
|----|-------------------------------------------------|--------------|
| 1  | Most goals                                       | Descriptive  |
| 2  | Highest shooting percentage                      | Descriptive  |
| 3  | Most total points                                | Descriptive  |
| 4  | Most assists                                     | Descriptive  |
| 5  | Most draw controls                               | Descriptive  |
| 6  | Highest points per game                          | Analytical   |
| 7  | High performance + low turnovers                 | Analytical   |
| 8  | Most improved player                             | Judgment     |
| 9  | Coaching focus: offense or defense               | Judgment     |
| 10 | Player to develop into a game-changer            | Judgment     |

Each prompt was evaluated for:
- Correctness (✅/🟡/❌)
- Reasoning ability
- Use of supporting stats

---

## 📈 Visualizations (Optional / Ongoing)

Planned visualizations:
- Bar chart: Top 5 scorers
- Pie chart: Shot distribution among top players
- Line chart: Simulated team performance over 19 games

These will be added to the `/scripts/` folder if completed.

---

## 📁 Repository Structure

```
Task_05_Descriptive_Stats/
├── prompts.md         ← All 10 questions, LLM answers, evaluations
├── README.md          ← This file (project overview)
├── scripts/           ← Optional Python/stat-checking/plotting scripts
```

---

## ✅ Evaluation Summary

| Metric                 | Outcome                                      |
|------------------------|----------------------------------------------|
| Descriptive Accuracy   | ✅ 100% (5/5 correct)                        |
| Inference/Reasoning    | ✅ High for well-structured prompts         |
| Creativity Handling    | 🟡 Moderate; better with guidance           |
| Failure Cases          | ❗Hallucination when context was unclear     |

---

## 📝 Submission Instructions

- Repo Name: **Task_05_Descriptive_Stats**
- Time Log Submitted:  
  - ✅ July 31st  
  - ⏳ August 15: [Submit Here](https://syracuseuniversity.qualtrics.com/jfe/form/SV_cDgnzM695AMx8d8)
- Email Repo Link to: **jrstrome@syr.edu**

---

## 🙋‍♂️ Reflections

This task demonstrated the power and limits of LLMs in structured reasoning. While stats-based questions were handled well, abstract prompts required careful guidance. The experiment was successful in highlighting where prompt engineering is essential to achieving correct and meaningful answers from AI.

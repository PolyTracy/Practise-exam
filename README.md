# CAP182 — Capstone Project: Practice Examination

## About This Practice Exam

|                       |                                  |
| --------------------- | -------------------------------- |
| **Module**      | CAP182 — Capstone Project       |
| **Assessment**  | Practice Examination (formative) |
| **Total Marks** | 36                               |
| **Platform**    | GitHub Codespaces                |

> **This is a practice examination.** It is shorter than the real exam (36 marks vs 72 marks, 2 notebooks vs 4) and uses a different dataset and scenario. However, the **types of tasks** (writing code, interpreting results, finding bugs, and communicating findings) are the same as what you will encounter in the actual examination. Use this to familiarise yourself with the format and to practise the kinds of thinking that earn marks.

---

## General Instructions

1. This practice exam consists of **two Jupyter notebooks** and **one dataset**.
2. All work should be completed within this Codespace.
3. Tasks require a **mix of Python code and written responses**:
   - **Code tasks:** Write your Python code in the provided code cells and run them.
   - **Written tasks:** Double-click the markdown cell to edit, type your answer, then click outside the cell to render it.
   - **Bug-finding / evaluation tasks:** Read the provided code carefully and explain what is wrong.
4. You may use any Python libraries available in the environment.
5. **Save your work frequently** (Ctrl+S / Cmd+S).

### A Note on Using AI Tools

In the real examination, you will have access to GitHub Copilot. You may use it for this practice exam as well. However, notice how many tasks require **interpretation, judgment, and written reasoning**. These are the tasks that distinguish students who understand the material from those who rely on code generation alone. Practise writing clear, thoughtful explanations, that is where most of the marks are.

---

## Repository Structure

```
cap182_practice_exam/
│
├── README.md                  ← You are here (Question Paper)
│
└── notebooks/
	│
	└──datasets/
   		│
    	└── online_learning.csv    ← Online learning platform dataset
    ├── 01_data_preparation_and_exploration.ipynb ← Notebook 1 (18 marks)
    └── 02_modelling_and_evaluation.ipynb         ← Notebook 2 (18 marks)
```

---

## Dataset Description

### `online_learning.csv`

Student enrollment data from an online learning platform. The platform offers courses across several categories, with both free and paid enrollment options.

| Column                         | Description                                                    |
| ------------------------------ | -------------------------------------------------------------- |
| `student_id`                 | Unique identifier for each student                             |
| `student_number`             | Internal platform student number                               |
| `age`                        | Student's age in years                                         |
| `country`                    | Student's country of residence                                 |
| `education_level`            | Highest level of education completed                           |
| `course_category`            | Category of the enrolled course                                |
| `enrollment_type`            | Whether the student enrolled for free or paid                  |
| `hours_spent`                | Total hours spent on the platform                              |
| `quiz_score_avg`             | Average score across all quizzes                               |
| `num_forum_posts`            | Number of discussion forum posts made                          |
| `video_completion_pct`       | Percentage of course videos watched (0–100)                   |
| `days_since_last_login`      | Days since the student last logged in                          |
| `previous_courses_completed` | Number of previously completed courses on the platform         |
| `satisfaction_rating`        | Student satisfaction rating (1–5 scale)                       |
| `referred_by_friend`         | Whether the student was referred by a friend (0 = No, 1 = Yes) |
| `signup_weekday`             | Day of the week the student signed up                          |
| `completed`                  | Whether the student completed the course (0 = No, 1 = Yes)     |

---

## Examination Tasks

### Notebook 1: Data Preparation & Exploration (18 marks)

| Task | Description                                                       | Type           | Marks |
| ---- | ----------------------------------------------------------------- | -------------- | :---: |
| 1    | Inspect the dataset and identify**all** data quality issues | Code + Written |   3   |
| 2    | Evaluate whether a colleague's imputation approach is appropriate | Written        |   3   |
| 3    | Fix inconsistent categories and data types in three columns       | Code           |   3   |
| 4    | Create an exploratory visualisation with interpretation           | Code + Written |   3   |
| 5    | Interpret a correlation matrix and discuss implications           | Written        |   3   |
| 6    | Choose the appropriate statistical test for three scenarios       | Written        |   3   |

---

### Notebook 2: Modelling & Evaluation (18 marks)

| Task | Description                                                              | Type           | Marks |
| ---- | ------------------------------------------------------------------------ | -------------- | :---: |
| 1    | Identify the problem type and justify algorithm selection                | Written        |   3   |
| 2    | Identify data leakage and feature selection issues; write corrected code | Written + Code |   3   |
| 3    | Train a classification model with appropriate methodology                | Code           |   3   |
| 4    | Explain why accuracy is misleading and propose better metrics            | Written        |   3   |
| 5    | Diagnose overfitting and underfitting from training vs testing results   | Written        |   3   |
| 6    | Rewrite a technical paragraph for a non-technical audience               | Written        |   3   |

---

## Mark Allocation Summary

| Notebook                       |     Code     | Written / Interpretation |    Total    |
| ------------------------------ | :----------: | :----------------------: | :----------: |
| Data Preparation & Exploration |      6      |            12            | **18** |
| Modelling & Evaluation         |      6      |            12            | **18** |
| **Grand Total**          | **12** |       **24**       | **36** |

---

## Tips for the Real Exam

- **Read before you write.** Many tasks provide code or output for you to analyse. Take time to understand what you're looking at before answering.
- **Be specific.** "The data has issues" earns fewer marks than "The `height_cm` column contains 15 entries with a 'cm' suffix that prevent numeric conversion."
- **Explain your reasoning.** A correct answer with no explanation earns fewer marks than a well-reasoned answer.
- **Consider the context.** Tasks often have a scenario (clinical, business, educational). Your answers should reflect the real-world implications, not just the technical details.
- **Don't panic about code.** If your code doesn't work perfectly, your written reasoning can still earn significant marks.

---

**Good luck!**

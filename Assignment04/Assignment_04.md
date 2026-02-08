# MIS312 Assignment 4 — Reading Python Code: Part 1

**Book Alignment:** Chapter 4  
**Primary Goal:** Trace variables and loops; predict output before running code  
**Environment:** JupyterLab (`.ipynb`)  
**Submission:** OneNote Artifact (PDF)

---

## Learning Objectives
Students will:
- Predict output by tracing variables step-by-step
- Explain what `range()` does
- Practice “read → predict → run → explain”

---

## Student Tasks

### Task 1 — Predict before you run (variables)
Create `assignment04_reading1.ipynb` and paste:
```python
x = 5
y = 2
x = x + y
y = x * 3
print("x:", x)
print("y:", y)
```

1) Predict output in a markdown cell.  
2) Run the code.  
3) Explain differences (2–3 sentences).

### Task 2 — Predict before you run (loop)
Paste:
```python
total = 0
for i in range(1, 6):
    total = total + i
print("total:", total)
```
Predict, run, explain.

### Task 3 — Modify and re-check
Change to `range(1, 11)`, predict, then run.

### Task 4 — AI explanation (required)
Ask:
> “Explain this code step-by-step using beginner language. What does `range(1, 6)` mean?”

---

## OneNote Artifact Requirements
- Predicted outputs (before running)
- Screenshots of actual outputs
- AI prompt + short summary
- Reflection: How does predicting output help you debug later?

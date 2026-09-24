# Phase 1 — Programming Foundations (8–10 weeks, ~110 hrs)

Goal: go from "I can follow along with tutorials" to "I can write, debug, and read Python and SQL on my own." Everything later in this roadmap assumes this fluency.

## Courses

### 1. Python for Everybody (Py4E) — University of Michigan
**~40–50 hrs.**
Replaces CS50x in this roadmap. CS50x opens with a week of Scratch (drag-and-drop visual programming blocks) before ever touching real code — a reasonable on-ramp for some, but a bad fit if you want to be reading and typing actual syntax from day one. Py4E skips that entirely: real Python code, explained line by line, from the first lesson, built specifically for people who have never programmed before.
- **Course home (free, including graded exercises and badges): https://www.py4e.com/** — use this site directly, not the paid Coursera specialization version of the same material (same reasoning as the CS50/edX situation: same content, but py4e.com is the genuinely free, unlimited-time version).
- Covers: variables, conditionals, functions, loops, strings, files, lists/dictionaries, and a light intro to databases — everything you need to read and write real Python confidently before CS50P below picks up the pace.

### 2. MIT 6.0001 — Introduction to Computer Science and Programming in Python (optional, extra depth)
**~40–50 hrs.**
Real MIT OpenCourseWare — lecture videos plus problem sets, free, no certificate (OCW doesn't offer one, same as the other MIT courses in this roadmap). Also pure Python from lecture one, no blocks, no C. Moves faster and assumes more than Py4E does.
- https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/
- Optional: use this if Py4E starts to feel too slow partway through, or afterward if you want a second, more rigorous pass before CS50P. Skip it entirely if Py4E → CS50P already feels solid.

### 3. CS50P — CS50's Introduction to Programming with Python
**~50 hrs.**
Harvard's dedicated Python course — no Scratch, no C, real Python syntax throughout, same as Py4E's format but faster-paced and more project-driven. This is where CS50 still belongs in your plan; only CS50x (with its block-based opening week) has been swapped out.
- **Enroll at https://cs50.harvard.edu/python/ — not edx.org.** Same reasoning as the certificate note elsewhere in this repo: only the cs50.harvard.edu (Harvard OCW) route gives a free certificate; edx.org only offers the paid $219 "Verified" certificate, even on "Audit." See [`CERTIFICATION-PATHS.md`](../../CERTIFICATION-PATHS.md).
- Covers: functions, variables, conditionals, loops, exceptions, libraries, unit testing, file I/O, and classes — the actual working vocabulary of Python.

### 4. freeCodeCamp — Relational Database Certification (SQL)
**~15–20 hrs.**
SQL is not optional for a data scientist — most real company data lives in relational databases, and SQL is one of the most-tested skills in DS interviews.
- https://www.freecodecamp.org/learn/relational-databases-v9
- Covers PostgreSQL fundamentals, joins, aggregation, subqueries — done inside your own Linux terminal environment provided by the course, so nothing to install.

### 5. freeCodeCamp — Git and GitHub, in depth
**~4–6 hrs**, beyond the crash course from Phase 0.
- https://www.freecodecamp.org/news/learn-git-in-detail-to-manage-your-code/
- Branches, merges, resolving conflicts, `.gitignore`, pull requests — you'll use all of this to keep this very repo (and your project repos) clean.

## Suggested order

Weeks 1–4: Py4E (real Python, from scratch, at a beginner-friendly pace).
Weeks 4–8: CS50P (same language, picks up the pace, adds real software-engineering habits like unit testing).
(Optional, insert anywhere it's useful) MIT 6.0001 — a second, more rigorous pass if Py4E and CS50P together still leave you wanting more depth.
Weeks 8–10: freeCodeCamp SQL certification, with Git/GitHub deepening happening in parallel in small doses.

## You're done when

- You can write a Python script from scratch that reads a file, processes it with functions, and handles errors gracefully — without copying from a tutorial.
- You can write SQL with multiple joins, `GROUP BY`, and subqueries to answer a specific question about a dataset.
- You're comfortable with `git add`, `commit`, `push`, `pull`, branches, and resolving a merge conflict.

Move to [Phase 2](../02-math-stats-foundations/README.md) (or run it in parallel — see the sequencing note in [`ROADMAP.md`](../../ROADMAP.md)).

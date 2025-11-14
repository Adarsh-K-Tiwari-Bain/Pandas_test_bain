# Pandas & NumPy Assessment — Candidate Instructions

Welcome! Follow these steps exactly. Your submission will be reviewed for **clarity, reproducibility, and Git hygiene** in addition to correctness.

---

## 1) Prerequisites
- **Git** (2.30+)
- **Python** 3.12 or 3.13 (recommended)
- **pip** (comes with Python) or **conda** (optional)
- Optional: an editor like VS Code, PyCharm, or JupyterLab


---

## 2) Clone the repository

---

## 3) Create and activate a virtual environment
Choose **one** approach (venv or conda). Do **not** install packages globally.

---

## 4) Install runtime dependencies
We’ve kept the project light—primarily **pandas** and **numpy**. Install them now:

---

## 5) Log dependencies in `requirements.txt`


Ensure `requirements.txt` is in the repository root and is **up to date** before you commit.


**Alternative (optional, more robust):**
Use `pip-tools` to pin transitive dependencies:
```bash
pip install pip-tools
echo "pandas
numpy
jupyter" > requirements.in
pip-compile requirements.in  # generates an exact, pinned requirements.txt
```

---

## 6) Explore the notebooks
The repository contains key notebook:
- `pandas_skill_test.ipynb` — **your task notebook**. Fill out the `# YOUR CODE HERE` cells.


> Keep your code clean, modular, and pythonic. Prefer vectorization over loops and document any tricky decisions inline as comments.

---

## 7) Create a README for downstream users (your own)
In addition to this file, create a **candidate-authored README** for others to follow when setting up your work. Name it **`SETUP_GUIDE.md`** (or `README_CANDIDATE.md`). It must include:
1. Environment creation instructions (venv or conda)
2. How to install packages
3. How to generate or update `requirements.txt`
4. How to launch Jupyter and run the notebook(s)
5. Any caveats (OS-specific notes, known issues, etc.)

> This is a writing/design exercise—be clear, concise, and reproducible.

---

## 8) Commit your work

---

## 9) Push to the remote repository


---

## 10) Final checklist (must-do)
- [ ] Virtual environment created and activated (no global installs)
- [ ] `pandas`, `numpy`, `jupyter` installed
- [ ] `requirements.txt` generated and committed
- [ ] `pandas_skill_test.ipynb` completed (all checks pass)
- [ ] `SETUP_GUIDE.md` written with clear setup steps
- [ ] Clean commit history (1–5 meaningful commits)
- [ ] Code pushed to the remote repository

---

Good luck—build it clean, reproducible, and professional.

# Phase 0 — Setup (1–2 weeks, ~15 hrs)

Get your tools working before touching any coursework. This is the least glamorous phase and the most skippable-feeling — don't skip it.

## Steps

1. **Install Python 3.** Get it from [python.org](https://www.python.org/downloads/) or, easier for data work, install the free [Anaconda distribution](https://www.anaconda.com/download), which bundles Python, Jupyter notebooks, and most data science libraries (pandas, numpy, matplotlib, scikit-learn) in one install.
2. **Install a code editor.** [VS Code](https://code.visualstudio.com/) (free) is the standard choice. Install the Python extension from the Extensions panel.
3. **Install Git and create a GitHub account** (if you don't already have one). GitHub account: [github.com/join](https://github.com/join). Git itself: [git-scm.com](https://git-scm.com/downloads).
4. **Learn just enough Git/GitHub to be dangerous:** freeCodeCamp's [Git and GitHub for Beginners](https://www.freecodecamp.org/news/git-and-github-for-beginners/) (video, ~1 hr) is enough to get started; you'll deepen this in Phase 1.
5. **Clone this roadmap repo to your own machine and push it to your own GitHub**, so it becomes *your* copy of record:
   ```bash
   git clone <this-repo-url>
   cd data-science-roadmap
   git remote set-url origin https://github.com/<your-username>/data-science-roadmap.git
   git push -u origin main
   ```
   (If you received this as a zip instead of a clone, run `git init`, `git add .`, `git commit -m "Initial roadmap"` first, then create an empty repo on GitHub and follow its "push an existing repository" instructions.)
6. **Set up a virtual environment** for coursework so packages don't conflict across projects:
   ```bash
   python -m venv dsvenv
   source dsvenv/bin/activate   # Windows: dsvenv\Scripts\activate
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```
7. **Open a Jupyter notebook and confirm it runs**: `jupyter notebook` from the terminal, then create a new notebook and run `print("environment works")`.

## You're done when

- You can open VS Code, write a 3-line Python script, and run it.
- You can commit a change to this repo and push it to your own GitHub.
- `jupyter notebook` opens in your browser without errors.

Move to [Phase 1](../01-programming-foundations/README.md).

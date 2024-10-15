# Essential Math for Data Science

<a href="https://mybinder.org/v2/gh/sebastianstupak/essential-math-for-data-science/HEAD?labpath=notebook" target="_blank" style="margin-bottom: 20px;">
  <img src="https://mybinder.org/badge_logo.svg" alt="Binder">
</a>

<a href="https://www.oreilly.com/library/view/essential-math-for/9781098102920/" target="_blank">
  <img align="left" src="docs/media/book-cover.jpg" alt="Essential Math for Data Science book cover" width="200" style="margin-right: 20px;">
</a>

Accompanying math from book <a href="https://www.oreilly.com/library/view/essential-math-for/9781098102920/" target="_blank">Essential Math for Data Science by Thomas Nield</a>.
This repository is not affiliated with Thomas Nield, the book "Essential Math for Data Science", or O'Reilly.
Repository was made for personal learning purposes.

<br clear="left">

## Table of Contents

- [Setup](#setup)
  - [For Unix-based systems (macOS and Linux)](#for-unix-based-systems-macos-and-linux)
  - [For Windows](#for-windows)

## Setup

### For Unix-based systems (macOS and Linux)

1. Open a terminal and navigate to your project directory.

2. Create a virtual environment:

   ```bash
   python3 -m venv .venv
   ```

3. Activate the virtual environment:

   ```bash
   source .venv/bin/activate
   ```

4. Confirm virtual environment is activated:

   ```bash
   which python
   ```

5. Install project dependencies from a requirement file:

   ```bash
   python -m pip install -r requirements.txt
   ```

6. Create a Jupyter kernel for this environment:

   ```bash
   python -m ipykernel install --user --name=essential-math-for-data-science
   ```

7. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

### For Windows

1. Open Command Prompt or PowerShell and navigate to your project directory.

2. Create a virtual environment:

   ```
   python -m venv .venv
   ```

3. Activate the virtual environment:

   ```
   .venv\Scripts\activate
   ```

4. Confirm virtual environment is activated:

   ```
   where python
   ```

5. Install project dependencies from a requirement file:

   ```
   python -m pip install -r requirements.txt
   ```

6. Create a Jupyter kernel for this environment:

   ```
   python -m ipykernel install --user --name=essential-math-for-data-science
   ```

7. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```

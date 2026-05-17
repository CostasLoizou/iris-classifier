# Iris Classifier

A beginner machine learning project that trains a decision tree to classify iris flowers using scikit-learn.
## Overview

This project uses the classic Iris dataset to train a simple decision tree model.
It shows the basic machine learning workflow: loading data, splitting into train and test sets, training a model, evaluating accuracy, and saving the results.

## Requirements

- Python 3.x
- pip
- Virtual environment (recommended)
- Packages listed in `requirements.txt`:
  - scikit-learn
  - matplotlib
  - seaborn
  - jupyter
  - pytest
  - joblib

  ## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/iris-classifier.git
   cd iris-classifier
   ```

2. Create a virtual environment:
   - Windows:
     ```bash
     python -m venv venv
     ```
   - macOS / Linux:
     ```bash
     python3 -m venv venv
     ```

3. Activate the virtual environment:
   - Windows:
     ```bash
     venv\Scripts\activate
     ```
   - macOS / Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   ## Usage

### Option 1 – Run the Jupyter notebook

1. Start Jupyter:
   ```bash
   jupyter notebook
   ```
2. Open `notebooks/iris_project.ipynb`.
3. Run the cells from top to bottom.

### Option 2 – Run the training script

From the project root:

```bash
python src/train.py
```

This will:
- Load the Iris dataset
- Train a decision tree model
- Print the model accuracy
- (If implemented) Save a confusion matrix image and the trained model into the `outputs/` folder.

## Project structure

- `notebooks/` – Jupyter notebooks for exploration.
- `src/` – Python scripts (e.g. `train.py`).
- `outputs/` – Saved model and plots (e.g. confusion matrix).
- `requirements.txt` – List of Python dependencies.
- `.gitignore` – Files and folders Git should ignore.

## Credits

This project was created as a beginner exercise to learn the basic machine learning workflow with scikit-learn and Git/GitHub.

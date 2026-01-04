# Single Neuron Model ✅

A small, self-contained project demonstrating a single neuron model (perceptron/logistic neuron) implemented and explored in a Jupyter notebook.

## Contents
- `Single_Neuron_Model.ipynb` — main notebook with code, plots and experiments
- `data/advertising.csv` — example dataset for Regression
- `data/winequality-red.csv`, `data/winequality-white.csv` — wine-quality datasets for binary classification experiments

## Goals 🎯
- Implement a single neuron (logistic/perceptron) from scratch for classification and Regression tasks
- Explore input preprocessing, training dynamics, and evaluation
- Visualize learning (loss curves, decision boundaries, confusion matrices)

## Requirements 🔧
- Python 3.8+ (Windows, Linux, macOS)
- See `requirements.txt` for pinned dependency versions (recommended for reproducibility).

Install with pip (recommended):

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Or using a virtual environment:

```bash
python -m venv .venv
# PowerShell
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

Or with conda:

```bash
conda create -n snm python=3.10
conda activate snm
pip install -r requirements.txt
```

## Usage ▶️
1. Open a terminal in the project folder.
2. Start Jupyter:

```bash
jupyter notebook
```

3. Open `Single_Neuron_Model.ipynb` and run cells top-to-bottom.

## Notebook overview
- Data loading & EDA
- Preprocessing (scaling)
- Single neuron model implementation and training
- Evaluation and visualization
- Notes on reproducibility and hyperparameters

## Reproducibility
Set a fixed random seed in the notebook to help reproducibility; results may still vary slightly depending on library versions and platform. For exact reproducibility, use the pinned versions in `requirements.txt` and record the environment (`pip freeze > installed.txt`).

## Data sources
- `winequality-*.csv` — UCI Wine Quality dataset
- `advertising.csv` — common ML tutorial dataset (included)

## Contributing
Feel free to open issues or pull requests with suggestions, fixes, or improvements.

---

Maintainer: Project owner

Enjoy exploring single-neuron learning! 💡

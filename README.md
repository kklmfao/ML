# Machine Learning Projects

A collection of machine learning projects and experiments.

## Projects

- **iris-flower**: Iris flower classification using various ML algorithms

## Setup

This project uses [uv](https://github.com/astral-sh/uv) for dependency management.

### Prerequisites

- Python 3.11+
- uv package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd ML
```

2. Install dependencies:
```bash
uv sync
```

3. Activate the virtual environment:
```bash
source .venv/bin/activate  # On macOS/Linux
# or
.venv\Scripts\activate  # On Windows
```

4. Launch Jupyter:
```bash
jupyter notebook
```

## Project Structure

```
ML/
├── iris-flower/          # Individual ML projects
│   └── notebook.ipynb
├── own-linear-regression/
│   └── notebook.ipynb
├── pyproject.toml        # Project dependencies
├── hello.py              # Not Used
└── README.md
```

## Dependencies

Key libraries included:
- scikit-learn
- pandas, numpy
- matplotlib, seaborn, plotly
- PyTorch
- XGBoost
- Optuna
- Jupyter

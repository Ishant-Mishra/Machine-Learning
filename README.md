# Machine Learning Practice

A learning repository containing notebooks, assignments, and experiments as I study Python data tools and foundational machine-learning concepts.

## Topics and Materials

- **Linear regression:** simple and multiple linear regression, mathematical intuition, and gradient descent.
- **Model evaluation:** notes and experiments around the R² score.
- **Dimensionality reduction:** a PCA notebook.
- **Python data ecosystem:** practice folders for NumPy, Matplotlib, Seaborn, and TensorFlow.
- **Assignments and experiments:** coursework and exploratory notebooks.

## Repository Guide

- `ML Algorithms/` — notebooks covering linear regression and gradient descent, plus a small placement-data example.
- `Assignment/` — assignment work.
- `Machine Learning/` — additional machine-learning practice.
- `numpy/`, `matplotlib/`, `Seaborn/`, `tensorflow/` — library-focused exercises.
- `PCA.ipynb` — principal component analysis practice.
- `new.ipynb` — additional exploratory notebook.

## Running the Notebooks

1. Install Python 3.10 or newer.
2. Create and activate a virtual environment.
3. Install the libraries required by the notebook you want to run.
4. Launch Jupyter and open the notebook.

```bash
python -m venv .venv
# Windows PowerShell: .\.venv\Scripts\Activate.ps1
# macOS / Linux: source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install jupyter numpy pandas matplotlib seaborn scikit-learn
python -m jupyter lab
```

Some notebooks may use additional packages such as TensorFlow. Install those only when needed by the selected notebook.

## Learning Notes

This is a practice repository, so examples may be at different stages of completion. Before relying on an experiment, run its cells from top to bottom and verify the output, assumptions, and dataset paths.

## License

No license is specified yet. Please do not assume reuse or redistribution rights until a license is added.

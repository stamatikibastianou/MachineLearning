# Hyperspectral Image Analysis: Spectral Unmixing & Classification

This project explores hyperspectral data through **spectral unmixing** and **pixel classification**, and looks at how the two approaches connect.

## What's Inside

1. **Part 1 — Spectral Unmixing**
   * Runs **5 unmixing methods** and compares their **Reconstruction Errors**.
   * Plots **Abundance Maps** for all **9 endmembers** across every method and analyzes the results.

2. **Part 2 — Classification**
   * Includes a custom **Minimum Euclidean Distance Classifier** (`MinimumEuclideanDistanceClassifier`) alongside standard classifiers.
   * Evaluates models using **10-fold cross-validation** and a **test set**, and compares **4 confusion matrices**.

3. **Part 3 — Combining Unmixing & Classification**
   * Discusses how unmixing abundances relate to classification results and where sub-pixel mixing affects predictions.

## Project Files

```text
.
├── notebook.ipynb          # Main Jupyter Notebook with code, plots, and written analysis
├── report.pdf              # Exported PDF version of the report
└── README.md               # This file
```


## Setup & How to Run

Install the main Python packages you need:

```bash
pip install numpy scipy scikit-learn matplotlib pandas jupyter
```

Then open the notebook:

```bash
jupyter notebook
```

Run the cells in order from top to bottom.


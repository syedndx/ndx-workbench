# NDX Workbench

Hands-on practice notebooks for the [NDX Garden](https://projectndx.com) curriculum — run the code, not just read about it.

Each notebook mirrors a specific Garden module: real datasets, exercises with worked solutions, and at least one thing you can't get from reading alone — implementing an algorithm by hand, watching a model's coefficients shrink under regularization, or reproducing a classic mistake so you actually feel why it matters.

These notebooks are supplementary. Nothing here is graded or tracked — work through them in any order, at any pace, or skip straight to the solutions if you just want to check your understanding.

## What's here

### `machine-learning/foundations/`

| Notebook | Module | What you'll do |
|---|---|---|
| [`module-01`](machine-learning/foundations/module-01/module-01.ipynb) | Introduction to Machine Learning | Fit a real classifier and a real clustering algorithm on the same data, then compare what each one finds with zero vs. full label information. |
| [`module-02`](machine-learning/foundations/module-02/module-02.ipynb) | The Machine Learning Workflow | Work through a deliberately messy dataset — missing values, unscaled columns, class imbalance — and reproduce the "fit on the whole dataset" leak firsthand. |

### `machine-learning/classical-supervised-learning/`

| Notebook | Module | What you'll do |
|---|---|---|
| [`module-03`](machine-learning/classical-supervised-learning/module-03/module-03.ipynb) | Regression and Core Optimization | Implement Gradient Descent by hand, compute VIF to catch multicollinearity, and watch Ridge/Lasso/Elastic Net shrink coefficients across a range of alpha. |

More notebooks are added as new Garden modules go live — Data Science and AI trunks will get their own top-level folders here as they launch.

## How to use these

Each notebook opens directly in Google Colab — no local setup, no environment to configure. Click a notebook's link on the [Workbench page](https://projectndx.com/workbench), or open one directly:

```
https://colab.research.google.com/github/syedndx/ndx-workbench/blob/main/<path-to-notebook>
```

Prefer to work locally instead? Clone the repo and open any `.ipynb` in Jupyter:

```
git clone github.com/syedndx/ndx-workbench
```

Every notebook only depends on standard libraries already available in Colab: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, and `statsmodels` where noted.

## Structure

Notebooks are organized by subject trunk, then by curriculum part:

```
<subject>/
  <part>/
    module-0X/
      module-0X.ipynb
```

Task cells are marked `# YOUR CODE HERE` — try each exercise yourself before checking the **Solutions** section at the bottom of each notebook.

## About

Part of [NDX](https://projectndx.com) — where Garden is the curriculum and Workbench is where you put it into practice.

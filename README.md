# Machine Learning Fundamentals — Image & Numeric Data

A collection of classic ML algorithms implemented across two tracks: unsupervised/supervised learning on **image data**, and regression on **numeric/tabular data**.

## Project structure

```
.
├── Image-Classification/
│   └── notebooks/
│       ├── Image Kmeans.ipynb              # K-Means clustering on image data
│       ├── Image Logistic Regression.ipynb # Logistic regression for image classification
│       ├── notebooks/                      # [what's inside this nested folder? flatten if redundant]
│       └── image_flower_data.txt           # dataset
├── numeric/
│   ├── Data/                               # [contents — CSV(s)? describe once visible]
│   ├── notebooks/
│   │   └── [KNN Regression, Linear Regression, preprocessing notebooks — exact filenames TBD]
│   └── Numerical-Regression                # [notebook or folder?]
└── README.md
```

> Note: I based this on the screenshot you shared — the nested `notebooks/notebooks/` folder and a couple of file names/extensions weren't fully legible. Worth flattening that nested folder before publishing; a `notebooks/` inside `notebooks/` looks like an accidental duplicate to a reviewer.

## What's in each notebook

| Notebook | Task | Data |
|---|---|---|
| `Image Kmeans.ipynb` | Unsupervised clustering (K-Means) on image data | `image_flower_data.txt` |
| `Image Logistic Regression.ipynb` | Image classification via logistic regression | `image_flower_data.txt` |
| KNN Regression | K-Nearest Neighbors regression on numeric data | `numeric/Data/` |
| Linear Regression | Linear regression on numeric data | `numeric/Data/` |
| Preprocessing | Data cleaning / feature scaling / train-test split pipeline shared across the numeric notebooks | `numeric/Data/` |

*(Once you share the actual notebooks, I'll replace this table with real details: what the flower dataset actually contains, how many clusters/classes, what features the numeric regression uses, and what metrics/results each one reports.)*

## Tech stack

- Python, Jupyter Notebook
- [scikit-learn / NumPy / pandas / matplotlib — confirm which libraries are actually imported]

## Getting started

```bash
git clone https://github.com/<your-username>/ml-fundamentals-image-numeric.git
cd ml-fundamentals-image-numeric
pip install -r requirements.txt
jupyter notebook
```

## Results

*(Placeholder — add once notebooks are available: clustering visualization for K-Means, accuracy/confusion matrix for logistic regression, RMSE/R² for KNN and linear regression.)*

## License

MIT

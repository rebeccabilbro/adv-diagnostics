# Diagnostics for More Informed Machine Learning

Welcome!
This is the course repository for XBUS-511 - Diagnostics for More Informed Machine Learning, offered by Georgetown University's School of Continuing Studies.

## Quickstart
This course assumes that you have Python >= 3.5 installed as well as a package manager (`pip` or `conda`).

Clone the repository and go into the top-level directory:

```bash
$ git clone git@github.com:rebeccabilbro/advanced-diagnostics.git
$ cd advanced-diagnostics
```

Requirements can be installed with:

```bash
$ pip install -r requirements/requirements.txt
```

## Course Description

Even with a modest dataset, the hunt for the most effective machine learning model is hard. Finding the optimal combination of features, algorithm, and hyperparameters that produce the best model frequently requires significant experimentation and iteration. This leads many machine learning practitioners to either stay inside their algorithmic comfort zones, to trail off on random walks, or to resort to automated processes like gridsearch. But whatever the path we take, many of us are left in doubt about whether our final solution really is the optimal one. And as our datasets grow in size and dimension, so too does this ambiguity.

Open source Python libraries such as Seaborn, Pandas and Yellowbrick can help make machine learning more informed with diagnostic tools like histograms, correlation matrices, parallel coordinates, manifold embeddings, validation and learning curves, residuals plots, and classification heatmaps. These tools enable us to tune our models with visceral cues that allow us to be more strategic in our choices.
In this course we will explore principled strategies for steering model search (e.g. visualizing feature transformations, algorithmic behavior, cross-validation methods, and model performance) to help identify better models, faster, and at lower cost to our organizations.


## Course Objectives

- Question, investigate, diagnose, and mitigate the influence of bias in the modeling process.
- Challenge and extend traditional ways of thinking about data visualization in the context of the machine learning workflow.
- Evaluate trade-offs in models (e.g. precision vs. recall, overfit vs. underfit, accuracy vs. training time).
- Compare and contrast hypothesis driven workflows and experimental results using visual and statistical techniques.
- Aggregate large amounts of complex data using visual and statistical methods.
- Explore visual techniques for feature exploration, selection, projection, and dimensionality reduction.
- Visually select the best model composed of feature, algorithm, and hyperparameters.


## Repository Structure

```bash
├── LICENSE
├── README.md
├── fixtures
├── notebooks
├── requirements
|   └── requirements.txt
└── results
```
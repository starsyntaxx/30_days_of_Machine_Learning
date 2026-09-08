🧠 30 Days of Machine Learning Models

«From "I can use it" to "I understand why it works."»

A 30-day deep dive into Machine Learning models, their mathematical foundations, assumptions, implementation, hyperparameters, tuning, diagnostics, and interpretability.

This isn't a challenge to simply learn how to call ".fit()".

The goal is to understand what happens underneath the model, why it works, when it works, when it fails, and how to make informed decisions when working with real-world data.

Each day, I'll learn, implement, experiment, document, and teach what I've learned through a corresponding Medium article.

---

🎯 The Goal

By the end of these 30 days, I want to be able to take an unfamiliar dataset and confidently reason through:

Understand the Data
       ↓
Define the Problem
       ↓
Choose an Appropriate Model
       ↓
Understand the Mathematics
       ↓
Implement the Model
       ↓
Tune the Hyperparameters
       ↓
Diagnose Model Behaviour
       ↓
Interpret the Results
       ↓
Experiment & Improve
       ↓
Explain the Model

The goal isn't to memorize algorithms.

It's to develop a mental model for Machine Learning.

---

🗺️ What I'll Explore

Machine Learning models will be explored through their major families.

1. Linear Models

- Linear Regression
- Logistic Regression
- Ridge Regression
- Lasso Regression
- Elastic Net
- Linear Discriminant Analysis

2. Distance-Based Models

- K-Nearest Neighbors
- K-Means
- K-Medoids

3. Tree-Based Models

- Decision Trees
- Random Forest
- Extra Trees
- Gradient Boosting
- XGBoost
- LightGBM
- CatBoost

4. Probabilistic Models

- Naive Bayes
- Gaussian Mixture Models
- Bayesian Networks
- Gaussian Processes

5. Kernel-Based Models

- Support Vector Machines
- Support Vector Regression
- Kernel methods

6. Neural Models

- Perceptron
- Multilayer Perceptron
- CNNs
- RNNs
- LSTMs
- GRUs
- Autoencoders
- Transformers

7. Unsupervised Learning

- Clustering
- Dimensionality Reduction
- Anomaly Detection

8. Model Selection & Optimization

- Cross-validation
- Grid Search
- Random Search
- Bayesian Optimization
- Optuna
- Bias-Variance Analysis

«Note: The 30-day challenge is not intended to cover every Machine Learning algorithm. The focus is on developing deep understanding of important model families and the concepts that generalize across them.»

---

🔬 The Model Learning Framework

Every major model will be studied using the same framework.

01 — Problem

What kind of problem does the model solve?

- Classification?
- Regression?
- Clustering?
- Dimensionality reduction?
- Anomaly detection?

---

02 — Data Assumptions

What does the model assume about the data?

I'll investigate assumptions around:

- Feature distributions
- Independence
- Linearity
- Scale
- Noise
- Class separability
- Feature relationships

Understanding assumptions is essential for understanding when a model should or shouldn't be used.

---

03 — Intuition

Before equations and code:

«What is the model actually doing?»

The objective is to explain the model in simple language and develop an intuitive understanding of its behaviour.

---

04 — Mathematics

Then we'll go underneath the hood.

Depending on the model, this may involve:

- Linear algebra
- Probability
- Statistics
- Calculus
- Geometry
- Optimization
- Loss functions
- Likelihood
- Regularization

The goal isn't just to memorize equations.

It's to understand why the equations look the way they do.

---

05 — From Scratch

Where practical, I'll implement the core algorithm using NumPy.

Not to replace production libraries, but to understand what happens internally.

Mathematics
     ↓
Algorithm
     ↓
Implementation

---

06 — Scikit-Learn Implementation

After understanding the underlying mechanics, I'll implement the model using the appropriate ML library.

This creates a connection between:

«Theory → Implementation → Practice»

---

07 — Hyperparameters

I'll investigate the important hyperparameters of each model.

Not just:

«""max_depth" controls the depth of a tree."»

But:

«What happens to model complexity, bias, variance and generalization when "max_depth" changes?»

For each important hyperparameter, I'll explore:

- What it controls
- Why it exists
- What happens when it increases
- What happens when it decreases
- Its effect on model behaviour

---

08 — Hyperparameter Tuning

I'll experiment with:

- Grid Search
- Random Search
- Bayesian Optimization
- Optuna

The goal isn't simply to find the highest score.

I'll also investigate why certain hyperparameter configurations perform better.

---

09 — Diagnostics

When a model performs poorly, I'll ask:

«Why?»

Possible causes include:

- Underfitting
- Overfitting
- High bias
- High variance
- Data leakage
- Poor features
- Class imbalance
- Incorrect preprocessing
- Inappropriate evaluation metrics
- Model mismatch

---

10 — Interpretability

Where appropriate, I'll explore:

- Model coefficients
- Feature importance
- Permutation importance
- Partial dependence
- SHAP

Because prediction is only part of the problem.

Sometimes we also need to understand:

«Why did the model make this prediction?»

---

11 — Experiment

I'll deliberately change variables and observe how the model responds.

Examples:

Change max_depth
        ↓
Observe training performance
        ↓
Observe validation performance
        ↓
Analyze the difference
        ↓
Understand the behaviour

Instead of simply reading that a hyperparameter affects a model, I'll make the model demonstrate it.

---

12 — Teach

Every major topic will be documented as a Medium article.

The objective is simple:

«If I can't explain it clearly, I probably don't understand it deeply enough.»

---

📅 30-Day Roadmap

Day| Topic| Status| Medium
01| Introduction to AI, ML & Data Science| 🔄| —
02| Types of Data & ML Problems| ⬜| —
03| ML Model Taxonomy| ⬜| —
04| Linear Regression| ⬜| —
05| Logistic Regression| ⬜| —
06| Regularization: Ridge & Lasso| ⬜| —
07| K-Nearest Neighbors| ⬜| —
08| Naive Bayes| ⬜| —
09| Decision Trees| ⬜| —
10| Random Forest| ⬜| —
11| Gradient Boosting| ⬜| —
12| XGBoost| ⬜| —
13| LightGBM / CatBoost| ⬜| —
14| Support Vector Machines| ⬜| —
15| K-Means| ⬜| —
16| DBSCAN| ⬜| —
17| Gaussian Mixture Models| ⬜| —
18| PCA| ⬜| —
19| Anomaly Detection| ⬜| —
20| Model Selection| ⬜| —
21| Hyperparameter Tuning| ⬜| —
22| Bias, Variance & Overfitting| ⬜| —
23| Perceptron| ⬜| —
24| Neural Networks| ⬜| —
25| Backpropagation| ⬜| —
26| Optimization & Neural Network Training| ⬜| —
27| CNNs| ⬜| —
28| RNNs, LSTMs & GRUs| ⬜| —
29| Transformers| ⬜| —
30| Final Model Selection & End-to-End Project| ⬜| —

«The roadmap may evolve as the challenge progresses. The goal is depth of understanding, not rigidly completing a checklist.»

---

📂 Repository Structure

30-days-of-ml-models/
│
├── README.md
├── requirements.txt
├── LICENSE
│
├── 00-introduction/
│
├── 01-linear-models/
│   ├── linear-regression/
│   ├── logistic-regression/
│   └── regularization/
│
├── 02-distance-based/
│   ├── knn/
│   └── kmeans/
│
├── 03-tree-based/
│   ├── decision-trees/
│   ├── random-forest/
│   ├── gradient-boosting/
│   ├── xgboost/
│   ├── lightgbm/
│   └── catboost/
│
├── 04-probabilistic/
│
├── 05-kernel-based/
│
├── 06-neural-models/
│   ├── perceptron/
│   ├── neural-networks/
│   ├── cnn/
│   ├── rnn/
│   ├── lstm/
│   └── transformers/
│
├── 07-unsupervised-learning/
│
├── 08-model-selection/
│   ├── cross-validation/
│   ├── hyperparameter-tuning/
│   └── optuna/
│
├── experiments/
│   ├── bias-vs-variance/
│   ├── overfitting/
│   ├── regularization/
│   └── hyperparameter-effects/
│
├── notes/
│   ├── mathematics/
│   ├── statistics/
│   ├── linear-algebra/
│   └── optimization/
│
└── progress/
    └── roadmap.md

---

🧪 Experiments

An important part of this repository is experimentation.

Instead of only recording what a model does, I'll investigate how its behaviour changes when its conditions change.

Examples:

- How does increasing tree depth affect overfitting?
- How does "k" affect KNN?
- What does regularization actually do?
- How does learning rate affect optimization?
- What happens when features aren't scaled?
- How does dataset size affect model performance?
- How do different models behave on the same dataset?

The objective is to move from:

"I read that..."

to:

"I tested it, observed it, and now I understand why."

---

📚 Mathematical Foundations

Throughout the challenge, I'll build a parallel collection of mathematical notes covering concepts such as:

Linear Algebra

- Vectors
- Matrices
- Matrix multiplication
- Dot products
- Eigenvalues & eigenvectors
- Vector spaces

Statistics

- Mean
- Variance
- Covariance
- Probability distributions
- Conditional probability
- Bayes' theorem
- Likelihood

Calculus

- Derivatives
- Partial derivatives
- Gradients
- Chain rule

Optimization

- Gradient Descent
- Stochastic Gradient Descent
- Convexity
- Regularization
- Optimization objectives

These concepts will be connected back to the models where they are used.

---

🛠️ Tools & Technologies

The primary tools used throughout the challenge will include:

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- Optuna
- SHAP
- Jupyter Notebook

The focus, however, is not on the tools.

The tools are the means. Understanding the models is the goal.

---

✍️ Medium Series

The learning process will be documented publicly through a corresponding Medium series.

Each article will focus on one concept or model and follow the learning framework above.

Medium Series: Coming soon

---

📈 Progress

Overall

Day 01 / 30
░░░░░░░░░░░░░░░░░░░░ 3%

Status

- ⬜ Not started
- 🔄 In progress
- ✅ Completed

---

🤝 Why I'm Doing This

Machine Learning has reached a point where using powerful models is easier than ever.

But abstraction can sometimes hide understanding.

Libraries make it possible to train sophisticated models with a few lines of code. That's incredibly useful—but I don't want the abstraction to become a substitute for understanding.

This challenge is my attempt to go one layer deeper.

I want to understand:

«What is the model doing?»

«Why does it work?»

«What assumptions does it make?»

«What mathematics makes it possible?»

«What happens when I change its parameters?»

«Why does it fail?»

«And when should I choose it over another model?»

---

🚀 The Challenge

30 days.

Multiple model families.

Mathematics.

Code.

Experiments.

Documentation.

One goal:

From "I can use the model" → "I understand the model."

---

⭐ If you find this learning journey useful, feel free to follow the repository and explore the experiments as they evolve. 

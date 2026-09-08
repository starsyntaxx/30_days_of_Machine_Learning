##30 Days of Machine Learning Models

«From "I can use it" to "I understand why it works."»

A 30-day deep dive into Machine Learning models — exploring their intuition, mathematics, assumptions, implementation, hyperparameters, tuning, diagnostics, and interpretability.

This is not just a challenge to use ML models.

It is a challenge to understand why they work, when they work, when they fail, and how to make better decisions when working with them.

---

#🎯 Goal

By the end of these 30 days, I want to be able to take an unfamiliar dataset and confidently go from:

Understand the Data
       ↓
Define the ML Problem
       ↓
Choose an Appropriate Model
       ↓
Understand the Mathematics
       ↓
Implement the Model
       ↓
Tune the Model
       ↓
Diagnose Its Behaviour
       ↓
Interpret the Results
       ↓
Experiment & Improve
       ↓
Explain It Clearly

The goal is not simply to know the syntax of "fit()" and "predict()".

The goal is to understand what happens under the hood.

---

# What I Will Explore

Throughout the challenge, I will study different Machine Learning model families, including:

- Linear Models
- Distance-Based Models
- Tree-Based Models
- Probabilistic Models
- Kernel-Based Models
- Neural Models
- Clustering Models
- Dimensionality Reduction
- Ensemble Methods
- Model Selection & Optimization

---

# Model Learning Framework

Every major model will be studied using the same framework.

1. Problem

What problem does this model solve?

- Classification?
- Regression?
- Clustering?
- Dimensionality reduction?
- Anomaly detection?

2. Data Assumptions

What does the model assume about the data?

Understanding assumptions helps determine when a model is appropriate — and when it isn't.

3. Intuition

Explain how the model works without mathematics first.

If I cannot explain the model simply, I probably don't understand it well enough.

4. Mathematics

Go beneath the abstraction.

Explore:

- Objective functions
- Loss functions
- Probability
- Geometry
- Optimization
- Gradients
- Regularization
- Statistical assumptions

5. From Scratch

Implement the core idea using Python/NumPy where practical.

The purpose isn't to recreate an entire production library.

It is to understand the mechanics.

6. Scikit-Learn / Framework Implementation

Implement the model using established libraries.

For example:

from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)

predictions = model.predict(X_test)

The goal is to understand what the abstraction is doing rather than blindly relying on it.

7. Hyperparameters

Identify the important hyperparameters and understand:

- What they control
- What happens when they increase
- What happens when they decrease
- How they affect bias and variance
- When they can cause overfitting or underfitting

8. Tuning

Experiment with different approaches:

- Grid Search
- Random Search
- Bayesian Optimization
- Optuna

9. Diagnostics

Investigate:

- Underfitting
- Overfitting
- Bias
- Variance
- Training vs validation performance
- Error patterns
- Model limitations

10. Interpretability

Understand what the model has learned.

Depending on the model:

- Coefficients
- Feature importance
- Decision boundaries
- SHAP
- Partial dependence
- Model-specific explanations

11. Experiment

Change one or two important factors and observe what happens.

For example:

«What happens when "max_depth" increases?»

«What happens when "k" changes in KNN?»

«What happens when regularization becomes stronger?»

The experiment is where theory meets behaviour.

12. Teach

Finally, explain the model in a Medium article.

If I can teach it clearly, I should have a much stronger understanding of it.

---

# 30-Day Roadmap

Day| Topic
01| Introduction to AI, ML & Data Science
02| Types of Data & ML Problems
03| ML Model Taxonomy
04| Linear Regression
05| Logistic Regression
06| Regularization: Ridge & Lasso
07| K-Nearest Neighbors
08| Naive Bayes
09| Decision Trees
10| Random Forest
11| Gradient Boosting
12| XGBoost
13| LightGBM / CatBoost
14| Support Vector Machines
15| K-Means
16| DBSCAN
17| Gaussian Mixture Models
18| Principal Component Analysis
19| Anomaly Detection
20| Model Selection
21| Hyperparameter Tuning
22| Bias, Variance & Overfitting
23| Perceptron
24| Neural Networks
25| Backpropagation
26| Optimization & Neural Network Training
27| Convolutional Neural Networks
28| RNNs, LSTMs & GRUs
29| Transformers
30| Final Model Selection & End-to-End Project

---

# Repository Structure

30-days-of-ml-models/
│
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
├── 00-introduction/
│   ├── 01-what-is-ai.md
│   ├── 02-ai-vs-ml-vs-ds.md
│   ├── 03-state-of-machine-learning.md
│   ├── 04-types-of-data.md
│   └── 05-model-taxonomy.md
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
│   └── naive-bayes/
│
├── 05-kernel-based/
│   └── svm/
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
│   ├── dbscan/
│   ├── gmm/
│   └── pca/
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

# Experiments

Understanding a model isn't complete without experimentation.

This repository will contain experiments exploring questions such as:

- How does increasing model complexity affect performance?
- What causes a model to overfit?
- How does regularization affect coefficients?
- How does the number of neighbours affect KNN?
- How does tree depth affect Decision Trees?
- How do ensemble models reduce variance?
- How do different hyperparameters change model behaviour?
- How does the amount of training data affect performance?

---

📐 Mathematical Foundations

Machine Learning models are built on mathematics.

This repository will therefore also contain notes covering:

Statistics

- Probability distributions
- Conditional probability
- Bayes' theorem
- Expectation
- Variance
- Covariance
- Correlation
- Maximum likelihood

Linear Algebra

- Vectors
- Matrices
- Matrix multiplication
- Eigenvalues & eigenvectors
- Dot products
- Projections
- Vector spaces

Calculus

- Derivatives
- Partial derivatives
- Gradients
- Chain rule
- Optimization

Optimization

- Gradient Descent
- Stochastic Gradient Descent
- Learning rates
- Convex vs non-convex optimization
- Local vs global minima

---

🛠️ Tools

The challenge will primarily use:

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- XGBoost
- LightGBM
- CatBoost
- Optuna
- TensorFlow / Keras
- Jupyter / Google Colab

---

#✍️ Medium Series

Each major learning milestone will be documented through a Medium article.

The articles will focus on explaining models from first principles rather than simply presenting code.

Medium Series: Coming soon.

---

#Progress

Day| Topic| Status
01| Introduction to AI, ML & Data Science| ⬜
02| Types of Data & ML Problems| ⬜
03| ML Model Taxonomy| ⬜
04| Linear Regression| ⬜
05| Logistic Regression| ⬜
06| Ridge & Lasso| ⬜
07| KNN| ⬜
08| Naive Bayes| ⬜
09| Decision Trees| ⬜
10| Random Forest| ⬜
...| ...| ⬜
30| Final Project| ⬜

---

🎯 Why I'm Doing This

It is easy to use Machine Learning libraries.

It is much harder to understand what is happening underneath them.

I want to move beyond:

«"I know how to use this model."»

towards:

«"I understand why this model works, what assumptions it makes, how its mathematics shapes its behaviour, how its hyperparameters affect it, why it fails, and when I should choose it."»

That is the goal of these 30 days.

---

# The Challenge

30 Days.

Multiple model families.

Mathematics.

Experiments.

Implementation.

Failures.

Documentation.

Teaching.

The ultimate goal:

«From "I can use it" to "I understand why it works."»

---

⭐ Follow the Journey

If you're also learning Machine Learning, feel free to explore the repository, follow the experiments, and learn along with me.

30 Days of Machine Learning Models — let's understand what is actually happening under the hood.
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

# Applied Machine Learning Mid-term

![Banner](images/banner.png)

## 🧑‍💼 Jason A. Ballard  

### Instructional Systems Special | Data Scientist | Data and AI Officer | Data Literacy Advocate | Educator in Professional Military Education

Welcome! I'm Jason A. Ballard, an experienced leader in data and AI integration, currently serving as the Data and AI Officer for the US Army Combined Arms Center at Fort Leavenworth, Kansas. My work bridges data science, AI strategy, and higher education, focusing on transforming decision-making through data literacy and innovation.

I invite you to explore my GitHub repository, [jbtallgrass](https://github.com/JBtallgrass?tab=repositories), where I share insights, tools, and resources focused on data literacy and advanced analytics in educational contexts. My projects emphasize practical solutions, open collaboration, and a commitment to enhancing data accessibility across teams.

### 🔑 Key Areas of Focus

- **Data Strategy & Governance**: Developing frameworks that promote data-driven decision-making and cross-departmental data sharing.  
- **AI & Analytics**: Leveraging data analytics and GenAI to unlock insights and drive transformational initiatives within the Army University.  
- **Data Literacy & Education**: Equipping leaders and students with data literacy skills critical for today's complex, data-rich environments.  

Please don't hesitate to connect, collaborate, or reach out to me if our interests align. **Let's make data-driven transformation a reality together.**  

📍 **LinkedIn**: [Jason A. Ballard](https://www.linkedin.com/in/jasonaballard)

### 📍 GitHub: [jbtallgrass](https://github.com/JBtallgrass)

---

## Applied Machine Learning Midterm Project: Classification Analysis

### Jason Ballard

#### Basehor, Kansas (CDT)

#### April 6, 2025

> Submission: GitHub Repository with Jupyter Notebook and Peer Review

---

## 📌 Project Overview

Organizations frequently need to classify data to support decision-making. 
For example, a healthcare provider may want to predict whether a patient has a specific condition based on lab results,
or a business may classify customer behavior to tailor marketing strategies.
Machine learning classification models help automate these decisions by recognizing patterns in historical data.

This project demonstrates the ability to apply classification modeling techniques to a real-world dataset. You will:

- Load and explore a dataset.
- Analyze feature distributions and consider feature selection.
- Train and evaluate a classification model.
- Compare different classification approaches.
- Document your work in a structured Jupyter Notebook.
- Conduct a peer review of a classmate’s project.

---

## 📌 Dataset Used

**Mushroom Classification Dataset** (Predict whether a mushroom is edible or poisonous based on characteristics)
[UCI Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/mushroom)

---

## Project Findings from the _Section Refelections_

---

## 🎯 Goals

---

### Data Sources

**Mushroom Classification Dataset** (Predict whether a mushroom is edible or poisonous based on characteristics)
[UCI Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/mushroom)

### ⚡ Technologies Used

### 🔑 Key Features

---

## 🛠️ Setup & Requirements

## 🔹 Project Components

## 🔄 Workflow

## 📊 Visualizations

---

## 📂 Project Structure

---

## 📊 Final Overview: The Full Data Flow

### 📊 Assignment Requirements

#### Professional layout

- Introduction

#### Section 1. Import and Inspect the Data

- 1.1 Load the dataset and display the first 10 rows.
- 1.2 Check for missing values and display summary statistics.

##### 📝 Reflection 1

- _What do you notice about the dataset?_

- _Are there any data issues?_

---

#### Section 2. Data Exploration and Preparation

- 2.1 Explore data patterns and distributions
  - Create histograms, boxplots, and count plots for categorical variables (as applicable).
  - Identify patterns, outliers, and anomalies in feature distributions.
  - Check for class imbalance in the target variable (as applicable).

- 2.2 Handle missing values and clean data
  - Impute or drop missing values (as applicable).
  - Remove or transform outliers (as applicable).
  - Convert categorical data to numerical format using encoding (as applicable).

- 2.3 Feature selection and engineering
  - Create new features (as applicable).
  - Transform or combine existing features to improve model performance (as applicable).
  - Scale or normalize data (as applicable).

##### 📝 Reflection 2

- _What patterns or anomalies do you see?_

- _Do any features stand out?_

- _What preprocessing steps were necessary to clean and improve the data? Did you create or modify any features to improve performance?_

---

#### Section 3. Feature Selection and Justification

- 3.1 Choose features and target
  - Select two or more input features (numerical for regression, numerical and/or categorical for classification)
  - Select a target variable (as applicable)
    - Regression: Continuous target variable (e.g., price, temperature).
    - Classification: Categorical target variable (e.g., gender, species).
    - Clustering: No target variable.
  - Justify your selection with reasoning.

- 3.2 Define X and y
  - Assign input features to X
  - Assign target variable to y (as applicable)

##### 📝 Reflection 3

- _Why did you choose these features?_

- _How might they impact predictions or accuracy?_

---

#### Section 4. Train a Model (Classification: Choose 1: Decision Tree, Random Forest, Logistic Regression)

- 4.1 Split the data into training and test sets using train_test_split (or StratifiedShuffleSplit if class imbalance is an issue).

- 4.2 Train model using Scikit-Learn model.fit() method.

- 4.3 Evalulate performance, for example:
  - Regression: R^2, MAE, RMSE (RMSE has been recently updated)
  - Classification: Accuracy, Precision, Recall, F1-score, Confusion Matrix
  - Clustering: Inertia, Silhouette Score

##### 📝 Reflection 4

- _How well did the model perform?_

- _Any surprises in the results?_

---

#### Section 5. Improve the Model or Try Alternatives (Implement a Second Option)

- 5.1 Train an alternative classifier (e.g., Decision Tree, Random Forest, Logistic Regression) OR adjust hyperparameters on the original model.

- 5.2 Compare the performance of all models across the same performance metrics.

##### 📝 Reflection 5

- _Which Model Performed Better?_

- _Why might one classifier be more effective in this specific case?_

---

#### Section 6. Final Thoughts & Insights

- 6.1 Summarize findings.

- 6.2 Discuss challenges faced.

- 6.3 If you had more time, what would you try next?

##### 📝 Reflection 6

- What did you learn from this project?

---

## ⚠️ Tasks to Complete the Assignment

1. Create a GitHub repository named **ml_classification_yourname**.  
1. Upload your dataset to a **data folder** in the repository.  
1. Develop a Jupyter Notebook (classification_yourname.ipynb) structured as outlined above.  
1. Complete and write reflections for each section as you work.
1. Write a README.md summarizing your project, dataset, and findings (see below).
1. Review a classmate’s project and provide feedback in peer_review.md (see below).

---

## README.md (Required)

Include a professional README.md that introduces your project. Include:
- a clickable link to your notebook file.
- a clickable link to your peer review Markdown file.
Instructions on setting up your virtual environment and running your notebook locally.

---

## Peer Review (Required)

Review one other GitHub repository and provide feedback on:

1. Clarity & Organization (Is the notebook structured and easy to follow?)
1. Feature Selection & Justification (Do the chosen features make sense given the objectives?)
1. Model Performance & Comparisons (Are the results and comparisons clearly explained?)
1. Reflection Quality (Are insights well thought out?)

Submission: Please submit a short peer review document in your repository, titled peer_review.md.  
The peer review must contain a **clickable Markdown link to the notebook (.ipynb) file reviewed** along with your personal, well-organized and presented 4-point review. 
Provide specific feedback - both positive and constructive. 
Suggest improvements where possible and explain why a different choice might be helpful as well.
Focus on actionable suggestions that the author could realistically implement.

---

## 4-point Repository Checklist

Verify your repository contains:

[ ] Jupyter Notebook with proper name, numbered sections and reflections.  
[ ] README.md (see above)
[ ] Dataset, stored in a data folder.  
[ ] Peer Review (peer_review.md).  

---

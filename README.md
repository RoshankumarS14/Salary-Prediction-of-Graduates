# Student Salary Prediction Project 🎓💰

Welcome to the Student Salary Prediction project! This repository contains all the code and resources related to predicting student salaries based on various factors. We've done extensive data analysis and built predictive models to help you understand the outcomes.

## Project Overview 📚📊

In this project, we aimed to predict student salaries using various data analysis and machine learning techniques. We have covered several important aspects of the project:

## Exploratory Data Analysis 📈🔍

We started by exploring the dataset, visualizing key statistics, and understanding the relationships between different variables. Our EDA includes count plots, histograms, box plots, heat maps, and pairwise scatter plots.

## Data Preprocessing 🧹📝

Data preprocessing is crucial for modeling success. We applied transformations using the Yeo-Johnson method, encoded categorical features using Target Encoding, and handled missing values. 

## Model Building 🧱🤖

We built predictive models using various regression algorithms, including Linear Regression, Lasso, Ridge, Stochastic Gradient Descent, and ElasticNet. The results showed that Ridge outperformed the other models.

## Model Selection 🏆📊

To select the best model, we compared their accuracy and performance metrics, and Ridge emerged as the top performer.

## Hyperparameter Tuning ⚙️🔧

We fine-tuned the hyperparameters of our Ridge model using GridSearchCV to further improve its efficiency.

## Feature Selection 🧐🔍

Feature selection is essential for model interpretability and performance. We employed Recursive Feature Elimination (RFE) and Sequential Feature Selection (SFS) to identify the most relevant features.

## Feature Engineering 🛠️🔮

We experimented with feature engineering by generating polynomial features of degree 2. However, this didn't yield improved model performance.

## Results 📊📈

The final Ridge model, after hyperparameter tuning and feature selection, achieved the best performance in predicting student salaries. We present detailed results and insights in our notebooks.

## Usage 🚀👩‍💻

You can use this project to learn about:

- Data analysis and preprocessing techniques
- Building and evaluating regression models
- Hyperparameter tuning and feature selection
- Best practices for README files and GitHub repositories

Feel free to fork and clone the repository to explore the code and try it on your own dataset!

## Contributing 🤝🙌

We welcome contributions from the open-source community! If you have ideas for improvements or would like to report issues, please create a pull request or open an issue.

---

We hope you find this project informative and useful. If you have any questions or feedback, don't hesitate to reach out. Happy coding! 🚀👩‍💻

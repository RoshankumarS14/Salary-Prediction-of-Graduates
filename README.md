# Student Salary Prediction Project 🎓💰

Welcome to the Student Salary Prediction project! This repository contains all the code and resources related to predicting student salaries based on various factors. We've done extensive data analysis and built predictive models to help you understand the outcomes.

## Project Overview 📚📊

In this project, the aim was to predict student salaries using various data analysis and machine learning techniques. Several important aspects of the project were covered:

- ### Exploratory Data Analysis 📈🔍

The dataset was explored, key statistics were visualized, and relationships between different variables were understood. EDA included count plots, histograms, box plots, heat maps, and pairwise scatter plots.

- ### Data Preprocessing 🧹📝

Data preprocessing, crucial for modeling success, involved the application of transformations using the Yeo-Johnson method, encoding of categorical features using Target Encoding, and handling of missing values.

### Model Building 🧱🤖

Predictive models were built using various regression algorithms, including Linear Regression, Lasso, Ridge, Stochastic Gradient Descent, and ElasticNet. The results indicated that Ridge outperformed the other models.

### Model Selection 🏆📊

The best model was selected by comparing accuracy and performance metrics, with Ridge emerging as the top performer.

### Hyperparameter Tuning ⚙️🔧

The hyperparameters of the Ridge model were fine-tuned using GridSearchCV to further enhance its efficiency.

### Feature Selection 🧐🔍

Feature selection, essential for model interpretability and performance, involved the use of Recursive Feature Elimination (RFE) and Sequential Feature Selection (SFS) to identify the most relevant features.

### Feature Engineering 🛠️🔮

Feature engineering experiments included generating polynomial features of degree 2. However, improved model performance was not observed.

### Results 📊📈

The final Ridge model, after hyperparameter tuning and feature selection, achieved the best performance in predicting student salaries. Detailed results and insights are presented in the project's notebooks.

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

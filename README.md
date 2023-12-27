# Census Data Classification Project

## Overview

Welcome to the Census Data Classification project! In this endeavor, we embarked on a journey to classify the income levels of approximately 40,000 individuals based on their workclass, age, sex, education, country, and occupation. Leveraging powerful machine learning techniques, specifically Decision Trees and Random Forest algorithms, we aimed to unravel patterns and insights within the data.

## Project Workflow

1. **Data Import and Cleaning:**
   - Imported the census dataset and diligently cleaned it by removing null values, ensuring data integrity and reliability.

2. **Data Visualization:**
   - Employed count plots for insightful visualizations, providing a quick glance into the distribution of key variables.

3. **Data Splitting:**
   - Strategically split the dataset into training (80%) and test (20%) sets, laying the foundation for robust model training and evaluation.

4. **Dummy Variable Creation:**
   - Recognizing categorical variables, created dummy variables to enable effective modeling.

5. **Model Training:**
   - Trained both Decision Tree and Random Forest models on the dataset, exploring the nuances of each algorithm.

6. **Model Evaluation:**
   - Rigorously evaluated the models on the test set, measuring their performance and effectiveness in predicting income levels.

## Results and Insights

- **Decision Tree vs. Random Forest:**
  - A marginal 1% increase in accuracy was observed with the Random Forest model over the Decision Tree. However, this difference was deemed insignificant.

- **Overall Accuracy:**
  - Achieved an impressive 85% accuracy with the Decision Tree model after pruning, establishing a robust predictive capability.

- **Pruning Success:**
  - Pruning techniques proved effective in both models, mitigating the risk of overfitting and enhancing generalization.

- **Model Selection:**
  - Considering robustness and accuracy, the Decision Tree with pruning emerged as the best-fit model for this dataset.

## Conclusion

This project not only provided valuable insights into the factors influencing income levels but also showcased the effectiveness of Decision Trees and Random Forests in classification tasks. The meticulous pruning process played a pivotal role in achieving optimal model performance. The codebase and findings presented here aim to serve as a valuable resource for those interested in exploring and understanding census data classification.

Feel free to explore the code, experiment with different parameters, and contribute to further enhancements! Happy coding! 🚀🌐

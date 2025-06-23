# Analysis of Stack Overflow Developer Salaries 2023

### Project Motivation

This project uses the 2023 Stack Overflow Developer Survey to find insights into developer compensation. The goal is to build a model to predict salaries and understand the key factors that influence them.

The analysis is structured around the following questions:
1.  What are the most important features that drive a developer's salary?
2.  What is the most surprising insight about developer compensation in this dataset?
3.  How accurately can we predict a developer's salary based on the survey data?

### File Descriptions

This repository contains the following files:
-   `MyProjectAnalysis.ipynb`: A Jupyter Notebook containing the full data analysis, from data cleaning and preparation to modeling and visualization.
-   `stackoverflow_survey_2023.csv`: The raw dataset used for this project, sourced from the official Stack Overflow Developer Survey.
-   `README.md`: This file, providing an overview of the project.

### Summary of Results

The analysis revealed several key findings:
-   **Professional experience (`YearsCodePro`) is by far the most significant predictor of salary.** This confirms that experience is the most valued asset in determining compensation.
-   Other important factors include the **Country** a developer works in and their **Education Level (`EdLevel`)**.
-   The machine learning model was able to explain a significant portion of the variance in salaries, demonstrating a strong relationship between the chosen features and compensation. A surprising insight was that fully remote developers reported higher median salaries than their in-office or hybrid counterparts.

### Blog Post

A summary of these findings has been published in a non-technical blog post on Medium. You can read the full story here:

**[PASTE YOUR BLOG POST LINK HERE]**

### Libraries Used

This project uses the following main Python libraries:
-   pandas
-   numpy
-   matplotlib
-   seaborn
-   scikit-learn

### Acknowledgements

This analysis would not be possible without the data provided by the Stack Overflow community through their annual survey.

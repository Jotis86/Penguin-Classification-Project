# 🐧 Penguin Classification Project 🐧

## Objective

The objective of this project is to build a classification model to predict the species of penguins using the penguin dataset available in the seaborn library. The project involves data cleaning, visualization, and applying a Random Forest classifier to achieve high accuracy in predictions.

## Functionality

This project performs the following steps:
1. 📥 **Import Data**: Load the penguin dataset from seaborn.
2. 📊 **Descriptive Statistics**: Generate statistical summaries to understand the data.
3. 🧹 **Data Cleaning**: Fill missing values with the mean for numerical columns and the mode for categorical columns.
4. 📈 **Data Visualization**: Use seaborn and matplotlib to create visualizations that explore relationships between features.
5. 🌲 **Model Training**: Apply a Random Forest classifier to predict the species of penguins.
6. 📉 **Evaluation**: Assess the model's performance and present the results.

## Tools Used

- **Python**: Programming language used for data analysis and model building.
- **pandas**: Library for data manipulation and analysis.
- **seaborn**: Library for data visualization.
- **matplotlib**: Library for creating static, animated, and interactive visualizations.
- **scikit-learn**: Library for machine learning, used to implement the Random Forest classifier.
- **Jupyter Notebooks**: An interactive computing environment that allows you to create and share documents containing live code, equations, visualizations, and narrative text.

## Development Process

1. **Data Import**: The penguin dataset is imported from the seaborn library.
2. **Descriptive Statistics**: Descriptive statistics are generated to understand the distribution and central tendencies of the features.
3. **Data Cleaning**: Missing values are handled by filling them with the mean for numerical columns and the mode for categorical columns.
4. **Data Visualization**: Various visualizations are created using seaborn and matplotlib to explore the data. This includes:
   - **Scatter Plot**: This plot shows the relationship between bill length and bill depth, with different colors and markers representing species and sex. It helps in identifying how these features vary across different species and sexes.
   - **Bar Plot**: This plot illustrates the body mass of penguins across different islands and sexes. It provides insights into how body mass distribution varies by location and gender.
   - **Box Plot**: This plot displays the distribution of flipper length across different species and sexes. It highlights the spread and outliers within each group, helping to understand the variability in flipper length.
   - **Violin Plot**: This plot combines aspects of box plots and density plots to show the distribution of bill length across species and sexes. It provides a detailed view of the data distribution and helps in identifying differences between groups.
   - **Histogram**: This plot shows the distribution of body mass among penguins. The inclusion of a kernel density estimate (KDE) line helps in understanding the overall distribution and central tendency of body mass.
   - **Relational Plot**: This plot shows the relationship between bill length and flipper length, with different colors and markers representing species and sex. It helps in identifying patterns and correlations between these features.
   - **Pair Plot**: This plot provides a comprehensive view of the relationships between all features, segmented by species. It helps in identifying patterns, correlations, and potential outliers in the dataset.

5. **Model Training**: A Random Forest classifier is applied to predict the species of penguins. The process involves:
   - Splitting the data into training and testing sets.
   - Training the model on the training data.
   - Evaluating the model on the test data.
6. **Results**: The model's performance is evaluated using metrics such as accuracy score and a confusion matrix.

## Results

The Random Forest classifier achieved excellent results in predicting the species of penguins. The model's accuracy was high, and the confusion matrix showed that the predictions were mostly correct. Below is a sample confusion matrix:


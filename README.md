# Real-Estate-Sales-Prediction

## Description:
Welcome to the Real Estate Sales Prediction project! In this repository, we delve into the fascinating world of machine learning to predict real estate sales outcomes with a focus on residential properties in the town of Bristol. Our project harnesses the power of Support Vector Machine (SVM) models, a robust machine learning technique, to unlock valuable insights and make informed predictions.

### Programming Language

- **Python**: The entire project is implemented in Python, a versatile and widely-used programming language for data analysis, machine learning, and scientific computing.

**Project Overview:**

Machine Learning:
Machine learning (ML) is the process of building algorithms that can "learn" from data. ML takes a dataset and endeavors to construct a model that can accurately predict future data or fill in missing information. In our case, we aim to predict real estate sales in Bristol based on historical data.

**Project Objectives:**
* Train a Model: We use the Scikit-learn library to generate and train an SVM model with an 80/20 training/validation split.
* Validation: Test the model's performance against a validation dataset to ensure its accuracy and reliability.
* Future Predictions: Utilize the trained SVM model to make predictions about future real estate sales.

**Libraries Used:**

This project involves the following key libraries:

- **Pandas**: Used for data manipulation and analysis. It's primarily used to read the CSV file, create dataframes, and perform operations on the data.
- **NumPy**: Used for numerical computations. It is utilized to handle arrays and perform various mathematical operations on the data.
- **Matplotlib.pyplot**: Used for creating data visualizations and plots. In this code, it's used to generate scatter plots and other graphs to visualize the data and model performance.
- **Seaborn**: A data visualization library built on top of Matplotlib. It's used to enhance the appearance of the plots, such as adding colors and labels to the scatter plot.
- **Scikit-learn (sklearn)**: A machine learning library that provides tools for data mining and data analysis.
  - **sklearn.preprocessing**: Used for data preprocessing tasks, such as label encoding.
  - **sklearn.model_selection**: Used for splitting the data into training and testing sets.
  - **sklearn.svm**: Used to implement Support Vector Machine (SVM) models for classification.
  - **sklearn.metrics**: Used for evaluating the model's performance, including accuracy calculation and confusion matrix creation.

## Data:
We source our data from a real estate sales dataset spanning the years 2001 to 2020. Through statistics and visualizations, we offer a comprehensive description of the dataset to gain insights into the underlying trends and patterns.

## Project Workflow:
1. **Data Preprocessing**: We clean the dataset by removing unnecessary columns, selecting specific residential types (Single Family and Condo), eliminating outliers, and handling missing values.
2. **Data Exploration**: We provide descriptive statistics and visualize the data to gain a better understanding of its characteristics.
3. **Model Training**: We employ the Scikit-learn library to train an SVM model using relevant features from the dataset.
4. **Model Evaluation**: We assess the model's accuracy and error rate by comparing its predictions to a validation dataset. We also display the confusion matrix for further evaluation.
5. **Predictions**: The trained model is employed to make predictions about real estate sales, enabling us to anticipate future trends in the Bristol housing market.
6. **Visualization**: We plot the model's predictions on a graph to visualize its performance, differentiating between Condo and Single Family properties.

**Result:**
The project offers a powerful tool for predicting real estate sales in Bristol, aiding in decision-making processes for both buyers and sellers. By leveraging SVM models and data analysis, we aim to contribute valuable insights into the dynamic real estate market.

Feel free to explore our code, dataset, and project documentation to gain a deeper understanding of the techniques and insights offered by this Real Estate Sales Prediction project.

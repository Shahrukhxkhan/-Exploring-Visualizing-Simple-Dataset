# -Exploring-Visualizing-Simple-Dataset
Task Objective
This project provides a Graphical User Interface (GUI) using Tkinter to interactively explore the famous Iris dataset. The tool allows users to quickly access data previews, statistical summaries, and various visualizations.

Dataset Used
Dataset Name: Iris Dataset

Source: Built into seaborn via sns.load_dataset("iris")

Features:

Sepal length

Sepal width

Petal length

Petal width

Species (Target variable)

Models Applied
This version does not include machine learning model training.
It focuses purely on data visualization and exploratory data analysis (EDA) using the following tools:

Pairplots (seaborn.pairplot)

Histograms (pandas.DataFrame.hist)

Boxplots (seaborn.boxplot)

Statistical summaries (DataFrame.describe())

Data schema (DataFrame.info())

Key Results and Findings
Clear separation between species in feature distributions is visible using pairplots.

Summary statistics provide quick insights into feature ranges and distributions.

GUI makes it easy for non-programmers to explore the dataset visually without writing code.

Can be extended with ML model integration for classification in future versions.


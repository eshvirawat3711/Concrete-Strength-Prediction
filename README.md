# Concrete-Strength-Prediction
Determining how strong will be the concrete mixture?

This case study creates a machine learning model which can predict the future strength of a concrete, based on its components and the time for which it is dried.

The flow of the case study is as below:

* Reading the data in python
* Defining the problem statement
* Identifying the Target variable
* Looking at the distribution of Target variable
* Basic Data exploration
* Rejecting useless columns
* Visual Exploratory Data Analysis for data distribution (Histogram and Barcharts)
* Feature Selection based on data distribution
* Outlier treatment
* Missing Values treatment
* Visual correlation analysis
* Statistical correlation analysis (Feature Selection)
* Converting data to numeric for ML
* Sampling and K-fold cross validation
* Trying multiple Regression algorithms
* Selecting the best Model
* Deploying the best model in production

The data has one file "ConcreteStrengthData.csv". This file contains 1005 concrete mixture combinations.

# Data Description
The business meaning of each column in the data is as below:

* **CementComponent:** How much cement is mixed
* **BlastFurnaceSlag:** How much Blast Furnace Slag is mixed
* **FlyAshComponent:** How much FlyAsh is mixed
* **WaterComponent:** How much water is mixed
* **SuperplasticizerComponent:** How much Super plasticizer is mixed
* **CoarseAggregateComponent:** How much Coarse Aggregate is mixed
* **FineAggregateComponent:** How much Coarse Aggregate is mixed
* **AgeInDays:** How many days it was left dry
* **Strength:** What was the final strength of concrete

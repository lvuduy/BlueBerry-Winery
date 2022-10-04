# BlueBerry-Winery Project

The Winery Exercises_Project will focus on Python and Statistics core concepts and its applications in Machine Learning. 
The tasks will be to prepare the data to be fitted to a Machine Learning algorithm, analyse the data taking into consideration the business questions and present the findings.

Some of the questions that need to pay attention to are:

Are there any problems with the data (null values, outliers, sufficient amount of data, etc.)?
Is the chemical composition of red and white wines comparable?
Does the chemical composition have any impact on the perceived quality of the wine?
What are your observations?

## Sprint 1
### Epic 1: Understanding the Data

There are 3 data files:

- the file named winequality-red.csv contains the dataset pertaining to 1599 records of red wine samples
- the file named winequality-white.csv contains the dataset pertaining to 4898 records of white wine samples
- the file named winequality.names consists of detailed information and the data dictionary pertaining to the datasets

The dataset contains physicochemical and sensory variables which require a bit more understanding.

Then use the Pandas read_csv function to read the data.

### Epic 2: Data Wrangling

Now let's start to explore the concepts of Data Wrangling on the provided dataset.

- print the first 10 and the last 10 records (use head() and tail() methods)
- chech the info and the shape (use info() and shape methods)
- observe if there are missing values (use isna(), isnull()
- check for Descriptive Statistics for both red and white wine datasets (use describe() method)
- Let's now group our qualities into 3 categories: low, medium and high quality wines.

### Epic 3: Exploratory Analysis

Using the red_wine and white_wine datasets,create a table to compare Descriptive Statistics between red and white wines.
This will help to undestand which features is worth investigating further.

Let's start plotting!
Use matplotlib and seaborn to explore relations between features.

## Sprint 2
### Epic 1: Univariate Analysis

This is perhaps one of the easiest yet a core foundational step in exploratory data analysis. Univariate analysis involves analyzing data such that at any instance of analysis you are only dealing with one variable or feature. No relationships or correlations are analyzed among multiple variables. The simplest way to easily visualize all the variables in the data is to build some histograms.

### Epic 2: Multivariate Analysis

Analyzing multiple feature variables and their relationships is what multivariate analysis is all about. Check if there are any interesting patterns and relationships among the physicochemical attributes of the wine samples, which might be helpful in the modeling process in the future.

One of the best ways to analyze features is to build a pairwise correlation plot depicting the correlation coefficient between each pair of features in the dataset.

### Epic 3: Statistical Significance

This is a branch of inferential statistics which draws inferences and propositions of a population using a data sample. The idea is to use statistical methods and models to draw statistical inferences from a given hypotheses. Each hypothesis consists of a null hypothesis and an alternative hypothesis.

Therefore, based on statistical test results, if the result is statistically significant based on pre-set significance levels (e.g., if obtained p-value is less than 5% significance level), one can reject the null hypothesis in favor of the alternative hypothesis.

Otherwise, if the results is not statistically significant, one can conclude that the null hypothesis was correct.

A great statistical model to prove or disprove the difference in mean among subsets of data is to use the one-way ANOVA test.

ANOVA stands for "analysis of variance", which is a nifty statistical model and can be used to analyze statistically significant differences among means or averages of various groups. This is basically achieved using a statistical test that helps one determine whether or not the means of several groups are equal.

## Sprint 3 
### Epic 1: Introduction to Machine Learning

Data is used to solve real-world problems via Machine Learning algorithms, techniques, and methodologies.

The following are some of the two broad areas of Machine Learning methods.

- Supervised learning
- Unsupervised learning

This project will cover Supervised Machine Learning methods with a classification task.

### Epic 2: Preparing the Data





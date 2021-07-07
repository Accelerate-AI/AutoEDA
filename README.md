# AutoEDA (Automated Exploratory Data Analysis)

## 1. Objective

To provide what is AutoEDA, what is the need, why it is used in Data Science projects and what are the libraries / packages that we can leverage from programming language such as Python to help facilitate data exploration and data analysis efforts in any project.

## 2. What is AutoEDA

Any Data Science project/program follows the CRISP-DM methodology. Data Understanding and Data Preparation phases involve EDA (Exploratory Data Analysis) and this is where we perform data exploration.

Why do we need EDA:
-	Extracting key variables and leaving behind not-so-important variables
-	Identifying various aspects such as outliers, missing values, or any human error in the dataset
-	Understanding the relationship between variables that are present or not present
-	Maximizing our insights of a dataset and minimizing potential error that may occur later in the process by ensuring understanding of data pattern better

How AutoEDA comes into play:
- We leverage some of the existing packages to **save time** in our analysis efforts
- There is need to analyze lots of messy and large datasets at initial phases in DS program for "Data Understanding". This is where AutoEDA helps **quick insight generation**
- **Feature wise comparision** of understanding data patterns and uncovering hidden insights which is a key step before we perform any "Data Preparation" / "Feature Engineering" step prior to Model development

## 3. AutoEDA Options with Features

Some of the key AutoEDA in Python are as follows:

Package / Library Name | Features                            | URL Reference         |
-----------------------|-------------------------------------|-----------------------|
Pandas Profiling       | Type inference, Quantile and Descriptive Stats, Most frequent values, Histogram, Correlations, Missing Values, Text analysis, Image analysis |https://pypi.org/project/pandas-profiling/ |
SweetViz               | Target Analysis, Visualize and Compare, Mixed-Type Associations, Type Inference, Summary Information | https://pypi.org/project/sweetviz/ |
AutoViz                | Scatter Plots, Pair-wise Scatter Plots, Histograms (KDE Plots), Violin Plot, Heatmap, Bar Plots  | https://github.com/AutoViML/AutoViz |
LUX                    | Correlation, Distribution, Occurrence, Geographical analysis, Current visualization and comparision with Enhance/Filter/Generalize approach | https://pypi.org/project/lux-api/ |
DataPrep               | Distributions, Correlations, Missing Values analysis, Profile Report with various stats, Time series data analysis, Faster than others like Pandas Profiling due to Dask based computing module | https://pypi.org/project/dataprep/ |
D Tale                 | Combination of Flask back-end and React front-end to view and analyze Pandas data structures, Integrates with IPython notebooks, supports interactive plots, 3d plots, heat maps, the correlation between features, builds custom columns etc. | https://pypi.org/project/dtale/ |

**P.S: This may not be an exhaustive list**

## 4. Notebooks / Kernels

Sample Notebooks are kept [here](https://github.com/Accelerate-AI/AutoEDA/tree/main/notebooks)


## 5. Interpretation Summary

- If we want to get quick insights on statistical inferences, missing values, duplicates, categorical/numerical/text features, correlations, interactions, top and bottom 10 rows, comparision between train and test datasets, then we can leverage some of these AutoEDA libraries and their capabilities.
- This helps in saving time significantly as we quickly generate some statistical inferences, insights as part of these reports / outcomes.
- If the dataset is large, we may use "DataPrep" which seems to be 10X faster than Pandas Profiling as it uses Dask based computing methods.
- We have used one sample dataset (Loan Eligible / Loan Prediction dataset) for the analysis to demonstrate features of various techniques. These can be used based on scenarios, data context, business need, feasibility etc. These are non-exhaustive list.


## 6. Suggestions / Questions if any ?

- Please reach out to ```AccelerateDataScience@gmail.com``` for any questions or suggestions or comments.
- Our attempt here is to capture use cases / real life applications in industry leveraging these.





<h1 align="center">EXPLORATION OF COVID19 VACCINATION DATA BASED ON ELECTION RESULTS</h1>

# Introduction:
The project aims to investigate the relation between vaccination rate and political preference based on U.S. with three discrete datasets. If a significant difference could be observed for this sample, machine learning models, such as a classifier model for countries/states/counties, could be created to infer the ruling ideology in a given area. The labels will be predicted by this model according to the vaccination rate (defined below) of the given area. This label may be used to raise awareness about the shortcomings of the ruling party in preventing the spread of the pandemic. These parties may then be called to encourage the people about vaccination.

# Problem Definition:
To investigate the problem, the following approach will be employed:

The US President 1976-2020 dataset will be explored to determine the state labels as either DEMOCRAT or REPUBLICAN. This process will be done by examining the last three elections (2012-2016-2020) and comparing win counts for the two groups.
The COVID-19 Vaccinations in the United States, County dataset will be explored to determine a Vaccination Rate for different states. This variable will be obtained by plotting the cumulative vaccination counts along days and using linear regression on said data points to determine a line fit. The slope of this line will be assigned as the Vaccination Rate for that state.
A two sample t-test will be conducted between the DEMOCRAT and REPUBLICAN samples to determine whether  μ1   ≥   μ2  holds with respect to  α1  = 0.05 and  α2  = 0.075.
If the results are significant enough, then we will proceed with developing different classifier models (which includes more features from the USA State Demographics Dataset) to make use of our results from the previous part.

# Utilized Datasets:
Three different datasets were used in the project:

COVID-19 Vaccinations in the United States, County
Vaccination dataset contains information about COVID-19 Vaccine administration and vaccine equity in a county level.
U.S. President 1976–2020
U.S. President 1976-2020 dataset contains state-level results for elections of the U.S. presidency from 1976 to 2020
USA State Demographics
Contains demographics data used for features
The links for datasets which was stated above:

https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-County/8xkx-amqh
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/42MVDX
https://corgis-edu.github.io/corgis/csv/state_demographics/

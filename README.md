# West_Nile_Virus_Prevelance_Analysis

<img alt="image" src="https://www.cdc.gov/dotw/westnilevirus/images/main_928px.jpg?_=32625">

West Nile Virus (WNV) is a viral illness largely spread by mosquitoes. The disease is transmitted to a person when an infected mosquito bites them.

<img alt="image" src="https://tooelehealth.org/wp-content/uploads/2016/02/WestNileVirus-large.png.webp">


The city of Chicago, Illinois has been keeping track of mosquito populations and WNV prevalence using a series of traps that they place around the city. They are then able to study the captured specimens and monitor the state of WNV spread in the city.

![image](https://user-images.githubusercontent.com/122119114/224687747-fd717e66-a7b1-46f6-9c3c-266c97c315bd.png)

Mosquito tracking dataset from 2008 to 2019 is given [here](https://docs.google.com/uc?export=download&id=159teLRYzRf8tbAUwlKZw_W68MGsn8gfR).

In part 1, I will perform EDA and data wrangling to get familiar with the dataset from the city of Chicago.

Refer to the table below for details about the data:

![image](https://user-images.githubusercontent.com/122119114/224685974-c00c62f6-7ebf-43e2-bde7-44d334ad7916.png)

The part aims to perform data wrangling and exploratory data analysis on a dataset containing information about mosquito traps and West Nile Virus (WNV) occurrences in the city of Chicago. The dataset includes various features such as the date, location of the trap, mosquito species, number of mosquitoes caught, and whether or not WNV was present in the sample.

Part 1 will be divided into four parts:

1. In Part 1 of the project, basic data wrangling is performed to clean the data and prepare it for analysis. The shape of the dataframe is determined, and the 'Date' column is converted to a datetime format. Two numeric and two categorical columns are selected and their data are explored through visualization. Redundant columns are removed, and any null values are dealt with appropriately.

2. In Part 2 of the project, basic exploratory data analysis is conducted using appropriate visuals to explore the relationship between mosquito numbers and date.

3. In Part 3, advanced exploratory data analysis is performed to examine the relationship between mosquito species and WNV prevalence using an appropriate visual. Additionally, the relationship between the number of mosquitoes caught and trap type is explored using a different type of visualization. Finally, an additional insight of the analyst's choice is explored using an appropriate visual.

4. In Part 4, more advanced statistical analyses are conducted to determine how independent variables affect the number of mosquitoes caught and WNV presence. Linear regression and logistic regression models are constructed and analyzed, and limitations of the models are discussed.

The project is intended to provide a comprehensive understanding of the dataset and to draw meaningful insights from the data through exploratory data analysis and statistical modeling.

---

In part 2, I will move on to a set of analyses on the relationship between the different variables and the mosquito number, as well as the probability of finding West Nile Virus (WNV) at any particular time and location using Advanced Statistical Analysis like Linear and Logistic Regression.




For this part, you must use the provided cleaned dataset which differs from that for Part 1. [Download the data here](https://api.brainstation.io/content/link/1OlcA7a7d0KXPMpFEZdjcgiNwqBsPEVPl).

<img alt="image" src="https://www.sccmad.org/images/mosquito-abatement-blog-post-3.jpg">

This part aims to analyze a dataset containing information on the occurrence of West Nile Virus in mosquitoes in the city of Chicago. The dataset includes data on the number of mosquitoes caught, the species of mosquitoes, the location of traps, trap types, and the presence or absence of West Nile Virus.

Part 2 will be divided into three parts: basic analysis, statistical analysis, and advanced statistical analysis.

1. In the basic analysis, the WNV Present column will be converted into a binary column, and dummy variables will be created from the Trap type column. The average number of mosquitoes for each month will be calculated, and trends will be identified.

2. In the statistical analysis, the focus will be on identifying correlations between the different columns and the number of mosquitoes caught. Positive and negative correlations will be identified, and the statistical significance of these correlations will be evaluated.

3. In the advanced statistical analysis, linear and logistic regression models will be constructed to determine how the independent variables affect the number of mosquitoes caught and the presence of West Nile Virus. The models will be constructed iteratively, and their limitations will be analyzed.

The project will require the use of statistical software such as Python or R, and visualization tools such as Matplotlib or ggplot2. The project will help to identify factors that contribute to the occurrence of West Nile Virus in mosquitoes, and could potentially help in the development of strategies to control the spread of the virus.

# World Economic Indicator
GDP(Gross Domestic Product)
Before you delve into it, let’s have a basic understanding of GDP.
Gross domestic product (GDP) is the total monetary or market value of all the
finished goods and services produced within a country’s borders in a specific period,
usually one financial year.
- GDP provides a scorecard for a country’s Economic Health.
- GDP can be calculated in 3 ways using Expenditure, Production or income.
- The GDP ratio to the region's total population is the per capita GDP, and the
same is called the Mean Standard of Living.
More on GDP
It is common to use GDP as a measure of economic welfare or standard of living in a
nation. When comparing the GDP of different nations for this purpose, these two
must be as follows:-
1. GDP of all countries should be in the same currency.
2. GDP of two countries will be dependent on the population as well, so it is always
good to compare them with respect to GDP per capita which is GDP/ population.
There can exist multiple factors that affect a country's GDP in both good and bad
ways; let's look into some common factors like industries production, population,
pollution, Government policies, etc. There are a few factors that will be different as
per the population. Whenever these features i.e, Energy consumption, CO2
emission and Tourism Outbound are compared between two countries they
always get calculated in terms of per population (per capita).

# Problem Statement:

The Organisation for Economic Co-operation and Development is creating a
department under its name which will focus on how a country can attain sustainable
growth. 
This organisation hires you as a data analyst for this department to
determine which factors a country should focus on to sustain GDP/ Capita.
Now, they provide you with the dataset ( World Economic Indicator Dataset), which
has different countries' and regions' GDPs, populations, and other factors that might
impact GDP/Capita. 
Now using Data Analysis methods, develop a solution that can
be referred to as “how a country can attain sustainable growth“.

Steps to Follow:
Formating & Data Processing: Before you start with your analysis, rearrange the columns in all sheets where you
can bring all the common columns as the first three columns of the individual sheet.
Then perform formatting on each sheet to make it presentable and understandable.

Once your sheet is ready, Apply data processing steps to prepare the dataset for the
analysis.

Data Analysis: 
Find individual features and study their distribution in the dataset. Further, analyse
how they impact the GDP column (like how Lending Interest affects GDP ) and
develop factors that affect a country's GDP to solve our Business Problem.

Storytelling:
Create a storyline that can be presented to the stakeholders. This should have all the
insight you got while doing the analysis.

# Your project will be evaluated on following parameters -
APPLY FORMATTING AND DATA PROCESSING
(Max Score 200)
Perfom all the formatting operation to make data presentable. Before the analysis, perform all the sub steps of data processing on the data.

PERFORM ANALYSIS TO GAIN INSIGHTS
(Max Score 400)
On the prepared data sheet, perform univariate and bivariate analysis to get useful insights.

EVALUATE THE INSIGHTS AND CREATE A STORYLINE
(Max Score 150)
Create a final outcome power point presentation using all the insights.

# Submission
Steps to Follow:
~Formating & Data Processing:
Before you start with your analysis, rearrange the columns in all sheets where you
can bring all the common columns as the first three columns of the individual sheet.
Then perform formatting on each sheet to make it presentable and understandable.

~Once your sheet is ready, Apply data processing steps to prepare the dataset for the
analysis.

~Data Analysis:
Find individual features and study their distribution in the dataset. Further, analyse
how they impact the GDP column (like how Lending Interest affects GDP ) and
develop factors that affect a country's GDP to solve our Business Problem.

~Storytelling:
Create a storyline that can be presented to the stakeholders. This should have all the
insight you got while doing the analysis.

# Questions asked initially
~ How to approach:

First, create a Unique Id as the first column of each sheet and then merge the sheets.
To merge different sheets, can take help of VLookup
Vlookup Syntax: =VLOOKUP(search_key, range, index, [is_sorted])

~ How would you handle the missing values in GDP dataset?

In this case, we can not replace missing values with any other values like mean/median/zero, etc. because GDP is a critical value, and the GDP of a country changes over a period of time depends on various factors.
Also whichever factors impact the GDP, will always have some value trend over a period. So because of this, any value which is missing in-between can not be replaced by zero or any aggregated method.
To impute the value for the current year we can take the previous year’s value for the same feature and region. 
Because for two consecutive years economic trends can be taken the same for the analysis. 
If the previous year’s value is also missing, then the best suitable practice, in that case, is to leave that cell blank.

~ Which of the following conditions will you use to handle the missing values?

Using an IF condition after sorting the data set in ascending order with respect to region, country & year. To handle missing values, you are replacing the missing value with the same country/Region’s previous year value. If the previous year's value is also missing, then leave it as it is.

~ What can you say about the presence of Outliers in the Dataset?

I can find outliers in the dataset in columns such as Health exp/Capita, Energy usage, CO2 emission, Population Total, etc.



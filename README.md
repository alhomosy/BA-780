# **Analyzing Regional Job Trends Across Industry Sectors in the United States**

## **1. Project Objective**

**Project title :** Analyzing Regional Job Trends Across Industry Sectors in the United States

**Problem Definition:** Exploring the correlation between employment across various sectors and various economic factors such as (GDP, income index) over the past few years.

1. Identifying the sectors with highest and lowest employment volatility.
2. Studying the effect of economic events on jobs across sectors
3. Analyzing the rate of firm deaths (closures) across sectors and the trailing effect on GDP across states.

**Data source :** United States Census Bureau and Bureau of Economic Analytics :
  1. https://data.census.gov/table?q=business+dynamics&tid=BDSTIMESERIES.BDSGEO
  2. https://apps.bea.gov/itable/?ReqID=70&step=1&acrdn=1#eyJhcHBpZCI6NzAsInN0ZXBzIjpbMSwyOSwyNSwzMSwyNi[…]JCZWdpbiIsIi0xIl0sWyJZZWFyX0VuZCIsIi0xIl1dfQ==

**Motivation :** As graduate students who are looking forward to employment in the US, analyzing sector-specific opportunities, job trends and state-level economic patterns will help us make informed career choices, ensuring we put our best foot forward.

## 1.1 Introduction
In the United States, where career opportunities are as diverse as the nation itself, the path to meaningful employment is an intricate puzzle shaped by a multitude of factors. The project, "Analyzing Regional Job Trends Across Industry Sectors in the United States," ventures deep into the dynamic world of employment to unveil the secrets that drive our nation's workforce. By drawing upon authoritative data sources, such as the United States Census Bureau and the Bureau of Economic Analysis, this research is poised to illuminate the American job market like never before.

In an era of unparalleled change and uncertainty, understanding the ebb and flow of job trends is not just a strategic advantage; it is a necessity. For all those charting their professional journeys, be it aspiring graduates or seasoned industry professionals, this project is your compass in the ever-shifting landscape of employment opportunities. It's also a crucial resource for policymakers and economists seeking to grasp the intricate threads that weave the fabric of the American economy.

## 1.2 Summary
The project, is an invaluable resource for anyone seeking a comprehensive understanding of the American job market.

The key takeaways are as follows:

**Employment Stability and Volatility**: This analysis identifies sectors with consistent employment opportunities and those marked by significant fluctuations, providing individuals with the insights needed to make informed career decisions.

**Economic Events and Jobs**: The analysis sheds light on how economic events impact employment trends, equipping individuals and businesses to navigate through economic shifts with greater resilience.

**Business Life and GDP Impact**: This analysis explores the lifecycle of businesses across various sectors and their influence on state-level economies. This analysis unveils the intricate relationship between entrepreneurship and economic stability.

For job seekers, policymakers, and economists, this project serves as a valuable compass in the dynamic American job market. With this comprehensive insight, individuals can make well-informed choices and chart a course toward success in the United States.

# **3. Data Dictionary**
We have two data sets here
1. Business Dynamics Statistics across States (1978 - 2021)
2. GDP data across the States (1998 - 2022)

## 3.1 Description for Job data Columns
*   **Geographic Area Name** : Including all the states in the US.

*  **2017 NAICS Code** : A NAICS Code is a classification within the North American Industry Classification System. The NAICS System was developed for use by Federal Statistical Agencies for the collection, analysis and publication of statistical data related to the US Economy. For instance, naics code 11 equals to "Agriculture, forestry, fishing and hunting".

*   **Meaning of NAICS Code** : Sectors.

*   **Meaning of Establishments located in Metropolitan or Micropolitan Statistical Area indicator** :  Establishments located in Metropolitan or Micropolitan Statistical Areas are designated as in metro.

*   **Year** : The reference year for the data.

*   **Number of firms** : A firm is a business organization or entity consisting of one or more domestic establishments (locations) under common ownership or control.

*   **Number of establishments** : An establishment is a single physical location at which business is conducted.

*   **Number of employees** : The reference employees for the data.

*   **(DHS) denominator (DENOM)** : Davis-Haltiwanger-Schuh (DHS) denominator. For time t, (current year) denom is the average of employment for times t and t-1. This variable attempts to prevent transitory shocks from creating a bias in the relationship between net growth from t-1 to t and size.

*   **Number of establishments born during the last 12 months** : A count of establishments born during the last 12 months.

*   **Rate of establishments born during the last 12 months** : Equal to the number of establishments born during last 12 months divided by the average number of estabs in year t (current year) and year t-1 (prior year).

*   **Number of establishments exited during the last 12 months (ESTABS_EXIT)** : A count of establishments that exited during the last 12 months.

*   **Rate of establishments exited during the last 12 months (ESTABS_EXIT_RATE)** : Equal to the number of establishments that exited during last 12 months divided by the average number of estabs in year t (current year) and year t-1 (prior year).

*   **Number of jobs created from expanding and opening establishments during the last 12 months** : A count of all employment gains within the cell from expanding and opening establishments in the last 12 months.

*   **Number of jobs created from opening establishments during the last 12 months** : A count of jobs created from opening establishments during the last 12 months.

*   **Number of jobs created from expanding establishments during the last 12 months** : A count of jobs created from expanding establishments during the last 12 months.

*   **Rate of jobs created from opening establishments during the last 12 months** : Equal to the number of jobs created from opening establishments during the last 12 months divided by the average employment for time period t (current year) and time period t-1 (prior year).

*   **Rate of jobs created from expanding and opening establishments during the last 12 months** : Equal to the number of jobs created from expanding and opening establishments during the last 12 months divided by the average employment for time period t (current year) and time period t-1 (prior year).

*   **Number of jobs lost from contracting and closing establishments during the last 12 months** : A count of jobs lost from contracting and closing establishments during the last 12 months.

*   **Number of jobs lost from closing establishments during the last 12 months** : A count of jobs lost from closing establishments during the last 12 months.

*   **Number of jobs lost from contracting establishments during the last 12 months** : A count of jobs lost from contracting establishments during the last 12 months.

*   **Rate of jobs lost from closing establishments during the last 12 months** : Equal to the number of jobs lost from closing establishments during the last 12 months divided by the average employment for time period t (current year) and time period t-1 (prior year).

*   **Rate of jobs lost from contracting and closing establishments during the last 12 months** : Equal to the number of jobs lost from contracting and closing establishments during the last 12 months divided by the average employment for time period t (current year) and time period t-1 (prior year).

*   **Number of net jobs created from expanding/contracting and opening/closing establishments during the last 12 months** : A count of net jobs created from expanding/contracting and opening/closing establishments during the last 12 months. This is equal to job creation minus job destruction.

*   **Rate of net jobs created from expanding/contracting and opening/closing establishments during the last 12 months** : Equal to the number net jobs created from expanding/contracting and opening/closing establishments during the last 12 months divided by the average employment for time period t (current year) and time period t-1 (prior year).

*   **Rate of reallocation during the last 12 months** : A measure of the rate of job reallocation over and above that needed to accommodate the net job creation in the cell. Equal to job_creation_rate plus job_destruction_rate - absolute value(net_job_creation_rate).

*   **Number of firms that exited during the last 12 months** : A count of firms that exited during the last 12 months.

*   **Number of establishments associated with firm deaths during the last 12 months** : A count of establishments associated with firm deaths during the last 12 months.

*   **Number of employees associated with firm deaths during the last 12 months** : A count of employees associated with firm deaths during the last 12 months.

## 3.2 Description of GDP Information Columns

The description of the columns in the dataset is as follows:

* **GeoName** : Includes all the states
* **LineCode** : Code to identifty the name of the state
* **Description** : Includes various variables such as:
* **Real GDP_2012** : millions of chained 2012 dollars series, are calculated as the product of the chain-type quantity index and the 2012 current-dollar value of the corresponding series, divided by 100.
* **Real Dollar Statistics**: Includes Real GDP, Real Personal Income, Real * Personal Consumption Expenditure
* **Current Dollar Statistics** : Includes GDP, Personal Income, Disposable * Personal Income, Personal Consumption Expenditure
* **Real Per Capita Dollar Statistics** : Includes Real Per Capita Personal Income, Real Per Capita Personal Consumption Expenditure
* **Per Capita Current Dollar Statistics** : Includes Per Capita Personal Income, Per Capita Disposable Income, Per Capita Personal Consumption Expenditure
* **Price Indexes** : Includes Regional Price Parities, Implicit Regional Price Deflator
* **Employement** : Number of jobs
* **Years** : starting from 1998 to 2022

The dataset includes information about:

* State and Year wise information about Real GDP, Real Personal Income and Real Personal Consumption Expenditure, Disposable Personal Income, Per Capita Income and Expenditure
* State and Year wise information about the Regional Price Parities, Implicit Regional Price Deflator
* State and Year wise Number of jobs

Basic Information

* There are a total of 1105 rows
* There are a total of 29 columns
* There are 9700 null values

# **4 Conclusions**

**Decoding Two Decades: A Deep Dive into the US Economy (2000-2020)**

Our odyssey through the intricate terrain of the US economy over two transformative decades reveals an absorbing narrative marked by resilience, disparities, and the delicate equilibrium between economic health and prosperity.

Intriguingly, specific sectors emerged as the bellwethers of job volatility. Manufacturing, Administration Services, and Construction were not only the most capricious but also corroborated by quantitative data. Articles from trusted sources resonate with our findings, further emphasizing the profound flux in these domains.

Venturing back to the annals of history, the **2008 recession** looms large. This seismic event deeply impacted the job market. **California, Texas, Florida, New York, and Illinois** experienced the most pronounced setbacks. Numerically, these states collectively witnessed a staggering **~9 million** job losses. This revelation underscores the pivotal role that regional dynamics play in shaping job opportunities and economic resilience.

As we explore the narrative of layoffs and firm closures, a regional tableau unfolds. The West region surfaces as the most vulnerable, with a significant **20%** decrease in jobs. In stark contrast, the Midwest remains an epitome of stability, experiencing a mere **3%** decrease. This divergence can be attributed to the varying concentrations of industries within these regions. It is evident that geography and economics are intrinsically linked, with far-reaching implications.

Our exploration has unveiled a profound comprehension of the continuously evolving US economy. It tells a narrative that highlights the dynamic interplay between job market fluctuations, the oscillations within distinct sectors, and the impact of macroeconomic forces.









# Project of Data Visualization (COM-480)

| Student's name | SCIPER |
| -------------- | ------ |
| Tatiana Tuor | |
| Robin Patriarca | |
| Mathis Magnin | 327 838 |

[Milestone 1](#milestone-1) • [Milestone 2](#milestone-2) • [Milestone 3](#milestone-3)

## Milestone 1 (21st March, 5pm)

## Instructions

**10% of the final grade**

This is a preliminary milestone to let you set up goals for your final project and assess the feasibility of your ideas.
Please, fill the following sections about your project.

*(max. 2000 characters per section)*

### Dataset

> Find a dataset (or multiple) that you will explore. Assess the quality of the data it contains and how much preprocessing / data-cleaning it will require before tackling visualization. We recommend using a standard dataset as this course is not about scraping nor data processing.
>
> Hint: some good pointers for finding quality publicly available datasets ([Google dataset search](https://datasetsearch.research.google.com/), [Kaggle](https://www.kaggle.com/datasets), [OpenSwissData](https://opendata.swiss/en/), [SNAP](https://snap.stanford.edu/data/) and [FiveThirtyEight](https://data.fivethirtyeight.com/)), you could use also the DataSets proposed by the ENAC (see the Announcements section on Zulip).


[Swiss Import Export Dataset (1988-present)](https://opendata.swiss/en/dataset/schweizerische-exporte-und-importe-nach-tarifnummer-und-land-monatliche-daten-ab-1988)


### Problematic

> Frame the general topic of your visualization and the main axis that you want to develop.
> - What am I trying to show with my visualization?
> - Think of an overview for the project, your motivation, and the target audience.

### Exploratory Data Analysis

> Pre-processing of the data set you chose
> - Show some basic statistics and get insights about the data

### Related work


> - What others have already done with the data?
> - Why is your approach original?
> - What source of inspiration do you take? Visualizations that you found on other websites or magazines (might be unrelated to your data).
> - In case you are using a dataset that you have already explored in another context (ML or ADA course, semester project...), you are required to share the report of that work to outline the differences with the submission for this class.

# Project Report

### Dataset

> The dataset contains Swiss import and export data by tariff number and country, updated monthly from 1988 to 2023. It provides detailed trade flows, including product categories and destination/origin countries. The data is accessible at [Swiss Import Export Dataset (1988-present)](https://opendata.swiss/en/dataset/schweizerische-exporte-und-importe-nach-tarifnummer-und-land-monatliche-daten-ab-1988).  
> The main files contain six key pieces of information: import or export status, date, article ID, country ID, price, and weight. Occasionally, the weight is missing for some products. Overall, the dataset is very clean. In addition to the main files, there are two auxiliary files: one containing a table with article IDs and their definitions, and another containing a table with country IDs and their corresponding names. All this information is available in three languages (German, French, and English).  

### Problematic

> The project aims to create an interactive website that visually represents Swiss trade patterns, making complex trade data easy to understand. It will include an interactive map and various statistical representations such as graphs, tables, and key metrics.  
> We anticipate two main types of users:  
> 1. **Experts** (economic, geographic, or historical) interested in a general overview of Swiss imports and exports.  
> 2. **Consumers** who want to explore the provenance of specific products and their evolution over time.  

### Exploratory Data Analysis

> For basic preprocessing, we loaded the dataset and parsed the date column into day, month, and year. We handled missing dates by raising an error but found none.  
> We then created bar plots of product count and average price per year, displayed in `first_look.ipynb`, to gain initial insights into the data.  

### Related Work

> Other projects use this data for economic analysis and reports. Our approach is unique because we focus on interactive and user-friendly visualizations rather than static reports, such as the [Swiss Federal Customs Administration Reports](https://www.bazg.admin.ch/bazg/en/home/topics/swiss-foreign-trade-statistics/daten/gesamtexporte-und-importe.html).  
> Currently, our inspirations include previous projects, course slides, and pre-visualization examples from the [D3.js](https://d3js.org/) library.  


## Milestone 2 (18th April, 5pm)

**10% of the final grade**


## Milestone 3 (30th May, 5pm)

**80% of the final grade**


## Late policy

- < 24h: 80% of the grade for the milestone
- < 48h: 70% of the grade for the milestone


# New York Police Department Court Summons Analysis (2010-2020)

## Project Overview

This project aims to analyze and visualize court summons data from the New York Police Department (NYPD) for the years 2010 to 2020. The dataset includes various attributes related to the summonses issued, such as offense descriptions, demographics of the individuals involved, and geographical information. The goal is to gain insights into the patterns and trends in court summonses over this period.

## Methodology

### Data Acquisition

Data was retrieved using the NYC Open Data API and includes court summons records from 2010 to 2020. The data was further processed and stored in a MongoDB database.

### Data Preprocessing

Data preprocessing steps included handling missing values, cleaning the data, and transforming various attributes to suitable formats for analysis. Specific steps involved:
- Dropping records with missing or unknown values.
- Converting date columns to datetime format.
- Encoding categorical variables.

### Exploratory Data Analysis (EDA)

EDA was conducted to understand the distribution of features and their relationships with the target variable. Visualizations were created using libraries such as Seaborn, Matplotlib, and Plotly.

### Data Visualization

Several visualizations were created to highlight key insights, including:
- Bar plots for the most common offenses.
- Catplots to analyze the relationship between year, race, and boroughs.
- Waffle charts for the distribution of summons over the years.
- Histograms and stacked bar charts for demographic analysis.
- Heatmaps for geographical distribution.

### Database Operations

The cleaned data was stored in a MySQL database to facilitate further analysis and reporting. SQL queries were used to create and populate the database tables.

## Results

Key insights from the analysis include:
- Marijuana possession, consumption of alcohol, and reckless driving are the most common offenses.
- The year 2017 recorded the highest number of summonses.
- Brooklyn had the highest number of summonses, particularly among Black individuals.
- Males had a higher count of summonses compared to females across all boroughs.
- Summonses were most common among individuals aged 25 to 44.

## Conclusion and Future Work

This project provides valuable insights into the patterns and trends of NYPD court summonses from 2010 to 2020. Future work could focus on deploying the visualizations to a dashboard for real-time monitoring and extending the analysis to include predictive modeling.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

# **Canadian Demographic **

# Description

The project is aimed to study the Canadian demographics change through time, and observe and identify the potential trend merged through data analysis and visualization. The source data came from the Canadian National Census collected before and after the reform in 1971. 

A brief description of the Canadian demographic can be found [*here*](https://www.statcan.gc.ca/en/subjects-start/immigration_and_ethnocultural_diversity).

The data set includes the number of cases and vaccine coverage of some common diseases. The time span includes from the 1970s to 2015, and the entities include independent data for nearly 200 countries, combined data for several continents, and overall data for the world.

The Census data were retrieved(Scraped) from [*here*](https://en.wikipedia.org/wiki/Demographics_of_Canada).
The original data officially published by the Canadian Government can be found [*here*](https://www150.statcan.gc.ca/n1/daily-quotidien/221026/dq221026b-eng.htm).

The current trend analysis is mainly focused on the demographic amount Canadian immigrants and their impact on the Canadian population in the past 40 years.
The virtualizations are currently performed through interactive wordcloud, line chart, and back-to-back bar plots.
More and broader analysis is always welcome in the projects.

# Contribution
GXPY1 - Canadian demographic trend visualization of the past 40 years.

# Zip file breakdown
README.md - Please read
Assessment#2 Code R. - The original prototype scripts are stored here.
CApopulation - The original unstructured prototype scripts of the data visualization application are stored here (app.R ).
ReportQuarto_file - The package where stored the quarto outputs.
ReportQuarto.qmd - The original construction file for report presentation.
ReportQuarto.html - The final report presentation.
Cover.docx- The cover sheet as the identifier


# ***Warning*** 
A list of Rstudio packages is used in the current report presentation.
- "pacman": used for a quick environment setup.
- "tidyverse": used for data cleaning and wrangling.
- "robotstxt": used for launching web scraping.
- "janitor": used for pre-cleaning data while scraping.
- "dplyr": used for data cleaning and wrangling.
- "tidyr": used for reshaping data frame.
- "shiny": used for an environment for producing interactive applications
- "wordcloud": used for data visualization for highlighting the most popular values.
- "ggplot2": used for creating plots for data visualization purposes.
- "plotly": used for creating plots and data visualization interactively.
Please ***be aware*** the R packages on the list might be automatically installed while running the current work.

This dataset currently used is from 2017, where the latest data is only updated to 2015, and for further research, performing on an updated dataset is always welcome.

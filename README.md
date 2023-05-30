


# COVID-19 Data Analysis
This project involved analyzing and exploring a COVID-19 dataset to gain insights into the global impact of the pandemic. The dataset contained information about COVID-19 cases, deaths, population, and vaccination data across different locations and continents. The goal of the project was to examine various aspects of the dataset, including the number of cases, deaths, vaccination rates, and their relationship with population and location.

# Steps Taken for Data Analysis


Exploring COVID-19 Deaths Data: The initial analysis focused on the COVID-19 deaths dataset. The data was filtered to include records where the continent information was available. The dataset was then ordered by the third and fourth columns.

# Dataset  

This dataset was gotten from https://ourworldindata.org/covid-deaths and the files can be found in the repository also with the sql script.

**Total Cases and Deaths by Location:** A query was used to retrieve data on the total cases, new cases, total deaths, and population by location and date. The results were ordered by location and date.

**Likelihood of Death if Infected:** To examine the likelihood of death if infected with COVID-19 in France, the dataset was filtered for records containing 'France' in the location. The query calculated the death percentage by dividing the total deaths by the total cases and multiplying it by 100.

**Percentage of Population Infected:** The analysis further explored the relationship between the total cases and the population. The query calculated the percentage of the population infected by dividing the total cases by the population and multiplying it by 100.

**Highest Infection Rates by Population:** This analysis aimed to identify countries with the highest infection rates compared to their population. The query grouped the data by location and population, and calculated the highest infection count and the corresponding percentage of the population infected.

**Countries with the Highest Death Count per Population:** The query identified countries with the highest death count per population. The data was grouped by location and population, and the maximum total deaths were calculated.

**Analysis by Continent:** The dataset was further analyzed by continent to identify the continent with the highest death count. The query grouped the data by continent and calculated the maximum total deaths.

**Global COVID-19 Numbers:** This analysis focused on the overall global COVID-19 numbers. The query calculated the total cases, total deaths, and the death percentage by dividing the total deaths by the total cases and multiplying it by 100.

**Population vs. Vaccination:** The dataset was joined with the COVID-19 vaccinations data to explore the relationship between population and vaccination. The query retrieved data on the continent, location, date, population, new vaccinations, and the rolling count of vaccinated people.

**CTE and Temporary Table:** The analysis made use of Common Table Expressions (CTE) and a temporary table to store intermediate results for further analysis and visualization.

C**reating a View:** A view was created to store the data from the analysis of population vs. vaccination for later visualization.

# Conclusion



This project involved analyzing a COVID-19 dataset to gain insights into the global impact of the pandemic. Various aspects of the dataset, such as total cases, deaths, vaccination rates, and their relationship with population and location, were explored. The analysis provided valuable information about the likelihood of death if infected, the percentage of the population infected, countries with the highest infection rates, and the continents with the highest death counts. The project utilized SQL queries, CTEs, temporary tables, and views to perform the analysis and store intermediate results for further visualization and exploration. The findings from this analysis contribute to a better understanding of the impact of COVID-19 globally.
# Covid-19 Data Exploration
## Overview
This project explores Covid-19 data, focusing on deaths and vaccinations, using various SQL techniques such as joins, CTEs, temporary tables, window functions, aggregate functions, creating views, and converting data types. The dataset contains information on Covid-19 cases, deaths, population, and vaccinations.
## Data Sources
The project uses two main tables:
 * CovidDeaths.xlsx - Contains data on Covid-19 cases, deaths, and population.
 * CovidVaccinations.xlsx - Contains data on Covid-19 vaccinations.
## SQL Techniques Used
 * Joins: To combine data from CovidDeaths and CovidVaccinations.
 * CTEs (Common Table Expressions): For simplifying complex queries.
 * Temporary Tables: For intermediate data storage and calculations.
 * Window Functions: For calculating rolling sums and other aggregate values.
 * Aggregate Functions: To calculate sums, maximum values, and percentages.
 * Views: For storing and reusing query results.
 * Data Type Conversions: To ensure proper calculations and comparisons.
## Analysis Performed
1. Initial Data Selection: Filtering and ordering the initial dataset.
2. Total Cases vs Total Deaths: Calculating the death percentage for the United States.
3. Total Cases vs Population: Calculating the infection percentage of the population.
4. Highest Infection Rate Countries: Identifying countries with the highest infection rates.
5. Highest Death Count Countries: Identifying countries with the highest death counts.
6. Death Count by Continent: Calculating death counts per continent.
7. Global Numbers: Summarizing global Covid-19 data.
8. Vaccination Analysis: Calculating the percentage of the population vaccinated using rolling sums and different SQL structures.
9. Creating View: Storing data for later visualizations.
## Getting Started
To run these queries, you need access to the PortfolioProject database with the CovidDeaths and CovidVaccinations tables. You can execute the provided SQL scripts in your preferred SQL environment.
## Prerequisites
* SQL Server or any other compatible SQL database.

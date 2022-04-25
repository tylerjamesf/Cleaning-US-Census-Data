# Cleaning US Census Data

## Goal

In this project, I will take on the role of a Data Analyst at the Census Bureau, which collects census data and creates interesting visualizations and insights from it. I will clean the data and organize the data. The first visualization I will make is a scatterplot that shows average income in a state vs proportion of women in that state. From there, I will make histogram and bar graphs based on race data gouped by each state.

## Method
I will be using `glob` to combine files, `regex` to clean and replace data in columns, `fillna` and `drop_duplicates` to handle missing data, and `matplotlib` to plot the cleaned data into visualization.

## Data


### Dataset

The data has been provided and oragnized in 10 files named states[0-9].

### Data Overview

- `State` : the name of the state
- `TotalPop` : total population of state in whole number
- `Hispanic` : percentage of population with indicated race
- `White` : percentage of population with indicated race
- `Black` : percentage of population with indicated race
- `Native` : percentage of population with indicated race
- `Asian` : percentage of population with indicated race
- `Pacific` : percentage of population with indicated race
- `Income` : average income of state in dollar formatting
- `GenderPop` : number of population based on gender, expressed as `numberM_numberF`

# 120 years of Olympics: Croatia

## Introduction
This project is looking into an Olympics dataset with 120 years of data from 1896 - 2016 with the focus on participants 
representing Croatia.

## Objective
The goal is to find out if the success of female participants has increased in the recents years and how big is the 
difference between female and male participants when it comes to winning medals.
Hypotheses:
  1. The number of female participants and medal winners has increased with the time
  2. The number of male participants is still significantly higher
  3. The number of male medal winners is still significantly higher

## Code Overview
This Python script performs exploratory data analysis (EDA) on the `athlete_events` and `regions` datasets, providing 
insights into Olympic athlete events and National Olympic Committee (NOC) regions.

Steps:
Loading DataFrames:
   - Uses pandas to load the `athlete_events` and `regions` datasets from CSV files.

   python:
   import pandas as pd,
   athlete_events = pd.read_csv('path/to/athlete_events.csv'),
   regions = pd.read_csv('path/to/noc_regions.csv')

Exploring DataFrames:
   - regions.head(), regions.tail(), len(regions), regions.info(), regions.region.hist()
   - athlete_events.head(50), len(athlete_events), athlete_events.info(), athlete_events.Age.hist(), athlete_events.Sex.hist(), athlete_events.Season.hist()

## Results
All three hypotheses have been proven correct.

## Conclusion
Even though the number of female participants representing Croatia has been slowly increasing the discrepancy between
the number of male participants and medals winners is still significantly high. 


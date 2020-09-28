# Covid-19 Exploration (Our World in Data) 
## by Moahmed Desouky

## Introduction
**Exploring**, **analyzing** and **visualizing** data to find some relationships and answers about the world pandemic `Covid-19`.

## Dataset

**The data** I will be using (and analyzing and visualizing) is dataset about **Coronavirus** Pandemic `COVID-19` avalibale via [**Our World in Data**](https://ourworldindata.org/coronavirus) website.

According to [WikiPedia](https://en.wikipedia.org/wiki/Our_World_in_Data), **Our World in Data** (OWID) is a scientific online publication that focuses on large global problems such as poverty, disease, hunger, climate change, war, existential risks, and inequality.

The trajectories show the daily number of confirmed cases. But the widely available data on confirmed cases only becomes meaningful when it can be interpreted in light of how much a country is testing. This is why **Our World in Data** built the [global database on COVID-19 testing](https://ourworldindata.org/coronavirus-testing) and the line colors in this chart show whether a country is testing adequately or not.

This **dataset** has `41` variables and `45,207` records

I used this **dataset** to answer the questions I had about the world pandemic **Covid-19**. Through the multiple **Data Wrangling** process, `Gathering`, `Assessing` and `Cleaning` the data. 

Generally, the dataset was already in a clean format, but some slight cleaning issues needed to be addressed. Also, I divided the data into six different tables are `country`, `corona`, `economy`, `pop`, `healthcare`, `social` depending on each variable category.

**Note:** Data wrangling process and data exploration are embedded in the project notebook with each steps.

## Summary of Findings
- The `top infected continents` are **South America** with `1.75%` followed by **North America** with `1.39%` and **Europe** with `0.59%`, while continents **Asia**, **Africa** and **Oceania** are all below `0.25%`.
- The `top infected countries` are **Peru**, **Brazil**, **Argentina**, **Costa Rica** and **Bolivia**.
- The effect of **smoking** on Coronavirus **symptom severity** has not yet been proven.
- Governments had failed to control Covid-19 pandemic with their stringency policies. So, we need to find better and more effective solutions.
- There is a recent increase in infection rates which indicate a second wave of **Covid-19**.
- In terms of `total cases` **USA**, **Russia**, **Peru** and **Brazil** are on the top. 


## Key Insights for Presentation
- If we depend in our analysis on the total number of cases or deaths instead of **ratios**, we might end with false results, e.g, **Asia** has the highest total cases number, while in fact it's the 4th continent in infection rates and that's because of its high number of population, almost `60%` of total population in the world. So, we have to take ratios into consideration.
- There are many countries that had done a large number of tests, e.g. **Qatar**, and that might result in being these country on the top of infected countries list (total cases / total population), but that's because either it had done a large number of tests (**Qatar** had done tests as total of `25%` of its population till now) or it has a low population (**Qatar** also has low population almost 2.9 million) or both. While **Peru** is the most infected country so far in terms of `infection rates`.

## Resources
- [WikiPedia](https://en.wikipedia.org/wiki/Our_World_in_Data)
- [global database on COVID-19 testing](https://ourworldindata.org/coronavirus-testing)
- [Coronavirus](https://www.undp.org/content/undp/en/home/coronavirus.html)
- [link](https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-codebook.csv)
- [Our World in Data](https://ourworldindata.org/coronavirus)
- [Gathering data](https://ori.hhs.gov/education/products/n_illinois_u/datamanagement/dctopic.html)
- [Cleaning Data](https://en.wikipedia.org/wiki/Data_cleansing)

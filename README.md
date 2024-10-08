# MaternalMortalityRatio
Gaining insights on the World Maternal Mortality Ratio.

## Table of Contents
1.[Introduction](#introduction)

2.[Getting Started](#getting-started)

3.[Features](#features)

4.[Data](#data)

5.[Analysis](#analysis)

6.[Results](#results)

7.[Recommendations](#recommendations)

##  Introduction
Welcome to the Maternal Mortality Ratio Project, the complete data analysis process is performed on Excel and PowerBI, this project delves into the intricate details of maternal mortality ratio of different countries from all the continents in the world.

The Maternal Mortality Ratio (MMR) is a crucial indicator within the Gender Inequality Index (GII), an encompassing measure designed to assess gender disparities and inequities within a society. The GII, an extension of the Human Development Index (HDI), focuses on three primary dimensions: reproductive health, empowerment, and economic activity. Reproductive health, one of the key dimensions, sheds light on the challenges faced by individuals based on their gender. Within this context, the Maternal Mortality Ratio specifically gauges the number of maternal deaths per 100,000 live births, providing insight into the disparities in health outcomes experienced by women. This indicator reflects the state of maternal health and underscores the importance of addressing reproductive rights to mitigate gender inequalities.

## Getting Started 
As a healthcare data analyst, the maternal mortality ratio dataset was stumbled upon on Kaggle and an immediate interest was triggered with the aim of finding out trends and understanding the history and current trend of what the situation with maternal mortality is.

## Features
Some key features include:

--**Average Maternal Mortality Ratio by continent**

--**Average Maternal Mortality Ratio by country**

--**Total number of countries in the dataset**

--**Country with the highest maternal mortality rate**.

--**Trend in Maternal Mortality Ratio over the Years(1990-2021)**

## Data
Data was downloaded from Kaggle as a csv file containing 39 columns and 195 rows which were cleaned and sorted in Excel, some null rows and columns existed in the dataset which were removed during the cleaning phase, making the total number of rows:183 and 38 columns left for analysis, Data was summarized using Pivot Table for the average mortality by country and continents, which was then imported in PowerBI for visualization and creating a dashboard to convey the message.

## Analysis
Data Cleaning begins

11 blank rows in Maternal Mortality Ratio(MMR) 1990 - 2021,

Using the Find all blank sheets, 3204025 cells were found,
A pattern of 11rows missing from each MMR column was noticed hence i deleted them all.

Rows deleted : 5,48,74,95,103,110,115,134,141,159,181,
HDI ranking had two blank rows:135 and 150, both got deleted,

UNDP developing regions had 52 missing rows: i deleted the whole column because it wasnt necessary for my analysis.

**Data Analysis**

Data was analyzed in Excel and summmarized using Pivot Table, exported to PowerBI for visualization and further organization

## Results

After analysis, data available was from 182 countries and 5 continents categorized.

53 African countries, 47 Asian countries,39 European , 33 American and 10 Oceanian countries were observed as the distribution in the dataset.

Africa ranked the highest with the Average Maternal Mortality Ratio at 581 per 100,000 livebirths,with Europe as the least affected on the graph at 13 Maternal Mortality ratio.

According to countries, Sierra Leone ranked the highest at 1,912 Maternal Mortality Ratio, closely followed by South Sudan with 1,476 while Italy and Greece were ranked the countries with the least Maternal Mortality Ratio with 3(three) each.

The average Maternal Mortality Ratio of Africa is greater than all the other continents combined.

The trend over the 32years period shows improvements and decline in the maternal mortality ratio in every continent.

The Dashboard from PowerBI is shown below;

![Maternal Mortality Ratio](https://github.com/iamBernardMuoneme/MaternalMortalityRatio/blob/main/Maternal%20Mortality%20Dashboard%20Report(1990-2021).PNG)

## Recommendations

Africa needs help desperately and more research needs to be conducted on why the ratio ranks extremely high, Asia seems to be doing almost okay as a continent despite it's large population.

However, more studies needs to be conducted on how European countries are doing far better than Africa and Asian countries and what should be adjusted to drastically reduce the Maternal Mortality Ratio in these continents.

More research in comparison of the African healthsector against the European and Asian healthcare sector would bring more insights on necessary measures that can improve overall health of mothers.




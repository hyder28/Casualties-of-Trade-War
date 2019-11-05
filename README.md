# Casualties of Trade War
## Overview
From the simplest forms of bartering that has been interwoven into the earliest fabric of human history, to the modern-day commodity derivatives traded on virtual exchanges, trade has always existed in one form or another as an important economic activity to mankind.

With globalisation as a catalyst, trade has become entrenched as an integral part of the global economy. Complex webs of country-to-country inter-dependencies have formed, and up to a quarter of global production is being exported (Ortiz-Ospina, Beltekian, & Roser, 2018).

As with other international activities, countries seek to preserve and further national interests when engaging in trade. Thus, trade flows are controlled and regulated by political instruments such as tariffs and sanctions. These tools are often used to impose penalties on antagonistic countries, or to preserve national interests.

Following the US President's recent signing of a protectionist memorandum detailing the imposition of a 25% tariff on $50 billion of imports from China (White House, 2018), and the subsequent announcement of the imposition of hefty tariffs on steel and aluminium imports from several countries (BBC, 2018), the delicate balance of world trade has been shattered. The breakout of a full-blown global trade-war seems to loom ahead, and amongst many questions that arise out of this possibility, we seek to apply visual analytics method to provide exploratory insights on international commodity trading, and to facilitate the analysis of the casualties of this potential trade war.
Please access jupyter notebooks in the repository.

## Project Motivations and Objectives
There is motivation to provide novel visual insights on a current and complex matter that affects the entire world. Using Global Commodity Trade Statistics published by the United Nations Statistics Division, we have identified investable and tradable commodities which fall into Metals, Energy, Livestock & Meat and Agriculture (Lioudis, 2018). Integrating the Commodity Trade with the current GDP data from the World Bank, we plan to identify trends, patterns and dependencies in commodity trade at geographic, regional and economic communities; and identify economies that are sensitive to trade, along with the particular commodities that give rise to this sensitivity. We use a funnel methodology by generalizing our data visualizations by geographic and financial trade commodity groupings before providing a drill-drown facility in an interactive dashboard to help policymakers have a better understanding their economies and trade given the looming trade-war.

Through out analysis, we hope to address the following:
### Commodity Trade Overview: Exploratory Analysis of Commodity Trade by Trading Parameters
We want to explore the hierarchical relationships between trade balance, quantity and volume by trading parameters such as commodity type, trade flow and regions to identify interesting patters between 2007 to 2016.
Choropleth Map: Filter by trade flow, commodity type and year to analyze trade balance (in USD Millions) between 2007 to 2016.
Sankey Diagram: Filter by year to view flow of commodity trade (in USD Millions) from the different commodity types to regions between 2007 to 2016.
Treemap: Filter by year to view import and export commodity trade quantity and volume by regions between 2007 to 2016.
Sunburst: Filter by year to view hierarchy of quantities and volume of commodity trade between 2007 to 2016.

__Commodity Trade Dependencies: Analysis of Trade dependencies by Regions__
We would like to analyze trends and trade dependencies among geographical and economic groups such as Organization for Economic and Development (OECD), European Union (EU) and Southeast Asia (SEA) by the different commodity types and trade flow.
Time-series with geographic panels: Filter by commodity flow and type to analyze trends and trade dependencies among OECD, EU and SEA between 2007 to 2016.

__Commodity Trade Position Over Time: Analysis of Export-to-Import relationship over time__
We would like to analyze commodity trade position by assessing export-to-import relationship among regions over time from 2007 to 2016.
Bubble Plot: Filter by commodity type and regions to assess Export-to-Import relationship among countries between 2007 to 2016.

__Commodity Trade Openness to GDP__
We would like to identify economies that are sensitive to trade, along with the particular commodities that give rise to this sensitivity.
Trellis Scatter Plot: To display the strong R-squared relationship between commodity trade balance to GDP to assess the level of sensitiveness among countries.

## Data Sources
We would be consolidating __Global Commodity Trade Statistics__ with __World Bank GDP__ data by their respective countries. The Global Commodity Trade Statistics[2] and GDP data[3] are retrieved from United Nations Statistics Division and World Bank respectively between 2007 to 2016. The consolidated dataset comprises of investable and tradable import/export commodities from the four (4) main categories: Metals, Energy, Livestock & Meat and Agriculture.

## R Shiny Application
Avaiable: https://funniezatee.shinyapps.io/TradeWars/

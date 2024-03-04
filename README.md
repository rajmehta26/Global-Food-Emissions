# Global Food Emissions

Information and knowledge from three datasets were used to complete this report. You can access all the cleaned datasets, Python scripts, and a detailed report in the repository.

## 1.	EDGAR (Emissions Database for Global Atmospheric Research)
EDGAR-Food serves as a comprehensive global emission inventory detailing greenhouse gas emissions stemming from food systems. This data repository encompasses GHG emissions across more than 200 countries, distinguishing emissions by GHG type and specific stage within the food system annually from 1990 to 2015. The dataset categorizes emissions into eight distinct stages of the food supply chain, with Land designated as Stage 1, Farm as Stage 2, and progressing sequentially to Waste as Stage 8.
The [original dataset](https://edgar.jrc.ec.europa.eu/edgar_food#data_download) needed cleaning and transformation before it could be used for deeper analytical insights. However, in this instance, this preparatory step was unnecessary as a pre-cleaned file was readily accessible [here](https://www.kaggle.com/datasets/amandaroseknudsen/edgarfoodemissions). Details regarding the methodology applied are available in Crippa et al. (2021), [here](https://www.nature.com/articles/s43016-021-00225-9) 

Below are the questions posed or analysed to derive key insights:

a.	What is the trend of total food related GHG emission from 1990 to 2015?
b.	What is the primary contributor to the increase in total greenhouse gas emissions, and what does the trend indicate?
c.	What is the percentage distribution of GHGs during this period?  
d.	What is the distribution of GHG emissions among different stages of food life cycle? 

## 2.	Environmental Impacts of Food 
The information provided in the Environmental Impacts of Food [dataset](https://www.science.org/doi/10.1126/science.aaq0216) originates from the research conducted by Jospeh Poore and Thomas Nemecek in 2018. This study, regarded as the most extensive meta-analysis of food systems to date, encompasses 43 of the most consumed products, examining their environmental impact from production to the point of sale. Spanning nearly 40,000 farms across 120 countries, the study ensures a comprehensive analysis that avoids bias towards any specific geographic region or income level. Notably, emissions stemming from cooking, refrigeration, and post-consumption food waste within the supply chain are excluded from the study's scope.

Questions addressed with this dataset are as follows:

a.	What is the average global emission per kilogram of food product?
b.	What is the percentage distribution of emission across the supply chain, for the two most polluting products on a per kilogram basis?


## 3.	GLEAM (Global Livestock Environmental Assessment Model) Emissions Data
The [Global Livestock Environmental Assessment Model](https://www.fao.org/gleam/en/) is a modelling framework developed within the Animal Production and Health Division of FAO. It simulates the functioning and environmental impacts of livestock production activities. The most relevant characteristics of GLEAM are:
a.	It is based on Life Cycle Assessment (LCA) methodologies.
b.	It runs in a Geographic Information System (GIS) environment.
c.	It covers upstream, on-farm and downstream impacts.
d.	The current version of GLEAM (2.0) focuses on the quantification of greenhouse gas emissions related to livestock sector supply chains.
Content in this dataset is from the GLEAM 2.0 public data release. GLEAM 2.0 was published in 2018 using data from 2010. The [model description](https://www.fao.org/gleam/model-description/data-sources-and-management/en/) can be found on the GLEAM website
 
Questions explored using this dataset are as follows: 

a.	What are the global emissions by different animal species?
b.	How are emissions distributed across various regions for the most polluting animal?
c.	What is the emission distribution profile for each animal species and its associated greenhouse gas?
d.	For which commodity were the animals largely used? 
e.	Which region has the highest emission intensity (kg CO2 eq per kg protein)? Why?

# EDA WINE
* This report analyzes wines reviews containing information of variety, location, winery, price, points and description.

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas for EDA, matplotlib, seaborn and plotly for data visualization, string, sklearn, wordcloud, textblob and collections for NLP.

## Dataset

Data from [Kaggle](https://www.kaggle.com/datasets/zynicide/wine-reviews/data?select=winemag-data_first150k.csv) scraped from WineEnthusiast during the week of June 15th, 2017.Variables: 
* `country`: country that the wine is from.
* `description`: sentences from a sommelier describing the wine's taste, smell, look, feel, etc.
* `designation`: vineyard within the winery where the grapes that made the wine are from.
* `points`: number of points WineEnthusiast rated the wine on a scale of 1-100.
* `price`: cost for a bottle of the wine.
* `province`: province or state that the wine is from.
* `region_1`: wine growing area in a province or state.
* `region_2`: more specific regions specified within a wine growing area.
* `variety`: type of grapes used to make the wine.
* `winery`: licensed facility where wine is made, from the processing of grapes to the final bottling. 
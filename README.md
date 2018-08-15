# Background
The retail prices of key commodities are sourced from Open Government Data platform of India. The dataset contains retail prices for key commodities recorded at around 75 key market centres in India. The granularity of the data is at day level.

## Data Dictionary
```
date : Date the retail price was recorded
centre : One of the 75 regional centres where the prices are recorded
commodity: Name of the commodity
price_per_kg: Price per Kilogram
region: The region of the country, the centre belongs to
country: Name of the country
```

# Questions
 - Use [scikit-learn](http://scikit-learn.org) library for modelling.
 - Provide exploratory data analysis(EDA). This include visualizations and gather insights from each visualization. Find this **[example](https://bibinmjose.github.io/dsgramner/ipython_md/analysis.html)**. Include correlation plots as well.
 - Afterwards create a distilled version of the EDA with most significant insights. Find the progression of earlier **[example](https://bibinmjose.github.io/dsgramner/)**.
 - Create a regression model which predicts future prices with a confidence band. You may create/add new features based on the dataset as well as external sources (include source reference).
 - Tune the model to achieve an [MAPE](https://en.wikipedia.org/wiki/Mean_absolute_percentage_error) of less than <0.5.
 - Find the most important features from your model and substantiate them.

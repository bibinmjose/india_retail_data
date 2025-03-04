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
## Recommended libraries
##### You may use:
 - [Ipython notebooks](https://ipython.org/index.html) to share your work.
 - For modelling: [scikit-learn](http://scikit-learn.org), [tensorflow](https://www.tensorflow.org), [pytorch](https://pytorch.org)
 - For EDA and plotting: [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/), [Pandas](https://pandas.pydata.org/)
 - For statistics and computing: [Numpy](http://www.numpy.org/), [SciPy](https://www.scipy.org/), [Statsmodel](https://www.statsmodels.org/stable/index.html)

# Questions to answer
 - Provide an exploratory data analysis(EDA) with visualizations and insights gathered from each visualization. Find this **[example](https://bibinmjose.github.io/dsgramner/ipython_md/analysis.html)**. Include correlation plots as well.
 - Create a distilled version of EDA with most significant insights. Find the progression of our **[example](https://bibinmjose.github.io/dsgramner/)**.
 - Can you pose 3-4 questions based on your EDA and answer them using statistical tests?
 - Create a model which predicts future prices with a confidence band. You may create/add new features based on the dataset as well as external sources (include source reference). Make sure you split the data into train, validation and test while training.
 - Tune the model to achieve [MAPE](https://en.wikipedia.org/wiki/Mean_absolute_percentage_error) of less than <50 on your test data.
 - Explain the strategy you used to validate and test your algorithm.
 - Find the most important features from your model and substantiate. You may also use external data for the same.
 - Finally, create a visualization overlaying your predictions with raw data.

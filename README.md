# Analysis of Factors that Affect Housing Prices in Melbourne
The housing market has long been a vital sector of Australia's national economy, exerting a profound influence
on economic growth, household wealth, and investment. As a stable yet substantial investment, and a
frequently purchased asset, the analysis of key drivers of housing prices is a widely researched and scrutinized
topic. This paper aims to identify the primary factors influencing housing prices in Melbourne, Australia, and
develop a data-driven model to predict housing prices accurately. To achieve this objective, various machine
learning models are explored, utilizing a public dataset that has been thoroughly cleansed and analyzed prior
to training to enhance accuracy and interpretability of features. An initial exploratory data analysis is conducted
to inform training methodologies, followed by training with potential models to evaluate model performance.
Most importantly, the study seeks to identify key features and factors that can reliably predict housing prices.
The results of this study provide valuable insights into the most influential factors affecting housing prices and
identify the most accurate models for predicting future prices. The findings have significant implications for
prospective homebuyers, real estate agents, and property investors, enabling them to make informed
decisions in the dynamic Australian housing market.

<p align="center">
  <img src="housing_prices.png" alt="Rising Housing Prices" title="Increase in Housing Prices" style="text-align:center" width="400px">
</p>

## Dataset Source
> The repo has the file in the Data folder. Alternatively, the data can be downloaded from the source below:

Melbourne Housing Prices; Source:[here](https://www.kaggle.com/datasets/anthonypino/melbourne-housing-market "Kaggle")

## Guide to Files

### Reports
* [Report](<Analysis of Factors that Affect Housing Prices in Melbourne Report.pdf>)
* [Slides](<Analysis of Factors that Affect Housing Prices in Melbourne Slides.ppt>)

### Python Code Walkthrough
* [EDA](<melbournehousing_EDA.ipynb>) | Extensive data cleaning and variable interactions 
  * Data cleaning is performed here to create a cleaned dataset used for the majority of the analysis
* [Regression and Tree Models] (<melbournehousing_regression_and_trees.ipynb>)
* [Regularization Models] (<Melbourne_regularization.ipynb>)



## How to run files

### Packages Required

| Package       | Description                                     |
|---------------|-------------------------------------------------|
| numpy         | Arrays and numerical computing                  |
| pandas        | Data manipulation and analysis                  |
| matplotlib    | Plotting and visualization                      |
| seaborn       | Statistical data visualization                  |
| scikit-learn	| Machine learning models and tools               |
| statsmodels	| Statistical modeling and inference              |
| xgboost	| Gradient boosting for high-performance modeling |

```python
# Install required packages if not already installed
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels xgboost
```


## Getting Started
1.  **Set up Python Environment & Install Dependencies:** (See **Packages Required** section above).
2. **Download [`MELBOURNE_HOUSE_PRICES_LESS.csv`](MELBOURNE_HOUSE_PRICES_LESS.csv) from Kaggle or from the local file here. Place this in the root folder.**
   ** If the EDA is not being used, you can alternatively download the already cleaned [`cleaned_melbourne_housing.csv`](cleaned_melbourne_housing.csv)
3. **Download code files [`melbournehousing_regression_and_trees.ipynb`](melbournehousing_regression_and_trees.ipynb) and  [`Melbourne_regularization.ipynb`](Melbourne_regularization.ipynb) and place it in the root folder.**

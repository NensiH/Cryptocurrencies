# Cryptocurrencies
## Overview
The purpose of this project is the create a report for an investment bank interested in offering a new cryptocurrency investment portfolio. The report includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data from Accountability Accounting needed to be cleaned in order to fit the machine learning models, and since there isn't a known output for what this investment bank is looking for, unsupervised machine learning was employed. In order to group the cryptocurrencies, a clustering algorithm was utilized and the data was visualized so the finding could be shared with the board.

## Resources

- Data Source: [crypto_data.csv](https://github.com/NensiH/Cryptocurrencies/blob/main/Resources/crypto_data.csv)
- Software: Jupyter Notebook, Anaconda Navigator
- Environment: Python 3.7
  - Dependencies
    - Numpy
    - Pandas
    - Path
    - Plotly
    - SKLearn
    - hvplot


## Results:

### Clustering Cryptocurrencies using K-Means - Elbow Curve

Once [crypto_data.csv](https://github.com/NensiH/Cryptocurrencies/blob/main/Resources/crypto_data.csv) was cleaned and preprocessed, there were 532 tradable cryptcurrencies. We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.

<img width="742" alt="Screen Shot 2022-02-27 at 10 08 56 PM" src="https://user-images.githubusercontent.com/92277581/155922712-068c1a18-c215-40d5-ab86-981240dbd53d.png">

### Visualizing Cryptocurrencies Results
**3D-Scatter plot with clusters**

The following 3D scatter chart shows the cryptocurrency dataset in four clusters.

<img width="720" alt="Screen Shot 2022-02-27 at 10 01 44 PM" src="https://user-images.githubusercontent.com/92277581/155922727-0905d033-06e8-4077-8359-ad5699ffe350.png">


**2D-Scatter plot with clusters**
We have created a two dimisional graph to show the relationship between total coin supply and total coins mined to show how each currency compares to the rest. Each point includes its currency name.

<img width="806" alt="Screen Shot 2022-02-27 at 10 08 29 PM" src="https://user-images.githubusercontent.com/92277581/155922720-3cb133a2-edd8-4fa9-a8ce-7c870cb29add.png">

## Summary
We have identified the classification of 532 cryptocurrencies based on similarities of their features.
Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.

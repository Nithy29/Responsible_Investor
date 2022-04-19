# The Responsible Investor

## Hello and welcome to our group project: The Responsible Investor

For this project, we want to show our investors the negative impact of CO2 emmissions on our planet and provide them with a portfolio of environmentaly friendly companies that is still lucrative. 

We are using the Yahoo ESG scores that are pulled from Sustainalytics. We are focusing on the Environmental scores specifically which can range between 0 and 100. A company with a score between 0-10 would have good controls over their environmental footprint and initiatives. Some of the facots that are assessed for the Environmental score are: Greenhouse Gas Emission, Water Use, Energy Use, Environmental policies.

We will first demonstrate the temperature change over the past years along with the global CO2 emission and how these two factors are correlated with the growth of some oil companies.

In a second part, we will introduce some green investing options. We have selected specific industries: Solar, Renewable Energy for Utilities, Auto Manufactures, Electrical Equipments and Speciality Chemicals. These industries englobe companies that have a good environmental score (less than 10).
We used Yahoo Finance to pull an intial list of companies. We also focused on companies with a current ratio higher between 1 and 2 and a Price/Earning less than 50.

Once we determined the green companies we want to analyze. We pulled historical data using the Alpaca API and we conducted our financial analysis: Daily Return, Standard Deviation to assess volatility, Monte Carlo Simulation and finally a risk adjusted returns based on different portfolio weights.

We will use the S&P 500 index as a benchmark throughout the analysis.

As a final feature of our product, we will present our client with the Responsible Investor Toolbox. It's an additional tool that provides the latest news from each stock, the last 5 dividends payouts and important dates such as earning dates.

___

**Team members:-**
        `Ali Ait,  Kevin Calderon, Hassan Mehmood, Sarvan Veluppillai`

<p>&nbsp;</p>

### Data sources:
- [BERKELEY EARTH](http://berkeleyearth.lbl.gov/regions/global-land)
- [BP - Statistical Review of World Energy](https://www.bp.com/content/dam/bp/business-sites/en/global/corporate/pdfs/energy-economics/statistical-review/bp-stats-review-2021-co2-emissions.pdf)
- [Zenodo](https://zenodo.org/record/5569235#.YldA8sjMKUm)
- [kaggle](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data/code)

<p>&nbsp;</p>

### Notebooks:
- [Stock Analysis](https://github.com/Nithy29/Responsible_Investor/blob/main/Analysis.ipynb)
- [CO2 Analysis](https://github.com/Nithy29/Responsible_Investor/blob/main/CO2%20Emissions/Global%20CO2%20Emissions%20%26%20Temperature%20Change.ipynb)
- [Yahoo Finance Analysis](https://github.com/Nithy29/Responsible_Investor/blob/main/Yahoo%20Finance.ipynb)

<p>&nbsp;</p>

### PowerPoint:

- [Responsible Investor]()

___

### VOILA Installation notes
VOILA can be instaaled through conda
- conda install -c conda-forge jupyterlab voila-gridstack

or PIP install
- pip install voila

Once it is install, change directory to the project folder and issue
- jupter notebook

Select the jupyter lab file and lunch 'VOILA' ![image](https://user-images.githubusercontent.com/98414364/163704316-5818fb57-1592-410f-96bb-0461d0a08ac9.png)
 from the jupyter notebook




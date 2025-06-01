# DSAI514 Statistical Inference - Effective Ball Play Times in Premier League and Turkish Super League

Installing the required libraries:

```
pip install -r requirements.txt
```

The project includes 2 seperate juptyer notebook files for the data collection and statistical inference steps.

* Data Collection.ipynb
* Statistical Inference.ipynb

## Data Collection
Data is scraped from [fbref](https://fbref.com/en/) for the 23/24 and 24/25 seasons for Turkish Super League and Premier League. Data collection part consist of the following steps:
* Scrape all of the game links
* Sample 20 games from each season (40 games for each league)
* Further scrape the game related statistics from the corresponding links for total of 80 games
* Manually inject effective ball play times from Mackolik mobile application

However, it is recommended to use the provided raw data file, <b>dataset_filled.csv</b>, as the data collection process can be time-consuming and requires manual data entry.

## Statistical Inference
The data visualizations and hypothesis testing results presented in the project report can be reproduced using the <b>dataset_filled.csv</b> file and the <b>Statistical Inference.ipynb</b> notebook.

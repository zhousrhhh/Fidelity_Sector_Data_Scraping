# Fidelity Sector Data Scraping

+ Using Python, I scraped data from fidelity.com. 
+ The goal of the [project](code.ipynb) is to get the latest sector performance data from the US markets, and to get the total market capitalization for each sector.
+ The end result is to write a function: get_us_sector_performance() that will return a list of tuples. Each tuple should correspond to a sector and should contain the following data:
  - the sector name
  - the amount the sector has moved
  - the market capitalization of the sector
  - the market weight of the sector
  - a link to the fidelity page for that sector
+ The data should be sorted by decreasing order of market weight. I.e., the sector with the highest weight should be in the first tuple, etc.

# Non-profit Executive Compensation

## Description
How has non-profit executive compensation changed in relation to for-profit executive compensation? Over the past decade, it seems like there has been a blurring of the lines between non-profit and for-profit organizations. Both types of organizations use standardized accounting practices, promote diversity, participatory decision making, and collaborative governance processes.

In light of these qualitative similarities, I wanted to see if we could qualitatively measure isomorphism between non and for profits, through the lens of executive compensation.

## Data
I manually scraped executive compensation and revenue data from organization's IRS 990, SEC DEF 14A, or 10-K annual reports. I would have liked to use Beautiful Soup to scrape the data, but the way in which this data is stored is not formatted consistently between organizations. Due to this limitation, I use a random sample of 23 S&P500 firms, and 23 non-profit organizations taken from Charity Navigator.

## Results
First, I wanted to know whether the relationship between executive compensation and total expenses in each sector was comparable. I found that the relationship between compensation and expenses to be incredibly similar between sectors. Note that the scale on the y-axis for for-profit organizations is orders of magnitude larger than non-profits, but that is to be expected.
![Compensation vs Total Expenses](https://github.com/Bassatron/nonProfit_execComp/blob/master/figures/comp_expenses.png?raw=true)

I followed this up by looking at trends over time to see if executive compensation was trending towards one another. Non-profit executive compensation as a percentage of total expenses was actually greater than for-profit executive compensation and was decreasing towards the for-profit baseline.
![Compensation vs Time](https://github.com/Bassatron/nonProfit_execComp/blob/master/figures/comp_time.png?raw=true)

Lastly I wanted to look at how male vs female executive compensation, and found that female executives in the non-profit sector were earning 56% of the salaries that their male counterparts were commanding.
![Compensation vs Time](https://github.com/Bassatron/nonProfit_execComp/blob/master/figures/male_female.png?raw=true)

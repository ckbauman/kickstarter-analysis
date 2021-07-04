# Kickstarting with Excel

## Overview of Project

Through analysis of Kickstarter fundraising data in various entertainment categories, such as film, music and theater, we have reviewed success and failure rates for the campaigns provided.

Louise has specifically been interested in Fundraising data for plays throughout the United States and Great Britain.  This analysis lead to a successfull introduction of the Play *Fever*, where she was able to come close to their fundraising goal in the kickstarter campaign.

Louise is now interested in reviewing other kickstarter campaigns for theater, to see how well campaigns fared based on launch date and their funding goals.

## Analysis and Challenges

### Theater Outcomes by Launch Date

Our first review is narrowed down to only include Theater data and Launch Date.  We wanted to determine if there is any correlation between success rates and seasonality.

Following is a sample of the dataset used in this analysis. The primary dataset includes the following:
- Name:  Name of item
- Blurb:  Information about the item
- Goal:  Monetary kickstart amount hoped to raise
- Pledged: Actual amount raised
- Outcomes:  Project outcome of Successful, Failed or Canceled
- Country:  Where produced
- Backers:  Number of backers to fund the item
- Percentage Funded:  Calculation of Pledged amount divided by Goal amount
- Average Donation:   Pledged amount divided by the number of Backers
- Parent Category: Primary Category
- Subcategory: Broken out Category derived from Parent Category
- Date Created Conversion:  Launch Date of Kickstarter Campaign
- Date Ended Conversion:  End Date of Kickstarter Campaign

![Kickstarter Data1](https://github.com/ckbauman/kickstarter-analysis/blob/main/KickstarterData1.png)

![Kickstarter Data2](https://github.com/ckbauman/kickstarter-analysis/blob/main/KickstarterData2.png)

The following image includes the data used in the chart further below.  The data includes the Outcome of Successful, Failed or Canceled **Theater** campaigns and is broken out by months the campaigns were launched. There were a total of 1,369 Theater campaigns.

The Launch Date chart below, indicates Theater outcomes of Successful, Failed or Canceled campaigns.

### Outcomes Based on Goals

Our next review looks at data only for Plays and their Goal amounts.  We wanted to determine if there is any correlation between initial Goal amounts and success rates.

The analysis was completed using the same initial dataset used in the prior analysis.

Following are the results of the data broken out to include only Plays and outcomes with their Goal amount.  Percentages were created in each category (Successful, Failed, Canceled).

The following chart includes the Percent Outcomes per Dollar amount Goals for Plays.

### Challenges and Difficulties Encountered

#### Challenges for Theater Outcomes by Launch Date

Please note that Theater data includes all information for Musicals, Plays and Spaces.  Plays make up approximatley 76% of the dataset, while Spaces is 13% and Musicals is at 10%.  Anlysis of this data broken out by subcategory show that Spaces and Musicals are very sporatic, where Plays determines the primary trend for Theater productions.  In hindsight, this dataset should only be looking at Plays to keep our analysis consistent between the 2 review categories.

#### Challenges for Outcomes Basaed on Goals

Both the Success and Failure lines are fairly consistent until around the $35,000 amount.  Further analysis should be done to determine what is causing these anomalies in the dataset.

Also note that the Dollar amounts were not converted based on currency.  This could explain some of the anomalies in the dataset.

## Results

### Outcomes based on Launch Date?

- The graph indicates that Theater launches are most successful in the Summer months of May, June and July with a declining rate as you head into the Fall and Winter.  Launch dates in the months of November and December see the lowest success rates and may be affected by the Holidays.

- Data also suggests that about 40% of launches fail to meet their goal.  Very few launches are canceled and have little impact on the data.

### Outcomes based on Goals?

- The graph indicates that Plays generally failed to meet their goal as the dollar amounts increased.

- The graph also indicates that Plays generally succeeded to meet their goal up to about $20,000 funding goals.

### Limitations of this dataset?

- The 2 reviews in the analysis should have been reviewing the same breakout to produce more consistency.  Either all Theaters or all Plays would have allowed us to standardize the analysis more efficiently.

- Other possible tables and/or graphs might include an analysis of length of the campaign vs. outcome as well as appropriately converting the correct currency amounts in the table.

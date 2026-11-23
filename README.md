# Auto Sales Pricing Dashboard (Power BI)

One-page Power BI dashboard for analysis of 2,747 sales orders: revenue, seasonality and pricing well off of the MSRP.

![Dashboard](dashboard.png)

**Data:** "Automobile Sales data" by Dhruv D on Kaggle (https://www.kaggle.com/datasets/ddosad/auto-sales-data). License is marked as "Other" therefore data will not be uploaded. The columns of customer contacts were dropped during data cleaning process.

**What is shown:** total revenue ($9.76M), units sold (96K), average selling price ($101.22), monthly sales including 8-month forecast, and the share of flagged lines by product line and country.

**Results**
- The median line is priced 0.4% above MSRP, but the average is 4.04% higher, so a few extreme lines pull the average up.
- 396 of 2,747 lines (14.4%) are flagged. The data doesn't explain why, so these lines are for review, not confirmed errors.
- The largest outlier is priced about 7.7 times MSRP, which looks like a data issue (cause unconfirmed).
- Sales peak in November in both 2018 and 2019.

**Drawbacks:** the forecast is made with help of the built-in Power BI method based on 2.5 years of data. The 20% cut-off is a judgement call, and the dataset is a static practice sample.

**Tools:** Power BI Desktop, Power Query, DAX

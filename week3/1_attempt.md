# Assignment 3 – Two Averages, One Argument

## 1. Dataset and Cleaning

I used the teaching prices dataset for this assignment. Followed the cleaning procedures in my Jupyter Notebook. The cleaning process involved removing commas from price values converting the price column into format standardising item names removing duplicate records and identifying missing values. I also identified high prices greater than PKR 1,000 as flagged observations. The original dataset contained 97 rows. After removing one duplicate record 96 rows remained. There was one missing price and two flagged observations.

## 2. Analysis

I calculated the mean, median and first-to-last percentage change for all four items: Oil B, Pulse C Staple A and Sweetener D. Oil B had a mean price of PKR 316.18 and a median price of PKR 324.00. Its first recorded price was PKR 301.00 while its last recorded price was PKR 347.00 representing an increase of 15.28%. Pulse C had a price of PKR 205.91 and a median of PKR 206.00. Its price increased from PKR 200.00 to PKR 210.50 representing a 5.25% increase. Staple A had a price of PKR 160.89 and a median of PKR 112.50. Its price increased from PKR 104.00 to PKR 117.50 representing a 12.98% increase. Finally Sweetener D had a price of PKR 576.81 and a median of PKR 167.75. Its price increased from PKR 152.00 to PKR 181.50 representing a 19.41% increase.

The first-to-last percentage change was calculated by subtracting the price from the last price dividing the result by the first price and multiplying by 100. Based on these calculations Sweetener D experienced the percentage increase while Pulse C experienced the smallest increase.

## 3. Comparison of Mean and Median With and Without Flagged Values

During the analysis I identified two high prices in the dataset. The first was PKR 1,250 for Staple A, recorded in City 2 on 15 January 2026. The second was PKR 9,999 for Sweetener D, recorded in City 1 on 22 January 2026.

For Staple A the mean including the flagged value was PKR 160.89 while the median was PKR 112.50. After excluding the flagged value for comparison the mean decreased to PKR 111.39 while the median remained PKR 112.50.

For Sweetener D, the mean including the flagged value was PKR 576.81 while the median was PKR 167.75. After excluding the flagged value the mean decreased to PKR 167.15 while the median changed slightly to PKR 167.50.

These results demonstrate that the mean is more sensitive to high values than the median. The presence of an observation can significantly increase the mean whereas the median generally remains more stable.

## 4. Referees Note

**O – Observation:** All four items experienced an increase in price between 1 January and 19 March 2026. Oil B increased by 15.28% Pulse C by 5.25% Staple A by 12.98%. Sweetener D by 19.41%.

**O – Observation:** Sweetener D experienced the first-to-last percentage increase while Pulse C experienced the smallest increase.

**O – Observation:** There is a difference between the mean and median prices of Staple A and Sweetener D when their flagged observations are included. Staple A has a mean of PKR 160.89 and a median of PKR 112.50 while Sweetener D has a mean of PKR 576.81 and a median of PKR 167.75.

**O – Observation:** When the flagged observations are excluded the mean decreases significantly for both items while their medians change little.

**E – Explanation:** The high flagged prices may explain the difference between the mean and median for Staple A and Sweetener D. This is supported by comparing the statistical results with and without the flagged observations.

**E – Explanation:** The differences in price increases between the four items may be related to changing market conditions, supply and demand or production costs. However the available dataset does not provide evidence to confirm these explanations.

**C – Causal Claim:** The dataset does not establish that any particular government policy, transportation cost, supplier decision or external factor caused the price increases. Additional evidence would be required to establish a relationship.

## 5.

The analysis shows that all four items experienced an increase in their to-last recorded prices. Sweetener D had the percentage increase while Pulse C had the smallest. The comparison between mean and median also demonstrates that high values can significantly affect the mean. The median provides a stable representation of the central price for Staple A and Sweetener D, in this dataset.

Overall this assignment demonstrates the importance of using both mean and median when analysing prices. It also highlights the need to identify observations and distinguish between direct observations, possible explanations and causal claims.


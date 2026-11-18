Assignment 3 – Two Averages, One Argument

3_log_reflection.md

1. AI Usage Log

Date: 18 November 2026

Task: Analysing grocery price data and understanding the effect of values on mean and median.

AI Tool Used: ChatGPT.

I used ChatGPT to help analyse grocery price data and understand the calculations required for the assignment. I asked ChatGPT to calculate the median, mode and first-to-last percentage change for Oil B, Pulse C, Staple A and Sweetener D. I also asked it to compare the mean and median with and without the flagged values.

ChatGPT identified two high prices in the dataset: PKR 1,250 for Staple A and PKR 9,999 for Sweetener D. It explained that unusually high values can increase the mean significantly while having a much smaller effect on the median.

I used Python and Pandas in Jupyter Notebook to check the calculations and examine the flagged observations. I accepted the explanation about the effect of values because the comparison between the mean and median demonstrated this relationship. However I treated the results as provisional until they could be checked against the notebook outputs.

 2. AI Interpretation Audit

I reviewed the interpretations provided by ChatGPT. Considered whether they were supported by the dataset. The claim that Sweetener D had the first-to-last percentage increase and Pulse C had the smallest increase could be verified using the percentage change calculations in Python. Therefore these claims were classified as green.

The claim that extreme values increase the mean significantly was also classified as green because the comparison of mean and median with and without observations demonstrated this effect.

ChatGPT also suggested that higher transportation costs could explain the increase in grocery prices. I classified this as amber because it is an explanation but the dataset does not contain information about transportation costs. Similarly the suggestion that government policies caused grocery prices to increase was classified as red because the dataset does not provide evidence to establish this causal relationship.

This exercise helped me understand that statistical observations should be separated from assumptions and unsupported causal explanations.

3. Confused Classmate Conversation

I considered a situation in which a classmate believed that the mean is always the measure of a typical price. I explained that although the mean considers every observation it can be heavily influenced by high or low values.

For example if five prices are 10, 12 13, 15 and 100 the mean is 30 while the median is 13. Most of the prices are close to 13 which means the median provides a representation of the typical price in this example.

My classmate then asked whether the median is always better than the mean. I explained that this is not necessarily true. Both measures are useful depending on the distribution of the data. The mean is useful when the data does not contain observations while the median is particularly helpful when unusual values are present.

I connected this explanation to our assignment by discussing Staple A and Sweetener D. Their high flagged prices increased their means significantly while their medians remained relatively stable. This demonstrated why both measures should be considered when analysing prices.

4. Reflection

While reviewing my analysis I realised that some explanations could go beyond what the data showed. For example suggesting that transportation costs or government policies caused grocery prices to increase would be making a claim without sufficient evidence.

The dataset only provides information about recorded prices. Does not explain why those prices changed. Therefore these factors should only be presented as explanations rather than confirmed causes.

I also learned that the mean can be affected significantly by values whereas the median is generally more resistant to them. The comparison of Staple A and Sweetener D helped me understand why relying on one average can sometimes give a misleading impression of the data.

Overall this assignment helped me understand the importance of checking calculations questioning AI-generated explanations and distinguishing between observations, possible explanations and causal claims.

5. Final Learning

This assignment taught me that AI can be useful for interpreting data and explaining concepts but its calculations and claims should always be checked. I should not accept every AI-generated answer without verification. Using both mean and median provides an understanding of price data particularly when unusual observations are present. I also learned that responsible data analysis requires evidence-based conclusions than assumptions, about why something happened.

# AI Interpretation Audit

| No. | Claim made by AI | Colour | How checked / reason |
|---:|---|---|---|
| 1 | Mean and median represent measures of central tendency and indicate typical price levels. | Green | This is the definition of mean and median. |
| 2 | Oil B has the highest typical price level, followed by Pulse C, Sweetener D and Staple A. | Green | Compared the mean and median values of all four items in my statistics table. |
| 3 | The median is the middle value when observations are arranged from lowest to highest. | Green | Checked against the definition of median. |
| 4 | 50% of observations are at or below the median and 50% are at or above it. | Green | This follows from the definition of the median, allowing for tied values. |
| 5 | The mean and median differ by less than Rs. 1 for every item. | Green | Subtracted the mean from the median for each item. |
| 6 | Staple A's mean is Rs. 0.58 lower than its median. | Green | Calculated 111.75 − 111.17 = 0.58. |
| 7 | Oil B's mean is Rs. 0.83 higher than its median. | Green | Calculated 324.83 − 324.00 = 0.83. |
| 8 | Pulse C's mean is Rs. 0.08 lower than its median. | Green | Calculated 206.00 − 205.92 = 0.08. |
| 9 | Sweetener D's mean and median are identical, with a difference of zero. | Green | Both values in my table are Rs. 166.75. |
| 10 | Close mean and median values suggest that the distributions are roughly symmetric. | Amber | This is a possible interpretation, but mean and median alone cannot establish the shape of a distribution. |
| 11 | Close mean and median values suggest that extreme outliers are not strongly pulling the average away from the middle. | Amber | This may be possible, but the actual distribution and individual observations need to be examined. |
| 12 | Staple A and Pulse C may have slight left (negative) skewness. | Amber | Their means are slightly lower than their medians, but this alone does not prove left skewness. |
| 13 | Oil B may have slight right (positive) skewness. | Amber | Its mean is slightly higher than its median, but this alone does not prove right skewness. |
| 14 | Equal mean and median are consistent with a perfectly symmetric distribution for Sweetener D. | Amber | Equal values can occur in a symmetric distribution, but they do not establish perfect symmetry. |
| 15 | All four items recorded positive first-to-last percentage changes. | Green | Checked the four positive percentage changes in my statistics table. |
| 16 | Sweetener D had the largest percentage increase at 19.41%. | Green | Compared the four percentage changes in my table. |
| 17 | Staple A had the second-largest percentage increase at 15.28%. | Green | Compared the four percentage changes in my table. |
| 18 | Pulse C increased by 12.98%. | Green | This matches my calculated percentage change. |
| 19 | Oil B had the smallest percentage increase at 3.69%. | Green | Compared the four percentage changes in my table. |
| 20 | A positive first-to-last change could result from steady growth, a sudden jump or fluctuations. | Amber | These are possible explanations, but the first-to-last percentage change alone cannot identify the actual pattern. |
| 21 | Oil B had the highest typical price but the lowest percentage increase. | Green | Compared its mean, median and percentage change with those of the other items. |
| 22 | Staple A and Sweetener D had the two largest percentage increases. | Green | Compared the percentage changes in my table. |
| 23 | Sweetener D had the largest percentage increase while its mean and median were identical. | Green | Both facts can be verified from my statistics table. |
| 24 | A small percentage increase on an expensive item may represent a noticeable rupee increase. | Amber | This is a possible mathematical explanation, but actual starting and ending prices are needed to compare rupee increases. |
| 25 | Sweetener D's equal mean and median suggest a steady, linear upward trend. | Red | Equal mean and median do not prove that prices increased steadily or followed a linear trend. |
| 26 | Oil B was consistently the most expensive item, while Staple A was consistently the least expensive. | Red | The mean and median show typical price levels, not the price ranking at every observation. |
| 27 | Every item ended at a higher price than where it started. | Green | Positive first-to-last percentage changes indicate that the ending prices were higher than the starting prices. |
| 28 | Close mean and median values prove that extreme price spikes or crashes did not distort the data. | Red | Similar mean and median values do not prove that extreme observations were absent or had no influence. |
| 29 | Sweetener D's percentage increase was more than five times Oil B's percentage increase. | Green | Divided 19.41 by 3.69, obtaining approximately 5.26. |
| 30 | Price inflation across the four-item basket was uneven. | Amber | The percentage changes differ, but measuring overall basket inflation requires an appropriate price index and expenditure weights. |
| 31 | The summary statistics cannot identify the causes of price increases. | Green | The dataset does not contain information that establishes why prices changed. |
| 32 | First-to-last percentage change does not show what happened between the first and last observations. | Green | It compares only the first and last prices. |
| 33 | The summary statistics alone do not reveal the sample size, time interval or dates covered. | Green | These details must be checked separately in the dataset. |
| 34 | Exact rupee changes cannot be verified using only the mean, median and percentage change. | Green | Exact starting and ending prices are needed to calculate the rupee difference. |
| 35 | Household budget impacts cannot be established without expenditure weights and quantities purchased. | Green | The dataset does not provide household expenditure or purchasing information. |
| 36 | Historical descriptive statistics cannot prove that prices will continue increasing in the future. | Green | Past descriptive statistics do not establish future price movements. |



Me: I am completing an economics assignment about mean and median using a teaching dataset of prices.
I want you to act as a confused classmate who strongly believes that the mean is always the best measure of a typical price.
Your job is to:
1. Ask me questions one at a time.
2. Challenge my explanations by repeatedly asking "But why?"
3. Question why the median might sometimes be more useful than the mean.
4. Use simple examples involving prices, including an unusually high price.
5. Do not explain the answers to me immediately. Let me try to explain first.
6. Continue asking questions until I demonstrate that I understand the difference between mean and median and why an unusually high observation can affect the mean more than the median.

AI: Hey, thanks for helping me look over this dataset! Honestly, I'm a bit stuck on why we're even bothering with the median column.
If we want to find the "typical" price of an item, isn't the mean just the obvious, best choice? You literally add everything up and divide by the total, so it includes every single price in the dataset. Why wouldn't that always be the best way to measure it?

Me: Mean cannot always be the best representative of the data because there may be outlier values as well. For example, if there are consistent values for a certain commodity around 100, for example, it has 100, 112, 110, 121, 117, and then there is this one outlier value of 500. That one value completely changes the data set. And if we find mean while keeping the outlier value in the calculation, it will get a higher mean than usual. But if we find median in there, 500 will automatically be excluded and we will get a more representative value for all of the data.

AI: Okay, I see the math—with that 500 in there, the average jumps way up to 160, while the middle number stays around 114.5.
But why is that a bad thing? That 500 is a real price someone actually charged in the dataset, right? Why shouldn't it pull the typical price up if it really happened?

Me: It is surely an actual value and it is not an error or it is not an invalid value, but it is an unusual value that can change the rest of the data set. When someone asks us about an average value, we wouldn't add 500 because that would not make the value more average. If we exclude 500 or if we take median, that shows us more of a typical value for that commodity rather than showing us an unusual value just because we had one outlier value.

AI: Hmm, okay, I get that 500 is unusual, and 160 isn't actually close to what most people paid.
But why does the median stay at 114.5 when the mean jumps all the way to 160? Like, mathematically, why didn't that 500 pull the median up too?

Me: The mean uses the formula of sum of all values divided by the number of observations, in which we will obviously add 500 as well. That changes the value. But for median, for grouped data, we use the formula of n + 1 / 2 number of position. So that tells us the middle value, the middle position. And then when we count back to that middle position, we find the data from the middle, which is the best representative value for a typical value for that commodity. And median does not add the outlier value to it, that is why.

AI: Oh, that makes total sense! Because the mean actually adds up the *values* of every single price, that huge 500 goes straight into the numerator and drags the whole average up. Whereas the median just lines everything up in order and looks at the *position*—so whether the highest price is 130, 500, or even 5,000, the middle spot doesn't budge!
I finally get why the median is way better when a dataset has crazy outliers or skewed prices. Thanks for walking me through that—I feel way more confident writing up the analysis for this assignment now!


Reflection:
Looking back at my first draft, I realise that I may have interpreted price increases as evidence of a broader inflation problem without sufficient evidence. The dataset only contains illustrative teaching prices and does not explain why prices changed.
I also needed to be careful about describing price increases as steady because first-to-last percentage change only compares the starting and ending prices. Similarly, mean and median cannot tell us whether goods are affordable for households.
This exercise taught me to separate what the data directly shows from what I assume or interpret. I should avoid making claims that the available data cannot support.
 

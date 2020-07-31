1.Question 1
A University admissions test has a Gaussian distribution of test scores with a mean of 500 and standard deviation of 100. One student out-performed 97.4% of all test takers.

What was their test score (rounded to the nearest whole number)?

Hint: Refer to the Excel NormSFunctions Spreadsheet.

Excel NormS Functions Spreadsheet.xlsx
1 / 1 point


972


306


694 *


502

Correct
Z-score = NormSInv(.973) = 1.9431

500 + (100*1.9431) = 694.3


2.Question 2
A carefully machined wire comes off an assembly line within a certain tolerance. Its target diameter is 100 microns, and the wires produced have a uniform distribution of diameters, between -11 microns and +29 microns from the target.

What is the mean and standard deviation of the uniform distribution of wire diameters?

Hint: Use the CLT and Excel Rand() Spreadsheet.

CLT and Excel Rand.xlsx
1 / 1 point


Mean = 120 microns, Standard Deviation = 11.547 microns.


Mean = 109 microns, Standard Deviation = 11.547 microns. *


Mean = 120 microns, Standard Deviation = .86 microns.


Mean = 109 microns Standard Deviation = 133.33 microns.

Correct
In the CLT and Excel Rand Spreadsheet, use cell C2 for a = 89 and cell E2 for b = 129. The formula for the standard deviation of a uniform distribution is given in cell N3.


3.Question 3
A population of people suffering from Tachycardia (occasional rapid heart rate), agrees to test a new medicine that is supposed to lower heart rate. In the population being studied, before taking any medicine the mean heart rate was 120 beats per minute, with standard deviation = 15 beats per minute.

After being given the medicine, a sample of 45 people had an average heart rate of 112 beats per minute. What is the probability that this much variation from the mean could have occurred by chance alone?

Hint: Use the Typical Problem with NormSDist Spreadsheet.

Typical Problem_ NormSDist .xlsx
1 / 1 point


99.9827%


.0173% *


29.690%


1.73%

Correct
The distribution of sample means has an expected mean of 120 and standard deviation of 15/sqrt(45) = 2.236. The z-score of the sample average of 112 is (112-120)/2.236 = -3.577. A z-Score this small or smaller has a probability of occurring by chance of only

( 1 –NormSDist(3.577)) = .0173% .
4.Question 4
Two stocks have the following expected annual returns:

Oil stock – expected return = 9% with standard deviation = 13%

IT stock – expected return = 14% with standard deviation = 25% 

The Stocks prices have a small negative correlation: R = -.22.

What is the Covariance of the two stocks?

Hint: Use the Algebra with Gaussians Spreadsheet.

Algebra with Gaussians.xlsx
1 / 1 point


-.00219


-.00715 *


-.00573


-.0286

Correct


5.Question 5
Two stocks have the following expected annual returns:

Oil stock – expected return = 9% with standard deviation = 13%

IT stock – expected return = 14% with standard deviation = 25%

The Stocks prices have a small negative correlation: R = -.22.

Assume return data for the two stocks is standardized so that each is represented as having mean 0 and standard deviation 1. Oil is plotted against IT on the (x,y) axis.

What is the covariance?

Hint: Use the Standardization Spreadsheet.

Standardization Spreadsheet.xlsx
1 / 1 point


-.22 *


-.00573


0


-1

Correct
Standardization changes covariance to equal correlation. Standardization leaves correlation unchanged. See the Standardization Spreadsheet.


6.Question 6
Two stocks have the following expected annual returns:

Oil stock – expected return = 9% with standard deviation = 13%

IT stock – expected return = 14% with standard deviation = 25%

The Stocks prices have a small negative correlation: R = -.22.

What is the standard deviation of a portfolio consisting of 70% Oil and 30% IT?

Hint: Use either the Algebra with Gaussians or the Markowitz Portfolio Optimization Spreadsheet.

Algebra with Gaussians.xlsx
Markowitz Portfolio Optimization.xlsx
1 / 1 point


12.68%


11.79%


17.93%


10.44% *

Correct
Correct. Use the Markowitz Portfolio Optimization Spreadsheet. Enter Oil Expected return in Cell C6, Oil standard deviation in cell C7, IT expected return in Cell D6, IT standard deviation in Cell D7, Oil weighting in Cell C9 and IT weighting in Cell D9. Results in Cell E12.


7.Question 7
Two stocks have the following expected annual returns:

Oil stock – expected return = 9% with standard deviation = 13%

IT stock – expected return = 14% with standard deviation = 25%

The Stocks prices have a small negative correlation: R = -.22.

Use MS Solver and the Markowitz Portfolio Optimization Spreadsheet to Find the weighted portfolio of the two stocks with lowest volatility.

Solver Add-In.xlsx
Markowitz Portfolio Optimization.xlsx
What is the minimum volatility?
1 / 1 point


9.5%


10.36% *


10.43%


11.58%

Correct
The minimum-volatility-portfolio is weighted at .74 Oil and .26 IT.


8.Question 8
You are a data-analyst for a restaurant chain and are asked to forecast first-year revenues from new store locations. You use census tract data to develop a linear model.

Your first model has a standard deviation of model error of $25,000 at a correlation of R = .30. Your boss asks you to keep working on improving the model until the new standard deviation of model error is $15,000 or less.

What positive correlation R would you need to have a model error of $15,000?

(Note: you can answer this question by making small additions to the Correlation and Model Error spreadsheet).

Correlation and Model Error.xlsx
1 / 1 point


R = .500


R = .428


R = .572


R = .8200 *

Correct
The model error of standardized variables at R = .30 is .9539.

Applying algebra, to obtain the required model error, you need a model error on standardized variables of ($15,000/$25,000)(.9539) = (.6)(.9539) = .57236.

By definition of model error for standardized variables, .57236 = Sqrt(1-R^2). Applying algebra and solving for R, R = sqrt(1 - (.57236)^2) = .8200.


9.Question 9
An automobile parts manufacturer uses a linear regression model to forecast the dollar value of the next years’ orders from current customers as a function of a weighted sum of their past-years’ orders. The model error is assumed Gaussian with standard deviation of $130,000.

If the correlation is R = .33, and the point forecast orders $5.1 million, what is the probability that the customer will order more than $5.3 million?

Hint: Use the Typical Problem with NormSDist Spreadsheet.

Typical Problem_ NormSDist .xlsx
1 / 1 point


6.2% *


4.3%


93.8%


12.4%

Correct
Convert $5.3 million to a z-score. The z-Score is (5.3-5.1)/.13 = (.2/.13) = 1.538.

Input the z-score in the Excel formula (1 - Normsdist(z)) to get the probability of a score at least that high. The probability is 1- 93.8% = 6.2%.
10.Question 10
An automobile parts manufacturer uses a linear regression model to forecast the dollar value of the next years’ orders from current customers as a function of a weighted sum of that customer’s past-years orders. The linear correlation is R = .33.

After standardizing the x and y data, what portion of the uncertainty about a customer’s order size is eliminated by their historical data combined with the model?

Hint: Use the Correlation and P.I.G. Spreadsheet.

Correlation and P.I.G..xlsx
1 / 1 point


4.2% *


3.5%


4.5%


5.2%


11.Question 11
A restaurant offers different dinner “specials” each weeknight. The mean cash register receipt per table on Wednesdays is $75.25 with standard deviation of $13.50. The restaurant experiments one Wednesday with changing the “special” from blue fish to lobster. The average amount spent by 85 customers is $77.20.

How probable is it that Wednesday receipts are better than average by chance alone?

Hint: Use the Typical Problem with NormSDist Spreadsheet.

Typical Problem_ NormSDist .xlsx
1 / 1 point


8.30%


9.15% *


9.05%


90.85%

Correct
The Z-score for Wednesdays is (77.20 – 75.25)/ 13.50/(sqrt(85) = 1.33. The probability that this much improvement would be due to chance alone, not the change of special, is (1 - NormSDist(1.33)).

Note that due to the Central Limit Theorem, even though the receipts may not have a Gaussian distribution, the sample means will have a Gaussian distribution so that use of the NormSDist function is appropriate.


12.Question 12
Your company currently has no way to predict how long visitors will spend on the Company’s web site. All it known is the average time spent is 55 seconds, with an approximately Gaussian distribution and standard deviation of 9 seconds. It would be possible, after investing some time and money in analytics tools, to gather and analyzing information about visitors and build a linear predictive model with a standard deviation of model error of 4 seconds.

How much would the P.I. G. of that model be?

Hint: Use the Correlation and P.I.G. Spreadsheet


How to use the AUC calculator.pdf
PDF File

1 / 1 point


48.2%


53.3%


61.5%


57.2% *

Correct
With no model, the correlation R = 0 and the “model error” is equal to the standard deviation of Y = 9 seconds. Standardized, the model error when R = 0 is equal to 1. Reducing the model error to 4 seconds is equivalent to reducing the standardized model error to 4/9 = .4444 Since Sqrt(1-R^2) = .4444, R^2 = 1- .4444^2 = .8958.

This corresponds to a P.I.G. of 57.2%.

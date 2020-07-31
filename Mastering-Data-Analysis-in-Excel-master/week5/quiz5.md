
1.Question 1
Keep the 125 outcomes in the Histogram Spreadsheet unchanged. Change the bin ranges so that bin 1 is [-3, -1), bin 2 is [-1,1) bin 3 is [1, 3).

Histograms Spreadsheet.xlsx
What is the approximate probability that a new outcome will fall within bin 1?
1 / 1 point


.4


5%


5


4% *

Correct
The approximate probability is (1+4)/125.
2.Question 2
Use the Excel Probability Functions Spreadsheet.

Excel_Probability_Functions.xlsx
Assume a continuous uniform probability distribution over the range [47, 51.5].

What is the skewness of the probability distribution?
1 / 1 point


49.25


1.69


2.17


0 *

Correct
The skewness of all uniform distributions is zero.

3.Question 3
Use the Excel Probability FunctionsSpreadsheet, provided in question #2.

Assume a continuous uniform probability distribution over the range [-12, 20]

What is the entropy of this distribution?
1 / 1 point


3 bits


5 bits *


4 bits


6 bits

Correct
The entropy is log2(20 –(-12) = log2(32).

4.Question 4
Use the Excel Probability Functions Spreadsheet that was previously provided.

Assume a Gaussian Probability function with mean = 3 and

standard deviation =4.

What is the value of f(x) at f(3.5)?
1 / 1 point


4.05


.352


.099 *


.550

Correct
This is Excel normdist(3.5, 3,4, false)


5.Question 5
Use the Excel Probability Functions Spreadsheet previously provided in this quiz.

Assume a Gaussian Probability Distribution with mean = 3 and standard deviation = 4.

What is the cumulative distribution at x = 7?
1 / 1 point


.841 *


.060


.960


1.00


6.Question 6
Use the AUC Calculator Spreadsheet.

AUC_Calculator and Review of AUC Curve.xlsx
If the “modification factor” in the original example given in the AUC Calculator Spreadsheet is changed from -1 to -2, what is the change in the actual Area Under the ROC Curve?
1 / 1 point


The area increases


The area decreases 


No change *

Correct
The spreadsheet estimate changes slightly --- from .64 [.6377] to .64 [.6388] – this change is due to the version with -1 using more bins on the data, making it slightly more accurate.


7.Question 7
Use the AUC Calculator Spreadsheet provided in question #6.

If the “modification factor” in the original example given in the AUC Calculator Spreadsheet is changed from -1 to -2, what is the threshold (row 10) that results in the lowest cost per event?
0 / 1 point


1.3 xxxxxxxxxxxx


.9 ?


.45 ?


3.5 ?

Incorrect
Changing the scale does not change the minimum cost per event, which remains $975. However, it will change the value of the threshold above which all results are classified positive.


8.Question 8
Refer to the AUC Calculator Spreadsheet previously provided.

Assume a binary classification model is trained on 200 ordered pairs of scores and outcomes and has an AUC of .91 on this “training set.” The same model, on 5,000 new scores and outcomes, has an AUC of .5.

Which statement is most likely to be correct?
1 / 1 point


The original model is expected to perform worse on test set data and is functioning acceptably.


The original model identified signal as noise and has no predictive value on new data. *


The model overfit the training set data and will need to be improved to work better on the new data.

Correct
The model’s AUC of .5 on the much larger set of 5,000 is no better than assigning binary classification purely at random. It appears likely that the model has no predictive value at all.
9.Question 9
Refer to the Excel Linest Function Spreadsheet.

Excel Linest Function.xlsx
If a multivariate linear regression gives a weight beta(1) of 0.4 on x(1) = “age in years,” and a new input x(7) of “age in months” is added to the regression data, which of the following statements is false?
1 / 1 point


Using Excel linest, and including x(1) and x(7) data, the new beta(7) on the age in months will be 0.


If the x(1) data are removed, the new beta(7) on the new x(7) data will be 0.4. *


If the x(1) data are removed, the new beta(7) on the new x(7) data will be .033

Correct
This statement is false. Because the x(1) and x(7) data are collinear, the model R^2 is unchanged, but because x(7) has 12 times the standard deviation of x(1), the correct coefficient will be 1/12 as much, or .0333.
10.Question 10
Use the Excel Linest Function Spreadsheet that was provided in question #9.

What is the Correlation, R for the linear regression shown in the example?
1 / 1 point


.606


.367


.778 or - .778 *

Correct
We know R is the square root of R^2 [Cell B42] but don’t immediately know whether the correlation is positive or negative.

java c
Math Stats practice problems for final exam 
December 15, 2024 
Problem 1
Suppose X0 = 0 and X1, . . . , Xn are given by the following Gaussian autoregressive process, i.e., the AR(1) model:
Xi = θXi−1 + ϵi
where θ ∈ [0, 1) is unknown, and the errors ϵi ∼ N(0, σ2) i.i.d. with σ2 > 0 known.
(a) Log-likelihood Function 

(b) MLE of θ

(c) Least Squares Estimate of θ

Alternatively, letting:

Problem 2 
Suppose you have a true model y = αeβx+ϵ, where ϵ ∼ N(0, σ2), and the following data:

(a) Least Squares Estimates of α and β
Transform. the data to get a linear model:
ln(y) = ln(αeβx) = ln(α) + βx + ϵ
Let z = ln(y), γ = ln(α).

The estimated model is:

(b) 95% Confidence Interval for β

Problem 3 
In a sociological study, 784 high school students were asked which two of ten given attributes were most desirable in their fathers. The following table summarizes the number of male and female students who included “being a college graduate” among the two. Did male and female students value this attribute differently?

Test for Homogeneity 
Null hypothesis:
H0 : pMale, included = pFemale, included, pMale, mitted = pFemale, omitted
Test statistic:

The number of degrees of freedom is (2-1)(2-1)=1. With α = 0.05 and 1 degree of freedom, the rejection region for a χ21test is X2 > 3.841. We reject H0 at α = 0.05 and even at α = 0.005.
Problem 4 
A survey was conducted to determine whether there is an association between age and preference for a type of movie. The responses are summarized in the following contingency table. Are age and movie 代 写Math Stats practice problems for final examMatlab
代做程序编程语言preference related?

Test for Independence 
• Null hypothesis (H0): Gender and movie preference are independent.
• Alternative hypothesis (H1): Gender and movie preference are not independent.
The expected count for each cell are

The Pearson χ2test statistic is

The degrees of freedom for this test are (2-1)(3-1)=2. Using a significance level of α = 0.05, the critical value from the chi-squared distribution table is 5.99.
Since X2 ≈ 10 > 5.99, we would reject the null hypothesis.
Problem 5 
Independent samples have been collected from two Gaussian distributions with the same variance. Use a t-test to test whether the means of the two distributions are equal. The data are as follows:

The sample sizes are n1 = 25 and n2 = 30.
(a) Hypotheses 
• Null hypothesis: H0 : µ1 = µ2
• Alternative hypothesis: H1 : µ1 ≠ µ2
(b) Test Statistic 

where:

(c) Rejection region 
The degrees of freedom for a t test are n1 + n2 − 2 = 25 + 30 − 2 = 53.
Using a significance level of α = 0.05, the critical value for |T| with df = 53 is bigger than ±2. So we cannot reject the null hypothesis at this significance level.
Problem 6 
A dataset contains the following values:
5, 7, 8, 12, 15, 18, 20, 21, 23, 25, 28, 30.
Find the median and interquartile range.
• First Quartile (Q1): Q1 = Median of the first half = Median of {5, 7, 8, 12, 15, 18} = 10
• Median (Q2): Q2 = Median of all data = 19
• Third Quartile (Q3): Q3 = Median of the second half = Median of {20, 21, 23, 25, 28, 30} = 24
So the IQR is 24 − 10 = 14.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

# Basic-Statistics-Level-2-SET-4
Basic Statistics Level 2 SET 4

CBA: Practice Problem Set 2

# Topics: Sampling Distributions and Central Limit Theorem


1.Examine the following normal Quantile plots carefully. Which of these plots indicates that the data …

I.Are nearly normal?  ANS : C

II.Have a bimodal distribution? (One way to recognize a bimodal shape is a “gap” in the spacing of adjacent data values.) ANS : B

III.Are skewed (i.e. not symmetric) ?  ANS : A, C , D

IV.Have outliers on both sides of the center?  ANS : A F




# 2.For each of the following statements, indicate whether it is True/False. If false, explain why.

The manager of a warehouse monitors the volume of shipments made by the delivery team. The automated tracking system tracks every package as it moves through the facility. A sample of 25 packages is selected and weighed every day. Based on current contracts with customers, the weights should have μ = 22 lbs. and σ = 5 lbs.

(i)Before using a normal model for the sampling distribution of the average package weights, the manager must confirm that weights of individual packages are normally distributed.  
ANS : TRUE

(ii)The standard error of the daily average SE() = 1.
ANS : TRUE 

 As we know  
SE = σ / √n
n = (σ / SE)^2
n = (5 / 1)^2
n = 25   which is true. Thus   SE(X) = 1.

 


# 3.Auditors at a small community bank randomly sample 100 withdrawal transactions made during the week at an ATM machine located near the bank’s main branch. Over the past 2 years, the average withdrawal amount has been $50 with a standard deviation of $40. Since audit investigations are typically expensive, the auditors decide to not initiate further investigations if the mean transaction amount of the sample is between $45 and $55. What is the probability that in any given week, there will be an investigation?

A.1.25%
B.2.5%
C.10.55%
D.21.1%
E.50%

ANS :  Option D

n = 100
μ =50 
σ = 40
P(45<= X <= 55) = ?
= P((45 - μ) / (σ / √n) <= X <=  (55 - μ) / (σ / √n))
= P((45 - 50 / (40/ √100) <= Z <=  (55 - 50) / (40/ √100))
=P( -1.25  <= Z <=   1.25)
=P( Z <=  1.25 )  -   P(  Z   <= -1.25 )
=0.8943502263331446     -    0.10564977366685535
= 0.7887004526662893

Probability of that the auditors decide to not initiate further investigations = P(45<= X <= 55) =0.7887
 Probability that in any given week, there will be an investigation =  1   -   P(45<= X <= 55)

 =  1   -   P(45<= X <= 55)
 =  1   -   0.7887
=0.2113
=21 % 
Option D


# 4.The auditors from the above example would like to maintain the probability of investigation to 5%. Which of the following represents the minimum number transactions that they should sample if they do not want to change the thresholds of 45 and 55? Assume that the sample statistics remain unchanged.

A.144
B.150
C.196
D.250
E.Not enough information

ANS : 
Not enough information.


# 5.An educational startup that helps MBA aspirants write their essays is targeting individuals who have taken GMAT in 2012 and have expressed interest in applying to FT top 20 b-schools. There are 40000 such individuals with an average GMAT score of 720 and a standard deviation of 120. The scores are distributed between 650 and 790 with a very long and thin tail towards the higher end resulting in substantial skewness. Which of the following is likely to be true for randomly chosen samples of aspirants?

A.The standard deviation of the scores within any sample will be 120.
B.The standard deviation of the mean of across several samples will be 120.
C.The mean score in any sample will be 720.
D.The average of the mean across several samples will be 720.
E.The standard deviation of the mean across several samples will be 0.60

ANS : 
A. The standard deviation of the scores within any sample will be 120.
This statement is true. Since the samples are drawn from the same population with a standard deviation of 120, any individual sample taken will inherit the same standard deviation.

B. The standard deviation of the mean of across several samples will be 120.
This statement is false. The standard deviation of the mean across several samples, often called the standard error (SE), is given by:

SE = population standard deviation / √(sample size)

In this case, the population standard deviation is 120, but the sample size (number of individuals in each sample) is not provided. Without knowing the sample size, we cannot calculate the standard deviation of the mean across several samples.

C. The mean score in any sample will be 720.
This statement is not necessarily true. While the population mean is given as 720, the mean score in any specific sample may vary due to random sampling. The sample mean will follow a sampling distribution, and it is expected to be close to the population mean, but it may not always be exactly 720.

D. The average of the mean across several samples will be 720.
This statement is likely to be true. The average of the means across several samples, also known as the expected value of the sample means, is equal to the population mean (μ). In this case, the population mean is 720, so the average of the means across several samples is also expected to be approximately 720.

E. The standard deviation of the mean across several samples will be 0.60.
This statement is false. The standard deviation of the mean across several samples, as mentioned in option B, depends on the population standard deviation and the sample size. It is not 0.60, and we cannot determine its exact value without knowing the sample size.

So, the likely true statements are:

A. The standard deviation of the scores within any sample will be 120.
D. The average of the mean across several samples will be 720.

 answer : A and D.

** Design an A/B testing steps **
measure the impact that changes have on your metrics
1 Define the goal and metrics
2 Choose the significance level (alpha), statistical power (1-beta), MDE  
sample size & duration 
(and practical significance level you really want to launch the change if the test is statistically significant) 
3 Create a variation and randomly split users into treatment/control group
4 Analyze the results

** How to calculate sample size? **
Baseline Conversion Rate (control group’s expected conversion rate)
Minimum Detectable Effect (min relative change in conversion rate) (the smallest effect that will be detected (1-ß% of the time))
Statistical Significance (% of the time a difference will be detected if it does not exist)
Statistical Power (1-ß%) (% of the time the MDE will be detected if it exists) 
Are we confident that the change of our test is meaningful enough to generate the minimum of x% uplift/off. 

** Not significant? **
1 What does “significant” mean in an A/B test? 
The probability you are willing to accept for incorrectly concluding that your improvement was successful, even though it was not. 
Theoretically, we use 95%, which means we stand a 5% chance of thinking our change improved conversions, when it actually didn’t. 
2 Recheck the setup: sampling data  random? Tracking tools
3 Think about how certain you want to be? In practice, 95%  90%? 
4 Run for a longer time
5 Cost: put more weight to the winner version, use a small portion to test 
6 It can be not significant. Problem: whether to launch it >> cost following test

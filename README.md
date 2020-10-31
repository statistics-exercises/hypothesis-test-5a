# Type I and type II errors 

You are now hopefully understanding how the workflow illustrated in the flow chart below is used when we perform a hypothesis test:

I thus want to spend some time using conditional probability to think about what we are doing when we perform a hypothesis test.  For the simple hypothesis tests that we have done thus far we essentially have two Bernoulli random variables:

H - is one if our null hypothesis is true
C - is one if our statistic falls within the critical region  

With these random variables defined, we can then note that:

P(C=0 | H=1 ) is the conditional probability that there is insufficient evidence to reject the null hypothesis given that the null hypothesis is true.  In other words, this is the conditional probability that our statistic falls outside the critical region given the null hypothesis is true.
P(C=1 | H=0 ) is the conditional probability that there the null hypothesis is rejected in favour of the alternative hypothesis given that the null hypothesis is false.  In other words, this is the conditional probability that our statistic falls within the critical region given the null hypothesis is true.

Notice, that we have no way of determining the absolute probabilities P(H=1) and P(H=0) and that we have not yet considered all the elements in the sample space for this experiment, which are enumerated in the diagram below:

To be clear, there is no way of detecting the two additional possibilities that are identified above.  In other words, you will only ever reject or not reject the null hypothesis.  You need to be aware, however, that these two types of error exist and you should seek to make the probability for type I or type II errors as low as possible.

We have already seen how you can control the probability that one of the two types of error occurs by setting the significance level of the test.  To complete this task you must, therefore, complete the sentence that is printed out by writing whether the significance level is the probability for a type I or type II error. 

 

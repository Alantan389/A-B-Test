# A-B-Test
Analyze A/B Test

## For this project, you will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to  try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Your goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

## The data and the Jupyter Notebook, which are all of the files you need to complete the project, are provided for you in a downloadable zip file in the resources tab (as well as under "Supporting Materials" below). Note that portions of the notebook reference back to quizzes that are linked in this lesson to ensure you are on the right track




## Introduction
### A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these For this project, you will be working to understand the results of an A/B test run by an e-commerce website. Your goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Part II - A/B Test
### Notice that because of the time stamp associated with each event, you could technically run a hypothesis test continuously as each observation was observed. However, then the hard question is do you stop as soon as one page is considered significantly better than another or does it need to happen consistently for a certain amount of time? How long do you run to render a decision that neither page is better than another?These questions are the difficult parts associated with A/B tests in general.

#### 1. For now, consider you need to make the decision just based on all the data provided. If you want to assume that the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%, what should your null and alternative hypotheses be? You can state your hypothesis in terms of words or in terms of  𝑝𝑜𝑙𝑑 and  𝑝𝑛𝑒𝑤, which are the converted rates for the old and new pages.Put your answer here.

#### 2. Assume under the null hypothesis, 𝑝𝑛𝑒w and 𝑝𝑜𝑙𝑑
#### both have "true" success rates equal to the converted success rate regardless of page - that is 𝑝𝑛𝑒𝑤  and 𝑝𝑜𝑙𝑑  are equal. Furthermore, assume they are equal to the converted rate in ab_data.csv regardless of the page. Use a sample size for each page equal to the ones in ab_data.csv. Perform the sampling distribution for the difference in converted between the two pages over 10,000 iterations of calculating an estimate from the null. Use the cells below to provide the necessary parts of this simulation. If this doesn't make complete sense right now, don't worry - you are going to work through the problems below to complete this problem. You can use Quiz 5 in the classroom to make sure you are on the right track




### Part III - A regression approach
####  In this final part, you will see that the result you achieved in the A/B test in Part II above can also be achieved by performing regression.

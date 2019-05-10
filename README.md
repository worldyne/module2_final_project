# Module 2 Final Project: 
## Music Industry Analysis for Producers
[Industry Presentation Slides](https://docs.google.com/presentation/d/102XJzzTyGXwBd3s3WvtfC0avcXfHVpAipzfFGSrTGwo/edit?usp=sharing)  
We propose to assist music producers with their search for music production opportunities. Our slices of analysis focus on four hypothesis test questions:  

**(1)** Is there a statistically significant difference between the scores of albums in the jazz and metal genres?

**(2)** Will the label with the most artists have the highest album scores? 

**(3)** Is there a relationship between labels' genre diversity and labels' average score?  

**(4)** Are the average album scores of 2000-2009 different from those of 2010-2017??  

Our methodology consists of approaching each of these questions with a null hypothesis to reject and an alternative hypothesis to accept in the case of rejection. Our hypotheses for each question are as follows:  

* **(1)** H<sub>0</sub>: Jazz albums have the same average score as metal albums.  
* **(1)** H<sub>a</sub>: Jazz albums do not have the same average score as metal albums. 

* **(2)** H<sub>0</sub>: The label with the most artists signed will have the same average score as the label with the least artists signed.
* **(2)** H<sub>a</sub>: The label with the most artists signed will not have the same average score as the label with the least artists signed.

* **(3)** H<sub>0</sub>: The label with the most genre diversity will not have a higher average score than the label with the least genre diversity. 
* **(3)** H<sub>a</sub>: The label with the most genre diversity will have a higher average score than the label with the least genre diversity.  

* **(4)** H<sub>0</sub>: Average album scores are the same in both the 2000-2009 and 2010-2017 periods.  
* **(4)** H<sub>a</sub>: Average album scores have changed in the more recent period. 

During our statistical analysis, we found the following results:

**(1)** Jazz albums consistently earn scores slightly higher than metal albums. Using a two sample two-tailed z-test, with a significance level of 0.05 and a p-value of 7.5e-06, we reject our null hypothesis in favor of our alternative hypothesis. [Jazz-Metal Comaparison Notebook](jazz_vs_metal.ipynb)

**(2)** The label with the most artists signed does not perform significantly differently than labels with only one artist signed. Using a two-sided T-test, with a significance level of 0.05, and a p-value of 0.706, we fail to reject the null hypothesis in favor of the alternative hypothesis. [Artist Density Notebook](artist_density.ipynb)  

**(3)** The labels with the most genre diversity does have statistically significantly higher scores than the labels with the least genre diversity. Using a one sided T-test, with a significance level of 0.05, and a p-value of 0.015 we successfully reject the null hypothesis in favor of the alternative hypothesis with a statistical power of 58.7%. [Genre Diversity Notebook](label_genre.ipynb)  

**(4)** Albums released between 2000 and 2009 consistently earn scores slightly higher than albums released between 2010 and 2017. Using a two sample two-tailed z-test with a significance level of 0.05 and a p-value of 5.67e-08, we reject our null hypothesis in favor of our alternative hypothesis. [2000s-2010s Comparison Notebook](scores_over_time.ipynb)

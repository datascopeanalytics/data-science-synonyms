Because many data analysis methods developed relatively independently in statistics, machine learning, biology, physics, chemistry, economics, psychology, engineering fields, and more, there is a lot of overlapping terminology.

This is an an attempt to sort it out.

NOTES:
* When terms are "near synonyms," it seems like it is v. educational to describe the difference.
* It could be interesting to scrape departmental course web pages to see what type of terminology is used in different disciplines.
* Maybe instead of an "all-encompassing" thesaurus, could write blog posts that talk about specific interesting cases.
* Writing specific blog posts might be a good strategy even if there is a central tool.

I don't know the best way to structure this, for now I'm just going to jot some notes here.

* False Positive (ML) = Type 1 Error (Statistics)  
* False Negative (ML) = Type 2 Error (Statistics)  
* Recall (Information Science) = Sensitivity (Medicine/Biology) = True Positive Rate (ML)  
* Precision (Information Science) = Positive Predictive Value (ML)  
* True Negative Rate (ML) = Specificity (Medicine/Biology)  
* Gaussian Distribution (Physics) = Normal Distribution (Statistics) = Bell Curve (Colloquial)  
* Hypothesis (Statistics) = Model (ML)  
* Marginal Likelihood (Frequentist) = Evidence (Bayesian)  

In the above, Precision is not the same as the contrast between Accuracy and Precision in measurement:
* Precision (Engineering) = Variance (Statitics) = Reliability (Psychometrics) = Variable Error  
* Accuracy (Engineering) = Bias (Statistics) = Validity (Psychometrics) = Constant Error  

Lots of good ones for stochastics optimization problems!

* Rough Landscape (Stochastic Optimization) = NP Complete (Computer Science)  
* Cost Function (Economics) = Loss Function (Statistics) = Utility (Economics) = Objective Function (Operations Management) = Reward Function () = Energy (Physics/Chemistry) = Fitness (Evolutionary Biology)  
* Search Space () = Fitness Landscape (Biology)  
* Reinforcement Learning (ML) = Approximate Dynamic Programming (Operations Management)  

These are not *exactly* equivalent, but are extremely closely related. **NOTE: How could we illustrate that?**

* Structural Equation Model (Statistics)
* Latent Variable Model () = Hidden Variable Model (Physics) = Bayesian Network (ML)

* Independent Variables (Statistics) = Regressors (Statistics) = Explanatory Variables (Statistics) = Exogenous Variables (stats/statsmodels) = design (statistics) = Exposure Variable (Reliability Engineering) = Risk Factor (Medicine) = Feature (ML) = Input Variable (Engineering)  
* Dependent Variable (Statistics) = Response Variable (Statistics) = Regressand (Statistics) = Endogenous Variable (stats/statsmodels) = Outcome Variable (Medicine) = Output Variable (Engineering)  
* Hidden Variable () = Latent Variable () = Confounding Variable () --- seems like it's confounding when it's not there on purpose :)  
* Categorical Variable (Statistics) = Enumerated Type (Computer Science)  
  * Binary Variable () = Dichotomous Variable ()

Latent Variable Model [nice chart on Wikipedia](http://en.wikipedia.org/wiki/Latent_variable_model) is a superset of all these things:
* Factor Analysis ~= Principal Component Analysis --- seems like the difference between Factor Analysis and PCA is the assumptions made
* Latent Trait Analysis = Item Response Theory
* Latent Profile Analysis = Mixture Model
* Latent Class Analysis


[Difference of Gaussians](http://en.wikipedia.org/wiki/Difference_of_Gaussians) = Mexican Hat function (really old, awesome American physicists)
[Ricker Wavelet](http://en.wikipedia.org/wiki/Mexican_hat_wavelet) = Mexican hat wavelet/function (anyone else who says Mexican Hat function)
But seriously, people. Let's not bicker over slivers of differences. We aren't launching spacecraft, here. 
![](http://upload.wikimedia.org/wikipedia/commons/b/b5/DOG_vs_MHF.png)
credit: [JustinWick](http://en.wikipedia.org/wiki/User:JustinWick) - Originally uploaded to en.wikipedia. Generated using Mathematica 5.0.


# Topic-Modeling

**Disclaimer: Implementation Demo only, striking a balance between code optimization and readability**

* Variational Bayes (Hoffman et al. 2010)
  * Batch Variational Bayes
  * Online Variational Bayes (Stochastic)
  * Online Variational Bayes (Mini-batch)
 
 NB: 
  * Initialization of parameters and hyperparam setting are super important (cf. Asuncion et al. 2009, UAI paper).
  * For better topics, need more epochs, but difficult to do w/o having to further optimize, which affects readability.
  * Relative decrease in perplexity does not necessarily mean better topics.
  * Absolute value of perpexity does not mean much.

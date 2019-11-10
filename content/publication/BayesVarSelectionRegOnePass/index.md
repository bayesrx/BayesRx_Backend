+++
title = "Bayesian Variable Selection in Linear Regression in One Pass for Large Datasets"
date = 2014-10-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ordonez, C","Garcia-Alvarado, C","**Baladandayuthapani, V.**"]


# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "ACM Trans. Knowl. Discov. Data"

# Abstract.
abstract = "Bayesian models are generally computed with Markov Chain Monte Carlo (MCMC) methods. The main disadvantage of MCMC methods is the large number of iterations they need to sample the posterior distributions of model parameters, especially for large datasets. On the other hand, variable selection remains a challenging problem due to its combinatorial search space, where Bayesian models are a promising solution. In this work, we study how to accelerate Bayesian model computation for variable selection in linear regression. We propose a fast Gibbs sampler algorithm, a widely used MCMC method that incorporates several optimizations. We use a Zellner prior for the regression coefficients, an improper prior on variance, and a conjugate prior Gaussian distribution, which enable dataset summarization in one pass, thus exploiting an augmented set of sufficient statistics. Thereafter, the algorithm iterates in main memory. Sufficient statistics are indexed with a sparse binary vector to efficiently compute matrix projections based on selected variables. Discovered variable subsets probabilities, selecting and discarding each variable, are stored on a hash table for fast retrieval in future iterations. We study how to integrate our algorithm into a Database Management System (DBMS), exploiting aggregate User-Defined Functions for parallel data summarization and stored procedures to manipulate matrices with arrays. An experimental evaluation with real datasets evaluates accuracy and time performance, comparing our DBMS-based algorithm with the R package. Our algorithm is shown to produce accurate results, scale linearly on dataset size, and run orders of magnitude faster than the R package."

# Summary. An optional shortened abstract.

# Digital Object Identifier (DOI)
doi = "10.1145/2629617"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ['Bayesian Integrative models','Functional data analyses']

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Links (optional).
 url_pdf = "http://doi.acm.org/10.1145/2629617"




# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
+++


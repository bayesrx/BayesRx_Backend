+++
title = "Fast PCA and Bayesian Variable Selection for Large Data Sets Based on SQL and UDFs"
date = 2010-07-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Navas, M","Ordonez, C","**Baladandayuthapani, V.**"]


# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "ACM KDD Large-scale Data Mining: Theory and Applications"

# Abstract.
abstract = "Large amounts of data are stored in relational DBMSs. However, statistical analysis is frequently performed outside the DBMS using statistical tools, such as the well-known R package, leading to slow processing when data sets cannot fit in main memory and going through a file export bottleneck. In this article, we propose algorithms for large data set processing of principal component analysis (PCA) and stochastic search variable selection (SSVS) that can work entirely inside a DBMS, using SQL queries and User-Defined Functions (UDFs). Both of our algorithms consist of two main phases: a first phase to compute sufficient statistics in one pass with SQL queries and a second one to derive the model from such such sufficient statistics, in main memory with UDFs. PCA is efficiently solved with SVD via UDFs in main memory after sufficient statistics are derived. On the other hand, the traditional SSVS algorithm requires multiple passes to compute a model. In contrast, our improved Bayesian algorithm performs a single table scan on the input data set and then the UDF performs thousands of iterations on small matrices. In addition, we incorporate optimizations that exploit DBMS multi-threaded processing capabilities to compute multidimensional aggregates in data summarization. Specifically, we present low-level optimizations to distribute the workload among multiple cores, accessing records by block and caching in main memory. Experiments with large data sets results demonstrate the efficiency of our optimizations to compute sufficient statistics and show our algorithms have linear scalability on the size of the data set. Finally, a detailed comparison against R, the standard open-source package for statistical research, shows correctness and superior speed of our DBMS-based algorithms to process very large datasets."

# Summary. An optional shortened abstract.

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ['Functional data analyses']

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Links (optional).
 url_pdf = "https://pdfs.semanticscholar.org/fa73/bce441cfd885ab15993e7a23c6c8546cf097.pdf"




# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
+++


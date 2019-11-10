+++
title = "Data mining algorithms as a service in the cloud exploiting relational database systems"
date = 2013-06-22T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ordonez, C","García-García, J","Garcia-Alvarado, C","Cabrera, W","**Baladandayuthapani, V.**","S. Quraishi, Mohammed"]

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
publication = "2013 ACM SIGMOD International Conference on Management of Data"

# Abstract.
abstract = "We present a novel cloud system based on DBMS technology, where data mining algorithms are offered as a service. A local DBMS connects to the cloud and the cloud system returns computed data mining models as small relational tables that are archived and which can be easily transferred, queried and integrated with the client database. Unlike other analytic systems, our solution is not based on MapReduce. Our system avoids exporting large tables outside the local DBMS and thus it avoids transmitting large volumes of data to the cloud. The system offers three processing modes: local, cloud and hybrid, where a linear cost model is used to choose processing mode. In hybrid mode processing is split between the local DBMS and the cloud DBMS. Our system has a job scheduler with FIFO, SJF and RR policies to enhance response time and get partial results early. The cloud DBMS performs dynamic job scheduling, model computation and model archive management. Our system incorporates several optimizations: local data set summarization with sufficient statistics, sampling, caching matrices in RAM and selectively transmitting small matrices, back and forth. We show that in general the most efficient computing mechanism is hybrid processing: summarizing or sampling the data set in the local DBMS, transferring small matrices back and forth, leaving mathematically complex methods as a task for the cloud DBMS."

# Summary. An optional shortened abstract.

# Digital Object Identifier (DOI)
doi = "10.1145/2463676.2465240"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ['Bayesian Integrative models']

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Links (optional).
 url_pdf = "http://delivery.acm.org/10.1145/2470000/2465240/p1001-ordonez.pdf?ip=35.1.118.181&id=2465240&acc=ACTIVE%20SERVICE&key=93447E3B54F7D979%2E0A17827594E6F2C8%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1565297590_7f756dc568365103251b54166fc63abe"




# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
+++


---
title: "SNP variable selection by generalized graph domination"
date: 2019-01-01
publishDate: 2020-12-23T16:51:07.043302Z
authors: ["Shuzhen Sun", "Zhuqi Miao", "Blaise Ratcliffe", "Polly Campbell", "Bret Pasch", "Yousry A. El-Kassaby", "Balabhaskar Balasundaram", "Charles Chen"]
publication_types: ["2"]
abstract: "
#### Background

High-throughput sequencing technology has revolutionized both medical and biological research by generating exceedingly large numbers of genetic variants. The resulting datasets share a number of common characteristics that might lead to poor generalization capacity. Concerns include noise accumulated due to the large number of predictors, sparse information regarding the p≫n problem, and overfitting and model mis-identification resulting from spurious collinearity. Additionally, complex correlation patterns are present among variables. As a consequence, reliable variable selection techniques play a pivotal role in predictive analysis, generalization capability, and robustness in clustering, as well as interpretability of the derived models.   

#### Methods and findings

K-dominating set, a parameterized graph-theoretic generalization model, was used to model SNP (single nucleotide polymorphism) data as a similarity network and searched for representative SNP variables. In particular, each SNP was represented as a vertex in the graph, (dis)similarity measures such as correlation coefficients or pairwise linkage disequilibrium were estimated to describe the relationship between each pair of SNPs; a pair of vertices are adjacent, i.e. joined by an edge, if the pairwise similarity measure exceeds a user-specified threshold. A minimum k-dominating set in the SNP graph was then made as the smallest subset such that every SNP that is excluded from the subset has at least k neighbors in the selected ones. The strength of k-dominating set selection in identifying independent variables, and in culling representative variables that are highly correlated with others, was demonstrated by a simulated dataset. The advantages of k-dominating set variable selection were also illustrated in two applications: pedigree reconstruction using SNP profiles of 1,372 Douglas-fir trees, and species delineation for 226 grasshopper mouse samples. A C++ source code that implements SNP-SELECT and uses Gurobi optimization solver for the k-dominating set variable selection is available (https://github.com/transgenomicsosu/SNP-SELECT)."
featured: false
publication: "*PLoS ONE*"
url_pdf: "https://doi.org/10.1371/journal.pone.0203242"
doi: "10.1371/journal.pone.0203242"
---

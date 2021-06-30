---
title: "Novel approaches for analyzing biological networks"
date: 2005-08-01
publishDate: 2020-12-23T16:51:07.057899Z
authors: ["Balabhaskar Balasundaram", "Sergiy Butenko", "Svyatoslav Trukhanov"]
publication_types: ["2"]
abstract: "This paper proposes clique relaxations to identify clusters in biological networks. In particular, the maximum $n$-clique and maximum $n$-club problems on an arbitrary graph are introduced and their recognition versions are shown to be NP-complete. In addition, integer programming formulations are proposed and the results of sample numerical experiments performed on biological networks are reported."
featured: false
publication: "*Journal of Combinatorial Optimization*"
url_pdf: "https://rdcu.be/b6a3D"
doi: "10.1007/s10878-005-1857-x"
---

# Erratum
At the time we wrote and published this paper, we were unfortunately not aware of publications [1,2] that pre-date us on this topic. In particular, reference [1] proves the NP-hardness of the problem, which makes our result in Theorem 1 unnecessary. In fact, our reduction is essentially the same although we arrived at it from a different perspective, as made evident by our presentation. We have rectified this oversight in all our subsequent publications on this topic by appropriately citing and crediting the works of Bourjolly, Laporte, and Pesant. Theorem 2 in our paper is still relevant as it applies to _k_-clubs in graphs of fixed diameter, _e.g._ graphs of diameter _k+1_, a stronger observation.

Frustratingly, the proof of Theorem 1 in our paper is not only redundant, it is also incorrect/incomplete. The proof provided works for odd values of the parameter, just like in Theorem 2. It does not work for even values of the parameter (again, just like in Theorem 2). The reduction provided in Theorem 2 for even values of the parameter should have been used in Theorem 1 as well. We are grateful to Sepp Hartung for bringing this error to our attention.  

Although very unlikely, I apologize if these errors caused any issues for you in your research! **--B.B.**

1. J.M. Bourjolly, G. Laporte, G. Pesant, [An exact algorithm for the maximum _k_-club problem in an undirected graph](https://www.sciencedirect.com/science/article/pii/S0377221701001333), _European Journal of Operational Research,_ 138 (2002) 21–28.
2. J.M. Bourjolly, G. Laporte, G. Pesant, [Heuristics for finding _k_-clubs in an undirected graph](https://www.sciencedirect.com/science/article/pii/S0305054899000477), _Computers & Operations Research,_ 27 (2000) 559–569.

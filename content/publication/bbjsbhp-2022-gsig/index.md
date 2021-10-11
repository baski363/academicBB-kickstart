---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Graph signatures: Identification and optimization"
date: 2022-02-01
authors: ["Balabhaskar Balasundaram", "Juan S. Borrero", "Hao Pan"]
publication_types: ["2"]
doi: "10.1016/j.ejor.2021.03.051"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-09-29T11:31:56-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*European Journal of Operational Research*"

abstract: "We introduce a new graph-theoretic paradigm called a *graph signature* that describes persistent patterns in a sequence of graphs. This framework is motivated by the need to detect subgraphs of significance in  temporal networks, e.g.,  social and biological networks that  evolve over time. Because the subgraphs of interest may not all \"look alike\" in the snapshots of the temporal network, the framework  deems a subgraph to be  *persistent* if it satisfies one of several preselected properties  in each snapshot  of a consecutive  subsequence. The persistency requirement is parameterized by the  length of this subsequence. This discrete mathematical framework can be viewed more broadly  as a way to generalize classical graph properties and  invariants associated with a single graph to a sequence of graphs.

In this introductory article, we formulate the _graph signature identification problem_  as a mixed-integer program and propose an algorithmic framework based on dynamic programming. This methodology is applicable to any collection of mixed-integer representable graph properties. We also demonstrate how this framework can be tailored to exploit property-specific decomposition and scale reduction techniques through three different computational case-studies. Our experiments show that the dynamic programming algorithm solves this problem across most  instances  in our test bed to optimality. Moreover, for the instances in our test bed, the optimal signature sizes are comparable to those of their static counterparts, suggesting that our new framework can identify subgraphs of significance in complex dynamic networks."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

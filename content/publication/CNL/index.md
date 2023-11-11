---
title: "Cooperative Network Learning for Large-Scale and Decentralized Graphs"
authors:
- Qiang Wu
- admin
- Yujie
- Yijie Teng
- Fang Zhou
- Linyuan
- (Joint first author)
date: "2023-09-22"
doi: ""


# draft：true之后就不会显示
# draft: true

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-03"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Graph research, the systematic study of interconnected data points represented as graphs, plays a vital role in capturing intricate relationships within networked systems.  However, in the real world, as graphs scale up, concerns about data security among different data-owning agencies arise, hindering information sharing and, ultimately, the utilization of graph data. Therefore, establishing a mutual trust mechanism among graph agencies is crucial for unlocking the full potential of graphs. Here, we introduce a Cooperative Network Learning (CNL) framework to ensure secure graph computing for various graph tasks. Essentially, this CNL framework unifies the local and global perspectives of GNN computing with distributed data for an agency by virtually connecting all participating agencies as a global graph without a fixed central coordinator. Inter-agency computing is protected by various technologies inherent in our framework, including homomorphic encryption and secure transmission. Moreover, each agency has a fair right to design or employ various graph learning models from its local or global perspective. Thus, CNL can collaboratively train GNN models based on decentralized graphs inferred from local and global graphs. Experiments on contagion dynamics prediction and traditional graph tasks (i.e., node classification and link prediction) demonstrate that our CNL architecture outperforms state-of-the-art GNNs developed at individual sites, revealing that CNL can provide a reliable, fair, secure, privacy-preserving, and global perspective to build effective and personalized models for network applications. We hope this framework will address privacy concerns in graph-related research and integrate decentralized graph data structures to benefit the network research community in cooperation and innovation."

# Summary. An optional shortened abstract.
summary:  "The CNL framework uniquely unifies the local and global perspectives of Graph Neural Network (GNN) computing by connecting all participating agencies as a global graph, all while operating without a fixed central coordinator. This decentralized approach, coupled with state-of-the-art security technologies such as homomorphic encryption and secure transmission, ensures that inter-agency computing remains protected. Additionally, each agency retains the autonomy to design or employ various graph models from both local and global perspectives, thus positioning CNL as a superior and more flexible solution compared to federated learning and swarm learning."


tags:
- Source Themes
featured: false

links:
url_pdf: https://arxiv.org/abs/2311.02117
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '**CNL**'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](xx).

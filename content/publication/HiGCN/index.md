---
title: "Higher-order Graph Convolutional Network with Flower-Petals Laplacians on Simplicial Complexes"
authors:
- admin
- Yujie
- Qiang Wu
- Linyuan
date: "2023-09-22"
doi: ""


# draft：true之后就不会显示
# draft: true

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-22"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Despite the recent successes of vanilla Graph Neural Networks (GNNs) on many tasks, their foundation on pairwise interaction networks inherently limits their capacity to discern latent higher-order interactions in complex systems. To bridge this capability gap, we propose a novel approach exploiting the rich mathematical theory of simplicial complexes (SCs) - a robust tool for modeling higher-order interactions. Current SC-based GNNs are burdened by high complexity and rigidity, and quantifying higher-order interaction strengths remains challenging. Innovatively, we present a higher-order Flower-Petals (FP) model, incorporating FP Laplacians into SCs. Further, we introduce a Higher-order Graph Convolutional Network (HiGCN) grounded in FP Laplacians, capable of discerning intrinsic features across varying topological scales. By employing learnable graph filters, a parameter group within each FP Laplacian domain, we can identify diverse patterns where the filters' weights serve as a quantifiable measure of higher-order interaction strengths. The theoretical underpinnings of HiGCN's advanced expressiveness are rigorously demonstrated. Additionally, our empirical investigations reveal that the proposed model accomplishes state-of-the-art (SOTA) performance on a range of graph tasks and provides a scalable and flexible solution to explore higher-order interactions in graphs."

# Summary. An optional shortened abstract.
summary:  "This paper introduces a novel higher-order representation, the flower-petals (FP) model, enabling interactions among simplices of arbitrary orders. FP adjacency and Laplacian matrices are further introduced based on the higher-order random walk dynamics on the FP model. As an application of FP Laplacians in deep learning, a higher-order graph convolutional network (HiGCN) is introduced. Our theoretical analysis highlights HiGCN's improved expressive power, supported by empirical performance gains across various tasks. Moreover, we deploy a data-driven strategy to demonstrate the existence of higher-order interactions and quantify their strength."


tags:
- Source Themes
featured: true

links:
url_pdf: https://arxiv.org/pdf/2309.12971.pdf
url_source: ''
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
  caption: '**HiGCN**'
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

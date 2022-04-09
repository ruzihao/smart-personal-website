---
title: "Scalable Heterogeneous Graph Neural Networks for Predicting High-potential Early-stage Startups"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- S. Zhang
- H. Zhong
- Z. Yuan
- H. Xiong

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD)*
publication_short: In *ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD)*

abstract: "It is critical and important for venture investors to find high-potential startups at their early stages. Indeed, many efforts have been made to study the key factors for the success of startups through the topological analysis of the heterogeneous information network of people, startup, and venture firms or representation learning of latent startup profile features. However, the existing topological analysis lacks an in-depth understanding of heterogeneous information. Also, the approach based on representation learning heavily relies on domain-specific knowledge for feature selections. Instead, in this paper, we propose a Scalable Heterogeneous Graph Markov Neural Network (SHGMNN) for identifying the high-potential startups. The general idea is to use graph neural networks (GNN) to learn effective startup representations through end-to-end efficient training and model the label dependency among startups through Maximum A Posterior (MAP) inference. Specifically, we first define different metapaths to capture various semantics over the heterogeneous information network (HIN) and aggregate all semantic information into a summated graph structure. To predict the highpotential early-stage startups, we introduce GNN to diffuse the information over the summated graph. We then adopt an MAP inference over Hinge-Loss Markov Random Fields to enforce label dependency. Here, a pseudolikelihood variational expectationmaximization (EM) framework is incorporated to optimize both MAP inference and GNN iteratively: The E-step calculates the inference, and the M-step updates the GNN. For efficiency concerns, we develop a GNN with a lightweight linear diffusion architecture to perform graph propagation over web-scale heterogeneous information networks. Finally, extensive experiments and case studies on real-world datasets demonstrate the superiority of SHGMNN."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

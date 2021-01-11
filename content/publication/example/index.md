---
title: "An Index Advisor Using Deep Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Hai Lan
- Zhifeng Bao
- Yuwei Peng

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: CIKM
#publication_short: In *ICW*

abstract: In this paper, we study the problem of index selection to maximize the workload performance, which is critical to database systems. In contrast to existing methods, we propose an index advisor that integrates index recommendation rules and deep reinforcement learning, such that it can recommend single-attribute and multiattribute indexes together for complex queries and meanwhile support multiple-index access to a table. Specifically, we first propose five heuristic rules to generate the index candidates. Then, we formulate the index selection problem as a reinforcement learning task and employ Deep Q Network (DQN) on it to select a subset of candidates as the recommended indexes. Using the heuristic rules can significantly reduce the dimensions of the action space and state space in reinforcement learning. With the neural network used in DQN, we can model the interactions between indexes better than previous methods. We conduct experiments on various workloads to show its superiority.

# Summary. An optional shortened abstract.
summary: we proposed a novel method to solve the ISP by integrating heuristic rules and DRL together. Unlike previous RL based methods, our method can recommend single and multi-attributes index together and support complex queries; moreover, our method can model the interaction between different indexes in a fine-grained manner.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3340531.3412106'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

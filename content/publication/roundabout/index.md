---
title: 'Roundabout: Solving PFC Deadlocks with Distributed Detection and Buffer Collaboration. (ICNP''24)'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Kai Lv
- Heng Pan
- Chenjun Jia
- Jiaxing Zhang
- admin
- Jianer Zhou
- Yanbiao Li
- Zhenyu Li
- Gaogang Xie

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2024-08-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-06T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proc\. ICNP'24*
publication_short: In **ICNP'24**

abstract: "RDMA over Converged Ethernet (RoCEv2) employs Priority-based Flow Control (PFC) for a lossless fabric to maintain high performance. However, PFC can cause deadlocks, which pause traffic and potentially lead to severe exceptions for applications. Existing solutions solve deadlocks at a considerable cost, resulting in degradation of end-to-end network performance. We present Roundabout, a data plane scheme designed to detect and resolve deadlocks with minimal side effects. We first analyze how switches in different states contribute to deadlocks. Based on the analysis, we design an election-based distributed detection scheme that efficiently and robustly identifies deadlocks. By exploiting buffer configuration redundancy, we develop an in-network collaborative packet scheduling scheme that forwards deadlocked packets to their destinations in a lossless manner, facilitating natural deadlock resolution. Additionally, we implement a barrier mechanism to ensure in-order packet delivery to the receiver. Both analysis and experiments demonstrate that Roundabout effectively detects and resolves deadlocks while minimizing side effects to the network, making it an ideal enhancement for PFC switches."

# Summary. An optional shortened abstract.
# summary: A Scalable and Efficient Hardware Acceleration Architecture for Stateful Layer-4 Load Balancing

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
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

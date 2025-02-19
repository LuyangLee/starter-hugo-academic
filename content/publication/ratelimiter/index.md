---
title: 'Fast, Scalable, and Accurate Rate Limiter for RDMA NICs (SIGCOMM''24)'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Zilong Wang
- Xinchen Wan
- admin
- Yijun Sun
- Peng Xie
- Xin Wei
- Qingsong Ning
- Junxue Zhang
- Kai Chen

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2024-08-07T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proc\. SIGCOMM'24*
publication_short: In **SIGCOMM'24**

abstract: "RDMA NICs desire a rate limiter that is accurate, scalable, and fast: to precisely enforce the policies such as congestion control and traffic isolation, to support a large number of flows, and to sustain high packet rates. Prior works such as SENIC and PIEO can achieve accuracy and scalability, but they are not fast enough, thus fail to fulfill the performance requirement of RNICs, due primarily to their monolithic de- sign and one-packet-per-sorting transmission. We present Tassel, a hierarchical rate limiter for RDMA NICs that can deliver high packet rates by enabling multiple-packet-per- sorting transmission, while preserving accuracy and scala- bility. At its heart, Tassel renovates the workflow of the rate limiter hierarchically: by first applying scalable rate limit- ing to the flows to be scheduled, followed by accurate rate limiting to the packets to be transmitted, while leveraging adaptive batching and packet filtering to improve the perfor- mance of these two steps. We integrate Tassel into the RNIC architecture by replacing the original QP scheduler module and implement the prototype of Tassel using FPGA. Exper- imental results show that Tassel delivers 125 Mpps packet rate, outperforming SENIC and PIEO by 3.6×, while sup- porting 16 K flows with low resource usage, 7.5% - 25.6% as compared to SENIC and PIEO, and preserving high accuracy, precisely enforcing rate limits from 100 Kbps to 100 Gbps."

# Summary. An optional shortened abstract.
# summary: A Scalable and Efficient Hardware Acceleration Architecture for Stateful Layer-4 Load Balancing

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://liluyang.com.cn/pdf/2024/tassel-sigcomm24.pdf'
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

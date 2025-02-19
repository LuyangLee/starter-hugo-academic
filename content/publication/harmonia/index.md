---
title: 'Harmonia: A Unified Framework for Heterogeneous FPGA Acceleration in the Cloud (ASPLOS''25)'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Heng Pan
- Xinchen Wan
- Kai Lv
- Zilong Wang
- Qian Zhao
- Feng Ning
- Qingsong Ning
- Shideng Zhang
- Zhenyu Li
- Layong Luo
- Gaogang Xie

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2025-03-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
date: '2024-08-09T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proc\. ASPLOS'25*
publication_short: In **ASPLOS'25**

abstract: "FPGAs are gaining popularity in the cloud as accelerators for various applications. To make FPGAs more accessible for users and streamline system management, cloud providers have widely adopted the shell-role architecture on their homogeneous FPGA servers. However, the increasing heterogeneity of cloud FPGAs poses new challenges for this architecture. Previous studies either focus on homogeneous FPGAs or only partially address the portability issues for roles, while still requiring laborious shell development for providers and ad-hoc software modifications for users. This paper presents Harmonia, a unified framework for heterogeneous FPGA acceleration in the cloud. Harmonia operates on two layers: a platform-specific layer that abstracts hardware differences and a platform-independent layer that provides a unified shell for diverse roles and host software. In detail, Harmonia provides automated platform adapters and lightweight interface wrappers to manage hardware differences. Next, it builds a modularized shell composed of Reusable Building Blocks and employs hierarchical tailoring to provide a resource-efficient and easy-to-use shell for different roles. Finally, it presents a command-based interface to minimize software modifications across distinct platforms. Harmonia has been deployed in a large service provider, Douyin, for several years. It reduces shell development workloads by 69%-93% and simplifies role and software configurations with negligible overhead (<0.63%). Compared with other frameworks, Harmonia supports cross-vendor FPGAs, reduces resource consumption by 3.5%-14.9% and simplifies software configurations by 15-23x while maintaining comparable performance."

# Summary. An optional shortened abstract.
# summary: A Scalable and Efficient Hardware Acceleration Architecture for Stateful Layer-4 Load Balancing

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://liluyang.com.cn/uploads/2025/harmonia-asplos25.pdf'
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

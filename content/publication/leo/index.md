---
title: 'Leo: A Generic and Efficient Communication Framework for Message-level In-Network Computing (INFOCOM''25)'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Xinchen Wan
- admin
- HandleTian
- Xudong Liao
- Xinyang Huang
- Chaoliang Zeng
- Zilong Wang
- Layong Luo
- Kai Chen

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2025-05-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-08T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proc\. INFOCOM'25*
publication_short: In **INFOCOM'25**

abstract: "Message-level in-network computing (MINC) emerges as a promising hardware acceleration method that utilizes accelerators to offload message-level computation and enhance application performance in the datacenter. However, the development of MINC applications is challenging in the communication aspect due to poor portability and under-utilized resource. In this paper, we present LEO, a generic and efficient communication framework for MINC. LEO facilitates portability across both application and hardware by introducing a communication path abstraction, which is capable of describing generic applications with predictable communication performance across diverse hardware. It further incorporates a built-in multi-path communication over CPU and accelerator to enhance communication efficiency. We have implemented a prototype of LEO and evaluated it with four case studies on testbeds covering FPGA-based, SoC-based smartNICs, and GPU. Experiments show that LEO achieves genericity and efficiency across MINC applications, yielding 1.2–4.7× speedup over baselines with negligible overhead."

# Summary. An optional shortened abstract.
# summary: A Scalable and Efficient Hardware Acceleration Architecture for Stateful Layer-4 Load Balancing

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://liluyang.com.cn/uploads/2025/leo-infocom25.pdf'
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

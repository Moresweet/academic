---
title: 'RASLS: Reinforcement Learning Active SLAM Approach with Layout Semantic'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Changhang Tian
  - Shasha Tian
  - Yilin Kang
  - Hong Wang
  - Jun Tie

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-03-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: Active SLAM plays a crucial role in applications of embodied intelligence. Previous learning-based methods struggle to sufficiently leverage semantic information in the environment, while frontier-based algorithms face challenges in mitigating myopic decision-making issues. Considering that humans experientially use observed information while exploring environments, we propose a deep reinforcement learning approach incorporating object semantic information and design a reward-matching mechanism based on the prior object layout. To tackle the instability in exploration gains caused by error optimization in the mapping part of the SLAM system, we introduce a method for differential map uncertainty confidence filtering. We conduct reinforcement learning training using Gazebo in office scenarios based on 3DGEMS and perform comparisons in a new scenario. Through ablation analysis, we demonstrate the effectiveness of layout semantic information. Compared to the latest reinforcement learning baseline, experimental results indicate that our method achieves a higher success rate with a shorter average execution time and path length.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/Moresweet/DRL_ARE_Graph_Gazebo'
url_dataset: 'https://data.nvision2.eecs.yorku.ca/3DGEMS/'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtube.com'

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
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

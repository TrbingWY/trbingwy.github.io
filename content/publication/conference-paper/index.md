---
title: 'Distributed Acoustic Source Tracking in Noisy and Reverberant Environments With Distributed Microphone Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qiaoling Zhang
  - Weiwei Zhang
  - Jie Feng
  - admin

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2019-12-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-12-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-artile']

# Publication name and optional abbreviated publication name.
publication: In *IEEE ACCESS
# publication_short: In *ICW*

abstract: In this paper, an improved distributed unscented Kalman particle filter (DUKPF) is proposed for the problem of tracking a single moving acoustic source in noisy and reverberant environments with distributed microphone networks. The conventional DUKPF employs the unscented Kalman filter (UKF) for its proposal of particle sampling, whereas the UKF incorporates one single observation from a certain localization function, which is vulnerable to noise or reverberation. To alleviate this problem, multiple observations are extracted from the localization function at each node and incorporated into the state update of the UKF via the probability data association (PDA) technique, yielding the PDA-UKF. Next, employing the PDA-UKF for the proposal of particle sampling, the improved DUKPF is further developed. Finally, the improved DUKPF is adapted for the acoustic source tracking problem, and a distributed acoustic source tracking method is presented. Simulation results reveal that the improved DUKPF achieved better tracking performance than the conventional DUKPF in different noisy and reverberant conditions.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
#   - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8954669'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

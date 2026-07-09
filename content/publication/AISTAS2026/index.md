---
title: '	
Representative, Informative, and De-Amplifying: Requirements for Robust Bayesian Active Learning under Model Misspecification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Weiwei Zhang
  - Sabina J Sloman
  - Samuel Kaski

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-artile']

# Publication name and optional abbreviated publication name.
publication: In AISTATS 2026
# publication_short: In *ICW*

abstract: In many science and industry settings, a central challenge is designing experiments under time and budget constraints. Bayesian Optimal Experimental Design (BOED) is a paradigm to pick maximally informative designs that has been widely applied to such problems. During training, BOED selects inputs according to a pre-determined acquisition criterion to target informativeness. During testing, the model learned during training encounters a naturally occurring distribution of test samples. This leads to an instance of covariate shift, where the train and test samples are drawn from different distributions (the training samples are not representative of the test distribution). Prior work has shown that in the presence of model misspecification, covariate shift amplifies generalization error. Our first contribution is to provide a mathematical analysis of generalization error in the presence of model misspecification, revealing that, beyond covariate shift, generalization error is also driven by a previously unidentified phenomenon we term error (de-)amplification. We then develop a new acquisition function that mitigates the effects of model misspecification by including terms for representativeness, informativeness, and de-amplification (R-IDeA). Our experimental results demonstrate that the proposed method performs better than methods that target only informativeness, only representativeness, or both.

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

url_pdf: 'https://arxiv.org/pdf/2506.07805'
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

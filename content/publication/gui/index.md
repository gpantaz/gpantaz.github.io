---
title: 'An Efficient Training Pipeline for Reasoning Graphical User Interface Agents'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Eda Bilici Ozyigit

# Author notes (optional)
# author_notes:
#   - "Equal contribution"
#   - "Equal contribution"
#   - "Equal contribution"

date: '2026-03-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ICLR 2026 Workshop Multimodal Intelligence Next Token Prediction And Beyond*
publication_short: In *ICLR*

abstract: Existing methods for developing Graphical User Interface agents rely on massive, noisy synthetic datasets obtained by extracting elements in the interface and then generating instructions with an oracle component. While effective, this pipeline often results in misaligned, low quality or repetitive instructions. This work introduces an efficient training pipeline that combines model-based data filtering with parameter-efficient fine-tuning. From 4.8M synthetic examples, 12K clean and diverse instances are curated by first identifying challenging cases, removing misaligned and then selecting a diverse set of multimodal instances. On this data, a 3B-parameter Vision-Language Model is trained under three regimes 1) supervised fine-tuning, 2) chain-of-thought augmented fine-tuning, and 3) reinforcement learning via Group Relative Policy Optimization. Models trained with the filtered data and lightweight training strategies match or surpass larger baseline models trained with orders of magnitude more data. These results demonstrate that principled data curation and robust adaptation can rival large-scale training, enabling compact yet capable multimodal reasoning agents.

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

url_pdf: 'https://arxiv.org/pdf/2511.08172'
url_code: 'https://github.com/alan-turing-institute/gui-agent'
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
#   focal_point: ''
#   preview_only: false

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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

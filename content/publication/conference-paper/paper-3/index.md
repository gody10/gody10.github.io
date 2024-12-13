---
title: 'EMS-env: A Reinforcement Learning Framework for Residential Energy Efficiency Recommendations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Spiros Chadoulos
  - admin
  - Iordanis Koutsopoulos
  - George C. Polyzos
  - Nikolaos Ipiotis
  

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-09-01T00:00:00Z'
doi: '10.1109/SmartGridComm60555.2024.10738082'

# Schedule page publish date (NOT publication's date).
publishDate: 'tbd'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Published in *2024 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)*
publication_short: In *2024 (SmartGridComm)*

abstract: Personalized device-level energy consumption recommendations towards energy efficiency can have a notable impact both on electricity bills and on the overall energy supply-demand balance. End-user behavior regarding device activation is usually unknown a priori, thus giving rise to a highly dynamic environment. Hence, Reinforcement Learning (RL) can be utilized for device scheduling and consumption recommendations since it constitutes an Artificial Intelligence (AI) framework that learns a control policy in a dynamic environment through trying actions and observing incurred rewards. However, existing works on energy consumption recommendations do not explicitly take into account human feedback and preferences regarding the issued recommendations, and they train a single RL agent per device, hence missing the human behavior interdependencies in using different devices. In addition, a flexible open-source RL environment model that integrates user behavior in a Markov Decision Process (MDP) model is missing. In this paper, we propose an MDP-driven RL framework for energy efficiency recommendations that jointly learns the user’s behavior for multiple devices. The proposed model is wrapped as an open-source customizable Gymnasium environment, named EMS-env, for multi-device energy efficiency recommendations. EMS-env can simulate different types of consumer behavior profiles based on the MDP model and supports different device types as well as user feedback. Validation experiments demonstrate the framework’s merits and hyperparameters for diverse use cases in terms of user simulation models and RL training policies, resulting in decreased energy costs while maintaining end-user satisfaction.

# Summary. An optional shortened abstract.
summary: 

tags: [Reinforcement Learning, Energy task scheduling, Smart Homes]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10738082'
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
  caption: 'Image credit: [**SMARTGRIDCOMM**](https://sgc2024.ieee-smartgridcomm.org)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---

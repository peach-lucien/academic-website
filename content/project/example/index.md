---
slides: example
url_pdf: ""
summary: The widespread adoption of online courses opens opportunities for
  analysing learner behaviour and optimising web-based learning adapted to
  observed usage. In collaboration with the Prof. David Lefevre and the [EdTech
  group in Imperial Business
  School](https://www.imperial.ac.uk/business-school/about-us/edtech-lab/), I
  began working on data extracted from the learning management system. Our aim
  was to first understand how students transitioned through courses, and then to
  find ways to predict performance and later optimise the student experience.
url_video: ""
date: 2016-04-27T00:00:00.000Z
featured: false
external_link: ""
url_slides: ""
title: Learning Analytics
tags:
  - LearningAnalytics
links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
image:
  caption: Unsupervised learning of student similarity reveals behavioural clusters.
  focal_point: Smart
  filename: featured.png
url_code: ""
---


\
In our first investigation we introduced a mathematical framework for the analysis of time-series of online learner engagement, which allows the identification of clusters of learners with similar online temporal behaviour directly from the raw data without prescribing a priori subjective reference behaviours. The method uses a dynamic time warping kernel to create a pair-wise similarity between time-series of learner actions, and combines it with an unsupervised multiscale graph clustering algorithm to identify groups of learners with similar temporal behaviour. To showcase our approach, we analyse task completion data from a cohort of learners taking an online post-graduate degree at Imperial Business School. Our analysis reveals clusters of learners with statistically distinct patterns of engagement, from distributed to massed learning, with different levels of regularity, adherence to pre-planned course structure and task completion. The approach also reveals outlier learners with highly sporadic behaviour. A posteriori comparison against student performance shows that, whereas high-performing learners are spread across clusters with diverse temporal engagement, low performers are located significantly in the massed learning cluster, and our unsupervised clustering identifies low performers more accurately than common machine learning classification methods trained on temporal statistics of the data. Finally, we test the applicability of the method by analysing two additional data sets: a different cohort of the same course, and time-series of different format from another university.
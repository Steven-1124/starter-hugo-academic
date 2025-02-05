---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Research Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:

  - title: Influencer Marketing (Empirical, Machine Learning)
    # company: advised by [_Prof. Shunyuan Zhang_](https://www.acem.sjtu.edu.cn/en/faculty/zhouzucheng.html) from [Shanghai Jiao Tong University](https://www.acem.sjtu.edu.cn/en/)
    # company_url: ''
    # company_logo: sjtu
    location: Remote
    date_start: '2023-06-01'
    date_end: 'ongoing'
    description: |2-
      <font size='4'>"Influencer Selection with MMOE" with [_Prof. Shunyuan Zhang_](https://www.hbs.edu/faculty/Pages/profile.aspx?facId=1175206) from Harvard Business School and [_Prof. Xitong Li_](https://sites.google.com/view/xitong-li/home) from HEC, Paris.</font>
      -	Improved Multi-Gate Mixture-of-Experts (MMOE) algorithm, based on the incentive mechanism of influencer behavior and interactions between marketing goals (reputation, revenue, acceptance), increasing the revenue prediction performance by over 20%.
    	- Explored the underlying mechanisms of multi-task learning models, based on literatures and regression analysis, identifying model-relevant factors such as the gating mechanism, data-relevant factors such as data sparsity, and feature-relevant factors such as latent relevance.
      - Embedded dynamic weighting algorithm (GradNorm) into MMOE to dynamically tune the weights of different tasks during the training process, increasing the model performance by over 200% over a highly unbalanced and sparse dataset.
      - Examined topic modeling algorithms (BerTopic, LDA etc.), implemented multimodal BerTopic model to cluster millions of posts (images and texts), optimized the topic representation, achieving a balanced performance on different metrics (coherence, topic overlap etc.).


  - title: Image Process and Classification (Machine Learning)
    # company: advised by [_Pro. Colin Tan_](https://www.comp.nus.edu.sg/cs/people/ctank/) from [National University of Singapore](https://www.comp.nus.edu.sg/)
    location: Singapore
    # company_logo: NUS
    date_start: '2022-06-01'
    date_end: '2022-08-01'
    description: |2-
      <font size='4'>"Drowsy Driving Detection under Different Circumstances with Convolutional Neural Networks (CNN)" with [_Pro. Colin Tan_](https://www.comp.nus.edu.sg/cs/people/ctank/) from NUS</font>
        - Developed the algorithm based on CNN to detect drowsiness with nearly 95% accuracy under different circumstances such as dark or bright.
        - Built the backend classification server that performed the algorithm to handle the data and communicated data between detectors and actuators.
        - Transferred data over Message Queueing Telemetry Transport (MQTT), RESTful APIs and stored in SQL databases.
design:
  columns: '2'
---

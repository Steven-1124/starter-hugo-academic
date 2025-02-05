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
    location: Shanghai, China
    date_start: '2021-09-01'
    date_end: '2022-09-01'
    description: |2-
      <font size='4'>"Relationship between Manager’s Personal Background and the Evaluation of External Environment for CSR Implementation" with [_Pro. Zucheng Zhou_](https://www.acem.sjtu.edu.cn/en/faculty/zhouzucheng.html) from SJTU</font>
        - Applied two multiple linear regressions, with and without control variables, to research the relationship between personal background such as age and the evaluation of external environment, based on the data collected from MBA students across China.
        - Analyzed the underlying mechanisms from the perspective of work experience, tolerance, forgiveness and anchor bias.
        - Gave implications for companies to recruit from different backgrounds to form the CSR department with staff’s attitudes towards the external environment balanced as well as for scholars to reduce bias in a right way when sampling people’s view about the external environment.

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

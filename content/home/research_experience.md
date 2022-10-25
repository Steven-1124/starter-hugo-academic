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
  - title: Joint Investment/Venture (Game Theory)
    # company: advised by [_Pro. Yaozhongwu_](https://bizfaculty.nus.edu.sg/faculty-details/?profId=161) from [National University of Singapore](https://bizfaculty.nus.edu.sg)
    # company_url: ''
    # company_logo: NUS
    location: Singapore
    date_start: '2022-07-01'
    # date_end: '2023-09-01'
    description: |2-
      <font size='4'> "Vertical Joint Investment under Capacity Limitation and Demand Uncertainty" with [_Pro. Yaozhong Wu_](https://bizfaculty.nus.edu.sg/faculty-details/?profId=161) from NUS</font>
        - We study the joint investment between a supplier (S) and one manufacture (M1) of the two (M1, M2), who sell to separate markets with uniform demand. Besides share of cost and revenue, there is “preferential strategy”, which means S would give M1 either order priority (order satisfied first) or price discount (discount market price) or both. We analyze the optimal joint investment strategy, which mainly concerns the share of cost and revenue and the preferential strategy. The optimal strategy can be characterized by market settings (cost, price, demand).

  - title: Capacity Expansion (Game Theory, Behavior)
    # company: advised by [_Pro. Zhihong Chen_](https://www.acem.sjtu.edu.cn/en/faculty/chenzhihong.html) from [Shanghai Jiao Tong University](https://www.acem.sjtu.edu.cn/en/)
    # company_url: ''
    # company_logo: sjtu
    location: Shanghai, China
    date_start: '2021-04-01'
    # date_end: '2022-09-01'
    description: |2-
      <font size='4'>"Adaptive Risk Preference and Strategy in Capacity Expansion under Price and Demand Uncertainty" with [_Pro. Zhihong Chen_](https://www.acem.sjtu.edu.cn/en/faculty/chenzhihong.html) from SJTU</font>
        -	Set out six price-demand scenarios with probabilities assigned and six available capacity expansion strategies.
        -	Built a suggestion system which outputs several indexes such as the expected profit and standard deviation of a specific capacity strategy.
        -	Plan to conduct an experiment where managers choose strategy based on our suggestions and learn from the competition results.
        -	Plan to research whether and how the risk preference of a manger adaptively changes and analyze the possible winning strategy.


  - title: Corporate Social Responsibility (Empirical)
    # company: advised by [_Pro. Zucheng Zhou_](https://www.acem.sjtu.edu.cn/en/faculty/zhouzucheng.html) from [Shanghai Jiao Tong University](https://www.acem.sjtu.edu.cn/en/)
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

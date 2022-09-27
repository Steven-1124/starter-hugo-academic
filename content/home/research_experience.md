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
      <font size='4'> "Contract Design for Vertical Joint Investment under Demand Uncertainty" with [_Pro. Yaozhong Wu_](https://bizfaculty.nus.edu.sg/faculty-details/?profId=161) from NUS</font>
        - In an emerging market (i.e., electrical vehicle), the demand may grow fast though with uncertainty and capacity may be limited, under which circumstance manufactures may stretch operation to materials through joint investment with suppliers. Besides cost and revenue sharing, the partner manufacture is always given priorities: priority ordering (order can be satisfied in the first place) and price discount (wholesale price should be lower than market price). We apply game theory to research the contract under different market settings (price, cost, demand) and try to propose a fair and profitable contract under demand uncertainty.

  - title: Capacity Expansion (Game Theory, Behavior)
    # company: advised by [_Pro. Zhihong Chen_](https://www.acem.sjtu.edu.cn/en/faculty/chenzhihong.html) from [Shanghai Jiao Tong University](https://www.acem.sjtu.edu.cn/en/)
    # company_url: ''
    # company_logo: sjtu
    location: Shanghai, China
    date_start: '2021-04-01'
    # date_end: '2022-09-01'
    description: |2-
      <font size='4'>"Capacity Expansion Strategy in a Growing Oligopoly with Financial Constraints Based on Scenario Analysis" with [_Pro. Zhihong Chen_](https://www.acem.sjtu.edu.cn/en/faculty/chenzhihong.html) from SJTU</font>
        - Modeled the capacity decision under financial constraints based on different price-demand scenarios.
        - Assigned probabilities to scenarios to describe the uncertainty and modified the probability to capture the uncertainty of uncertainty, simulating that in reality, companies may not be informed of future price-demand and can be misled by competitors, securities and customers.
        - Designing a game for managers to play with different market settings and strategies.
        - Will incorporate behavioral factors inspired by managers‘ performance to research the mechanism behind winning strategy.

  - title: Corporate Social Responsibility (Empirical)
    # company: advised by [_Pro. Zucheng Zhou_](https://www.acem.sjtu.edu.cn/en/faculty/zhouzucheng.html) from [Shanghai Jiao Tong University](https://www.acem.sjtu.edu.cn/en/)
    # company_url: ''
    # company_logo: sjtu
    location: Shanghai, China
    date_start: '2021-09-01'
    date_end: '2022-09-01'
    description: |2-
      <font size='4'>"Impacts of Personal Background on Managers’ View about External Environment for CSR Implementation" with [_Pro. Zucheng Zhou_](https://www.acem.sjtu.edu.cn/en/faculty/zhouzucheng.html) from SJTU</font>
        - Applied regression, clustering and hypothesis test to analyze the data collected from MBA students across China and found that managers who work longer and more senior are less optimistic as well as males are generally less than females.
        - Analyzed mechanisms behind the results from multiple disciplines such as psychology and sociology.
        - Gave implications for companies to form a more efficient CSR group as well as for scholars to consider the inevitable bias in manager’s view about enterprise external environment in a right way.

  - title: Image Process and Classification (Machine Learning)
    # company: advised by [_Pro. Colin Tan_](https://www.comp.nus.edu.sg/cs/people/ctank/) from [National University of Singapore](https://www.comp.nus.edu.sg/)
    location: Singapore
    # company_logo: NUS
    date_start: '2022-06-01'
    date_end: '2022-08-01'
    description: |2-
      <font size='4'>"Drowsy Driving Detection under Different Circumstances with Convolutional Neural Networks (CNN)" with [_Pro. Colin Tan_](https://www.comp.nus.edu.sg/cs/people/ctank/) from NUS</font>
        - Developed an algorithm based on Convolutional Neural Networks (CNN) to detect the drowsiness of driver with nearly 95% accuracy under several circumstances (dark or bright, traffic jammed or not, head up or down).
        - Collected data with detectors, transferred over Message Queueing Telemetry Transport (MQTT), RESTful APIs and stored in SQL databases.
        - Built a global web server, on which we applied our algorithm and transfer the results back to instruct actuators to remind the driver.
design:
  columns: '2'
---

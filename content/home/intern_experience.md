---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Professional Experience
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

 - title: Moseeker 
    company: Data Scientist, AI Interview Team
    # company_url: 'https://www.risingwave-labs.com/'
    # company_logo: rwicon
    location: Shanghai, China
    date_start: '2023-10-01'
    date_end: '2024-10-01'
    description: |2-
      - Designed an interview question generation algorithm, by combining knowledge graph and LLM, improving the depth and diversity of interview questions, smoothing the communication, and balancing the job requirements and the candidate’s experience.
      - Built an automated resume parsing system, based on multiple LLM agents (i.e., GPT and Deepseek) and text processing tools (i.e., Tika and pdfplumber), achieving over 90% accuracy across diverse formats of resumes such as image-based PDFs and multilingual resumes.
      - Demonstrated the effectiveness and potential socioeconomic biases of AI evaluation on candidates’ interview performance by using multiple methods such as hypothesis testing and regression to analyze the campus recruitment data.
      - Examined millions of job posts and applications to illustrate and visualize the talent trends from multiple aspects such as talent flows across job types and cities and most popular skills.

  - title: Guo Sheng Securities
    company: Analyst intern, Electrical Engineering and New Energy Department
    # company_url: 'https://dynamics.microsoft.com/en-us/'
    # company_logo: Microsoft_logo
    location: Shanghai, China
    date_start: '2021-07-01'
    date_end: '2021-08-01'
    description: |2-
        * Independently investigated the whole supply chain of electrical vehicle, analyzing the competitive landscape and comparing various companies, and forming in-depth reports with more than 15,000 words.
        * Built and managed a database for electrical vehicle to track the production and sales by country, firm, and model.
 
design:
  columns: '2'
---

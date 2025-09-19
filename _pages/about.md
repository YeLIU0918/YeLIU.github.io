---
permalink: /
title: "👤 Biographies"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Ye Liu was born in China. She received her MBBS in Public Health from Guangzhou Medical University (2015–2020) and an MSc in Public Health from the London School of Hygiene & Tropical Medicine (2020–2021). She is currently working as a Research Assistant at the University of North Carolina at Chapel Hill – Project China.

Her research interests include **pharmacoepidemiology, real-world evidence (RWE), digital health interventions, AI/machine learning** for drug safety, antimicrobial resistance, and implementation science. She has led cluster-randomized trials of pay-it-forward STI testing, designed digital partner-notification and self-sampling interventions, and organized gamified co-creation workshops for STI management.

She has contributed to peer-reviewed publications in PLOS ONE, Lancet Global Health, JAMA Network Open, and Frontiers in Oncology, covering randomized controlled trials, systematic reviews, and implementation science.

You can find my CV here: [Ye LIU's Curriculum Vitae](https://yeliu0918.github.io/YeLIU.github.io/assets/CV-YeLIU.pdf).

📖 Educations
======
- One MSc Public Health, **London School of Hygiene & Tropical Medicine**, UK (2020–2021)  
- Two **Bachelor of Medicine**, Public Health, Guangzhou Medical University, China (2015–2020)


👩🏻‍🔬 Research
======
**Pay-it-Forward STI Testing RCT (UNC–Project China) (Aug 2023–Present)**
- Coordinated a cluster randomized controlled trial (RCT) on pay-it-forward STI testing among MSM in Guangdong, China.
- Managed participant recruitment, follow-up, and site coordination.
- Conducted advanced statistical analyses (R, Stata, SPSS).
- Led an AMR sub-study to evaluate Neisseria gonorrhoeae antimicrobial resistance trends using MIC-based indicators
across intervention vs. control cities.

**Digital Partner Notification & Self-sampling (WeChat Mini-app) (2023–Present)**
- Designed and implemented a digital intervention enabling STI patients to notify partners for self-sampling. 
- Developed simplified referral pathways (patient → partner → self-sampling → result → referral). 
- Produced SOPs and visual templates for clinical integration.

**Gamified Co-creation for Digital STI Management (2023–Present)**
- Organized participatory workshops with doctors, patients, and CBOs to co-create gamified digital health interventions. 
- Designed guiding scripts, visual templates, and evaluation metrics. 
- Piloted gamification elements to improve user engagement and ownership.

**Mutual Aid Interventions in HIV/STI – Systematic Review (Aug 2023–July 2025)**
- Conducted database searches, critical appraisal, and data synthesis. 
- Produced evidence summaries and manuscripts. 

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

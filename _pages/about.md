---
layout: about
title: about
permalink: /
description: A Python Developer with expertise in Data Science and Natural Language Processing. 

profile:
  align: right
  image: prof_pic.jpg
  address: >

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I am a `Python Developer` with expertise in `Data Science`, `Natural Language Processing` and `Testing`.

Currently, I work as a `Data Analysis Engineer` at [GoMore](https://www.gomore.net/en).

* * *

### personal projects

1. NDLTD TW Papers Graph ![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)![](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)
   - This project uses Vue.js for the frontend and FastAPI for the backend. It utilizes Opensearch as vector database.
   - This project employs GitHub Actions for automating the CI/CD process and hosted on AWS.
   - Uses AWS Lambda as  web scraper to gather data, using Sentence-Transformer to understand the meaning of words, and uses KNN to find articles that are similar to each other.
   - Inpired by: [Keyword Analysis (GroundAI)](https://keywords.groundedai.company/) 
   - [https://ndltd-tw-papers-graph.wspooong.com](https://ndltd-tw-papers-graph.wspooong.com)

2. LY Transcription
   - LY Transcription helps you download Legislative Gazette records from the [Legislative Yuan(立法院)](https://www.ly.gov.tw/Home/Index.aspx) and convert them into JSON files.
   - Since the files are in DOC format, and Python currently supports processing Word files in DOCX format, the files need to be converted from DOC to DOCX before the transformation can take place.
   - Note: The DOC-to-DOCX conversion tool is provided by Microsoft Office, and I have only tested it on Windows. Therefore, this project is currently compatible only with Windows systems.


* * *

### skilled-based project

1. Facebook Group Scraper ![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
   - Written in Python 3.7, leveraging the requests library to extract group posts, comments, and replies, featuring pagination support and configurable wait times between requests.
   - Highly inspired by [kevinzg/facebook-scraper](https://github.com/kevinzg/facebook-scraper).  
   - GitHub: [wspooong/facebook-group-scraper](https://github.com/wspooong/facebook-group-scraper)

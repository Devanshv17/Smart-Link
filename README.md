# Automated-Content-Analysis-Website
## Team Whackos
Abhijeet Kumar,
Aryan Mittal,
Devansh Verma,
Riya Sanket Kashive

## Overview
This solution aims to automate the extraction and content analysis of all embedded links from a website, regardless of their location, and includes asking concise and relevant questions,  the most relevant links and topics for those questions, all complete with an automated verification and metric system for assessing their aforementioned parameters (conciseness and relevance). 
A detailed documentation of the repository has been laid out in [this document](https://docs.google.com/document/d/15aiZwVIH22bgzQ4fd2t6DxWWno5sgLMp5cle6LNZZTI/edit?usp=sharing).

## Key Features:
1. Data Scraping: Utilizes Selenium to extract all embedded links from the target website.
2. Data Storage: JSON files are used to store and organize the extracted data.
3. Question Generation: We employ the duckduckgo_search library in conjunction with the gemini API to generate precise and pertinent questions.
4. Link-Question Mapping and Relevance Metric: TFIDF Vectorization is used to map the generated questions to the most relevant links, and is employed as a relevance metric to evaluate the quality of the mappings.

## Problem Statement
For detailed information on the problem statement, please refer to [this document](https://docs.google.com/document/d/1GaQza95lxQJHXrCtrdntavKL3a0_Bg_Kvj3QmZuDNWA/edit).

## Achievements
Our solution achieved an accuracy of 83%.
<img width="525" alt="Screenshot 2024-08-26 at 1 19 30 PM" src="https://github.com/user-attachments/assets/29f73f70-5ac7-4047-b4ed-1ba50efd258d">



## Milestones
1. Extraction of embedded links from a website.
2. Content analysis and question generation.
3. Implementation of an automated system for verification and relevance assessment.

# Instahyre-Job-Portal-Analysis

## Introduction
The project's objective is to gather job-related information from Instahyre using Python's Selenium library and organize it in a specified format. The collected data will then be converted into three separate tables: jobs, company, and details, utilizing the Pandas library. To enable user-friendly searches, a search bar will be implemented using the Flask web framework, allowing users to look up skills. The search results will display essential details, such as the most common experience level, industry, and company class where the skill is in demand, along with the number of available job opportunities. To enhance user experience, the FuzzyBuzzy library will be employed to correct any input errors made by users in the search bar.

## Problem Aimed to Solve:
1.Automate the job search process - Save time and effort.

2.Provide comprehensive job details - Rich information for users.

3.Enhance search query accuracy - Improve search results precision.

4.Analyze job market trends - Identify employment patterns and demands.

5.Increase job matching efficiency - Connect candidates with suitable positions.

## Methodology
The following methodology was used to accomplish the project objectives:

 1. Data Scraping: Job data was obtained from Instahyre using Python's Selenium library, considering specific criteria like job titles, locations, and company names.
2. Data Conversion: Utilizing Pandas, the scraped data underwent transformation into three tables: jobs, company, and details.
3. Data Cleaning and Preparation: The data cleaning phase involved eliminating irrelevant data, handling missing values, standardizing formats, removing duplicates, cleaning text, managing outliers, type conversion, consistency checks, categorical data normalization, and ensuring data integrity.
4. Company Classification: Companies were classified into five classes (Class0 to Class4) based on employee count and company age using K-Means clustering. The optimal number of clusters was determined using the Elbow Method.
<img width="618" alt="image" src="https://github.com/Ajay-V1/Instahyre-Job-Portal-Analysis/assets/132564171/ebb84f19-17d3-4714-aab5-6e649889e672"><br>

 <img width="372" alt="image" src="https://github.com/Ajay-V1/Instahyre-Job-Portal-Analysis/assets/132564171/ea2b80ac-daf6-4b9a-b360-f48c09e6fd02"> <br>
 <img width="623" alt="image" src="https://github.com/Ajay-V1/Instahyre-Job-Portal-Analysis/assets/132564171/bde192eb-592e-4878-b0f3-6321ee89a1e5"> <br>

<img width="372" alt="image" src="https://github.com/Ajay-V1/Instahyre-Job-Portal-Analysis/assets/132564171/fc8c08a9-a104-43c4-99c0-23732b41a391"> <br>

5. User-Friendly Interface: A Flask web framework introduced a search bar for users to look up skills. FuzzyBuzzy library corrected any input errors. Search results displayed the most common experience level, industry, company class related to the skill, and the number of available job opportunities.<br>

## Challenges and Learnings
1. Webpage with HTML/CSS:
   * Challenge: Design a webpage using HTML/CSS.
   * Learning: Learn HTML structure, CSS styling.
2. User Text Processing with FuzzyWuzzy:
   * Challenge: Process user text using FuzzyWuzzy.
   * Learning: Understand text manipulation, fuzzy matching.
3. Backend with Flask, Webpage Interaction:
   * Challenge: Create Flask backend, connect to webpage.
   * Learning: Grasp Flask basics, dynamic content.
4. Model Deployment Exploration:
   * Challenge: Explore deployment options.
   * Learning: Deployment option
 
## Results
1. This webpage is designed to accept user input.<br>

<img width="603" alt="image" src="https://github.com/Ajay-V1/Instahyre-Job-Portal-Analysis/assets/132564171/aa201fe8-9783-4339-93d2-f7e663d43328"><br>
2. The webpage generates output based on the skills searched by the users.<br>
<img width="601" alt="image" src="https://github.com/Ajay-V1/Instahyre-Job-Portal-Analysis/assets/132564171/dff527bf-7253-43bc-90d5-b50bdc4760de"><br>
3. This webpage showcases a comprehensive list of jobs related to specific skills entered by users, along with supplementary information.<br>
<img width="1080" alt="image" src="https://github.com/Ajay-V1/Instahyre-Job-Portal-Analysis/assets/132564171/5f3dbe31-5922-417f-b084-b88ec9275a53"><br>
  
## Conclusion:
In this project, we embarked on a comprehensive analysis of the Instahyre job portal to uncover valuable insights into the job market and user interactions. We identified the most in-demand job categories and explored how they evolved over time, providing job seekers with valuable information on where to focus their job search. Our analysis highlighted regional disparities in job availability and industry preferences, helping job seekers target their search efforts more effectively.

## References
* Python Software Foundation. (2022). Python Language Reference, version 3.10. Retrieved from
  https://docs.python.org/3/reference/index.html
* Selenium with Python: https://selenium-python.readthedocs.io/
* Wikipedia contributors. (2023, April 13). Flask (web framework). In Wikipedia, The Free Encyclopedia. Retrieved 15:48, April 22, 2023, from "https://en.wikipedia.org/wiki/Flask_(web_framework)"
* Scikit-learn developers. (n.d.). Clustering. Retrieved April 22, 2023, from "https://scikit-learn.org/stable/modules/clustering.html"






## Project 2: Marketing Email Campaign 

This repository contains an email analytics project for CSB304 (Data Analytics in Business). The goal of this project was to act as an analytics department/team for Timeless Transport Models in 2004. The company conducted A/B tets to determine the following:
- Which email tone performs better:
    - Conversational (Group A)
    - Alarming/Urgent (Group B)
- Which day of the week maximizes engagement and sales:
    - Monday
    - Wednesday
    - Friday
Using the R programming language, we conducted statistical tests, created visualizations, and interpreted the results to provide recommendations for the company.

# Business Objective:
We want to determine what email strategies drive more user engagement and sales. To do so we will run statistical tests on previous email metrics gauging what tone of speech and days of the week produce better results via open rate, click rate, unsubscribe rate, etc. We will present our findings with visualizations and analyses.

We determined the conversational tone promoted more positive user engagement via open to click rate, unsubscribe rate, and order rate. Net sales was also greater due to the incresed order rate. Additionally, we found that Monday is our best day for sending emails and reciveing back positive user engagement via open rate and click rate.

## Contents in the Repository
This repository contains the following:
- data folder - Data sets used for this project.
- .gitignore - a plain text file that tells Git/GitHub which files or directories to exclude from tracking in a repository.
- AI.md - Explaination of how AI tools were used in this project in alignment with course guidelines on AI usage.
- CONTRIBUTING.md - Description of team member roles and contributions.
- Marketing-Email-Campaign-Data-Analytics.Rproj 
- README.md - Overview of the project and the repository as a whole.
- project-2-technical-notebook.Rmd - R Notebook where the graphs and statistical analysis were done.
- project-2-technical-notebook.nb.html - HTML version of the R notebook.

## How to Use This Repository 
  1. Clone the repository
  2. Install the requirements.yml using a virtual environment with the command: conda env create -f environment.yml (if using conda)
  3. Data sets are already in the repository, so open the notebook in R studio for your use.
  4. Open the 'project-2-technical-notebook.Rmd' to see the project work.

## Tools used:
- R 
- R Markdown
- RStudio
- R libraries (tidyverse, pwr, car, effectsize, ggplot2, etc.)
- GitHub (for version control and team collaboration)

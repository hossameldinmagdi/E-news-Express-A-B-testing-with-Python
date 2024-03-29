# E-news-Express- A/B testing with Python

An online news portal aims to expand its business by acquiring new subscribers. Every visitor to the website takes certain actions based on their interest. The company plans to analyze these interests and wants to determine whether a new feature will be effective or not. Companies often analyze user's responses to two variants of a product to decide which of the two variants is more effective. This experiment technique is known as a/b testing that is used to find out whether a new feature attracts users based on a chosen metric.

Suppose you are hired as a Data Scientist in E-news Express. The design team of the company has created a new landing page. You have been assigned the task to decide whether the new landing page is more effective to gather new subscribers. Suppose you randomly selected 100 users and divided them equally into two groups. The old landing page is served to the first group (control group) and the new landing page is served to the second group (treatment group). Various data about the customers in both groups are collected in 'abtest.csv'. Perform the statistical analysis to answer the following questions using the collected data.

Objective:

Statistical analysis of business Data. 
Explore the dataset and extract insights from the data.

- Explore the dataset and extract insights using Exploratory Data Analysis.
- Do the users spend more time on the new landing page than the existing landing page?
- Is the conversion rate (the proportion of users who visit the landing page and get converted) for the new page greater than the conversion rate for the old page?
- Does the converted status depend on the preferred language? 
- Is the mean time spent on the new page same for the different language users?
*Consider a significance level of 0.05 for all tests.

Data Dictionary:

- user_id - This represents the user ID of the customer visiting the website.
- group - This represents whether the customer belongs to the first group (control) or the second group (treatment).
- landing_page - This represents whether the landing page is new or old.
- time_spent_on_the_page - This represents the time(in minutes) spent by the customer on the landing page.
- converted - This represents whether the customer converted or not.
- language_preferred - This represents the language chosen by the customer to view the landing page.
- Course Business Statistics

This project used statistical analysis, a/b testing, and visualization to decide whether the new landing page of an
online news portal (E-news Express) is effective enough to gather new subscribers or not. The simulated dataset has 
certain important metrics such as converted status and time spent on the page that will help to conclude the effectiveness 
of the new landing page. Apart from that, the dependence of conversion on the preferred language will also be analyzed in this project.

Skills and Tools

Hypothesis Testing, a/b testing, Data Visualization, Statistical Inference

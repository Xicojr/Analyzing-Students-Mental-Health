# Analyzing Students Mental Health

## Project Overview

This repository contains a data analysis project developed as part of the DataCamp Data Analyst track. The focus is on exploring factors affecting the mental health of international students at a Japanese university using SQL (PostgreSQL).

The primary goal is to evaluate depression, social connectedness, and acculturative stress among students, considering both international status and length of stay. The project investigates whether staying longer in a foreign country impacts students' mental health and aims to identify key risk factors.

## Data Description

A total of 286 students were analyzed, each with a university stay ranging from 1 to 10 years. The dataset distinguishes between international and domestic students and includes results from three standardized psychological tests:

- **PHQ-9:** Total score for depression
- **SCS (Social Connectedness Scale):** Total score for social connectedness
- **ASISS (Acculturative Stress Scale for International Students):** Total score for acculturative stress

## Methodology

Data exploration and analysis were conducted using PostgreSQL, focusing on relationships between mental health scores, international status, and length of stay. The analysis seeks to replicate findings from the original university survey and explore new insights using structured querying and statistical summaries.

## Results and Discussion

As expected, the number of international students decreases as their length of stay at the university increases. Many participate in exchange programs for only part of their studies, resulting in a high number of students with just one year of stay, while in subsequent years the sample size drops significantly (more than halves from the first to the second year). Between the fifth and tenth years, there are only seven students among the 286 analyzed, which limits the strength of conclusions for this group.

A notable **11% decline** in the average Social Connectedness Scale (SCS) score is observed between the first and fifth years. In contrast, average scores for acculturative stress (ASISS) **increase by 25%**, and the depression score (PHQ-9) **rises by 14.5%**. For later years, the small number of samples restricts the reliability of further analyses.

These results indicate that a prolonged period of study abroad is associated with reduced social connectedness among international students, possibly due to factors such as friends returning home, feelings of homesickness, increasing academic challenges, or a combination of these elements.

Therefore, it is essential that universities closely monitor international students, especially those who remain for longer periods. These students face added challenges due to distance from their usual social environment and language barriers. The adoption of inclusion policies, psychological support, and social integration initiatives are important measures to promote their well-being.

Expanding this research by increasing the sample size and conducting similar studies at other universities around the world would provide a more robust and comprehensive understanding. With broader and more diverse data, institutions could develop even more effective strategies to support students seeking knowledge abroad.

## Credits

Dataset and study: Japanese international university's published research, 2019  
Project developed for DataCamp's Data Analyst track  
Analysis and interpretation by Francisco Peres

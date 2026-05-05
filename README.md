# **AMERICAN INTERNATIONAL UNIVERSITY-BANGLADESH**
---
## **PROGRAMMING IN PYTHON**
**Section:** C | **Semester:** Spring 25-26
### *Final Term Project*

> #### **Uncovering the Hidden Drivers of Student Depression**
> *An Exploratory Data Analysis of Lifestyle, Academic Pressure and Financial Stress*

**Project Members:**
| Name | Student ID | GitHub Profile |
| :-------- | :----------: | :----------: |
| Salman Sayeed | 22-49006-3 | [salman-sayeed](https://github.com/salman-sayeed) |
| Kayjer Islam | 22-49005-3 | [kayjer-islam](https://github.com/Kayjer-Islam) |

### Problem Defination
#### Dataset Selection
For this project, I have selected the Student Depression Dataset sourced from Kaggle. This dataset contains 27,901 records and 18 columns, covering a diverse range of demographic, academic and lifestyle variables.
#### Problem Statement
Student mental health is a growing global concern. This dataset represents the intersection of personal lifestyle choices (sleep, diet), academic environment (pressure, satisfaction), and external socio-economic factors (financial stress). By analyzing this data, we aim to move beyond anecdotal evidence and identify the specific pressures that correlate most strongly with depression in a student population.
#### Analytical Questions
Which factors are most strongly associated with student depression?
Student depression is influenced by many academic, financial and personal factors. Identifying which variables show the strongest association helps highlight the most important risk indicators. This can guide universities, families and policymakers toward targeted interventions and support systems.

How do lifestyle habits differ between depressed and non-depressed students?
Lifestyle behaviors such as sleep, diet, work/study hours and satisfaction levels are closely linked to mental health. Understanding how these habits differ between groups can reveal patterns that may contribute to poor mental wellbeing and help promote healthier daily routines for students.

Does academic and financial stress significantly increase depression risk?
Academic pressure and financial stress are common challenges faced by students worldwide. Investigating their relationship with depression can provide evidence of how stress impacts mental health and emphasize the importance of stress management and financial support programs.

### Findings & Discussion
#### The Stress-Depression Link (Q3)
There is a moderate positive correlation (0.55) between the cumulative stress_index and depression. This numerical relationship, visualized in our scatter plot, confirms that as academic, financial, and work pressures increase, the probability of depression rises in a predictable pattern.

#### The Impact of Academic Workload (Q2)
The data reveals a significant "Workload Gap." Depressed students average 7.81 hours of work/study per day, compared to 6.24 hours for non-depressed students. This suggests that high academic demand is one of the most prominent lifestyle factors associated with poor mental health outcomes in this population.

#### Sleep Deprivation Patterns (Q2)
Our boxplot analysis shows that depressed students consistently obtain less rest, averaging 6.20 hours of sleep versus 6.53 hours for their peers. While the mean difference is small (~20 minutes), the distribution shows that a larger portion of the depressed subgroup falls into critically low sleep ranges, which acts as a compounding stressor.

#### Hereditary vs. Environmental Risk (Q1)
Family history is a tangible risk factor. Students with a history of mental illness have a depression rate of 61.3%, while those without it have a rate of 56.0%. This 5.3% difference indicates that while external factors (stress) are major drivers, genetic or home-environment history provides a higher baseline risk.

#### Demographic Neutrality (Q1)
Contrary to many social assumptions, gender does not appear to be a significant predictor of depression in this dataset. The rates were nearly identical for Males (58.6%) and Females (58.5%). This finding is crucial because it suggests that the drivers of depression in this student group are more closely tied to lifestyle and pressure than to demographic identity.

#### Summary of Findings Table

| Analytical Question  | Key Finding  |   Supporting Evidence |   
|---|---|---|
| Q1: Demographics  | Gender is neutral; Family History is a minor risk.  | 5.3% difference in depression rates between family history groups.  |
| Q2: Lifestyle  | High study hours and low sleep are primary traits.  | Depressed students study 1.5+ hours more per day and sleep less on average.  |
| Q3: Stress  | Cumulative stress is the strongest predictor.  | Correlation coefficient of 0.55 between Stress Index and Depression. |

### Limitations & Conclusion
#### Project Limitations
Every data science project has constraints. Acknowledging these ensures that your findings are interpreted correctly.Correlation vs. Causation: While our analysis shows a strong link (0.55 correlation) between stress and depression, we cannot definitively say that high stress causes depression. It is equally possible that students suffering from depression struggle more with their workload, leading to higher perceived stress.Self-Reported Survey Data: The dataset relies on students' subjective reporting. Factors like "Social Desirability Bias" might lead students to under-report depression or over-report study hours.Missing Contextual Variables: Our model lacks data on physical exercise, diet, social support networks, and access to healthcare. These "buffer" factors likely explain the resilient students we found who have high stress but no depression.Snapshot in Time: This data represents a single point in time. It does not capture how student wellness fluctuates throughout an academic year (e.g., during finals week vs. the start of a semester).
#### Final Conclusion
This project successfully utilized a structured data science roadmap to investigate the crisis of student wellness.

Our investigation into 27,898 student records concludes that academic workload and sleep deprivation are the primary lifestyle markers associated with depression. While demographic factors like gender showed no significant impact, the cumulative Stress Index emerged as the strongest predictor of mental health struggles. To improve student outcomes, institutions should focus on workload management and promoting healthy sleep hygiene rather than focusing solely on demographic risk groups.

# Employee-Attrition-Visual-Analytics

*Tags: Power BI, Employee Attrition, Dashboard*

## 1. Project Overview

Employees are the backbone of any organization. Its performance is heavily based on the quality of the employees and retaining them. With employee attrition, organizations are faced with a number of challenges:

- Expensive in terms of both money and time to train new employees
- Loss of experienced employees
- Impact on productivity
- Impact on profit
 
The primary objective of this project was to answer one critical business question: **“What factors are driving employee attrition, and how can organizations design effective retention strategies?”** By analysing satisfaction levels, job roles, working experiences, demographics, and work-life balance, the project aims to deliver insights that HR leaders can use to reduce turnover and improve employee engagement.

### 2. Objectives

The organization aims to understand the factors driving employee attrition to reduce turnover, retain talent, and enhance both productivity and profitability. Addressing attrition is critical to maintaining organizational performance and sustaining competitive advantage.

### 3. Requirements

The project requires analysis of 04 categories (Demographics, Job/Dept, Experince/Promotion, and Performance Rating). For example, each category can be addressed by answering questions as follows.

1. What is the age profile of our workforce? The system must compute an "Average Employee Age" (shown as 36.92) and bin employees into groups (e.g., 20-30, 30-40) for the "Age Distribution" histogram.
2. Does gender or marital status impact retention? The data must allow filtering by Gender (Male/Female) and Marital Status (Single/Married/Divorced) to populate the "Employee Gender/Marital Status by Department" chart.
3. Does educational background matter? The dashboard requires "Education Field" data (e.g., Life Sciences, Medical) to cross-reference with attrition counts.
4. Which roles are experiencing the highest attrition? The system needs to aggregate "Yes" attrition counts by "Job Role" (e.g., Laboratory Technician vs. Sales Executive).
5. Does travel frequency drive employees away? You need to segment employees by "Non-Travel," "Travel_Rarely," and "Travel_Frequently" to calculate the percentages (e.g., 18.84% frequent travelers).
6. Are salary structures competitive across roles? The dashboard requires averaging "MonthlyIncome" and "MonthlyRate" by Job Role to create the income comparison line charts.
7. Are we losing new hires or long-term veterans? The data must support a histogram of "Attrition by YearsAtCompany" to identify if spikes occur at specific tenures (e.g., year 1 vs. year 5).
8. Does career stagnation trigger attrition? You need to calculate the "Average of YearsInCurrentRole" and compare it against attrition status to see if those who leave have been in their role longer without change.
9. Is there a pattern of job-hopping? The model needs to count "NbrCompaniesWorked" to see if employees with a history of many previous jobs are more likely to leave.
10. Is high performance linked to retention or flight risk? The dashboard requires comparing "Average of PerformanceRating" against "Average of JobInvolvement" to see if disengaged high-performers are leaving.
11. Does work-life balance impact turnover by role? The system must calculate the average "WorkLifeBalance" score for each Job Role (e.g., Managers vs. Sales Reps).
12. Are specific satisfaction areas failing? You need pivot tables that count employees by satisfaction scores (1-4) for Environment, Relationships, and Job Satisfaction, grouped by Department.

## 4. Flowchart

<img width="600" height="448" alt="image" src="https://github.com/user-attachments/assets/119e6c75-2d1f-4160-9800-2ddc4b244edd" />

## 5. References

Knowledge at Wharton. (2017, July 19). Why employee turnover costs more than you think. University of Pennsylvania. https://knowledge.wharton.upenn.edu/article/why-employee-turnover-costs-more-than-you-think/

Plum HQ. (2023, March 14). The impact of attrition on productivity: Costs beyond hiring. Plum. https://www.plumhq.com/blog/impact-of-attrition-on-productivity

Quest Journals. (2020). Study of employee attrition and its footprint on organization performance. Quest Journal of Research in Humanities and Social Science, 13(3), 122–126. https://www.questjournals.org/jrhss/papers/vol13-issue3/1303122126.pdf

---

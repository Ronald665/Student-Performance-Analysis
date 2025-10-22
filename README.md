# **Student Mathematics Performance Analysis Report**

## **1. Introduction**

This report presents the results of an Exploratory Data Analysis (EDA) carried out to understand the factors influencing students’ 
performance in mathematics. The dataset comprises 1,000 students with attributes such as gender, race/ethnicity, parental education, lunch type, and test preparation status.
The goal is to uncover performance patterns, identify key demographic or socio-economic influences, and recommend strategies for improving academic outcomes.

## **2. Population Overview**

* **Male students:** 482
* **Female students:** 518
* **Gender ratio:** Approximately **1:1**

<img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/c1535e67-6602-4e49-8db2-4ab217ac0b91" />

## **3. General Performance in Mathematics**

* **Average (Mean):** 66.1
* **Median:** 66
* **75th Percentile:** 77

**Insights:**
Overall student performance in mathematics centers around the mid-60s, indicating that while the general competency level is satisfactory, there is room for improvement.
Most students scored within the **60–79** range, reflecting a moderate level of proficiency across the population.

<img width="500" height="350" alt="image" src="https://github.com/user-attachments/assets/32b4bcaa-d671-4229-954a-68d6fd51eee5" />

**Recommendation:**
Schools should strengthen academic reinforcement programs such as after-school tutoring, peerassisted learning, and early performance monitoring to support students near or below the national average.

## **4. Gender-Based Performance**

| Gender | Mean | Median | 75th Percentile |
| ------ | ---- | ------ | --------------- |
| Male   | 68.7 | 66     | 79              |
| Female | 63.6 | 66     | 74              |

**Findings:**

* Male students performed better overall, with higher mean and 75th percentile scores.
* The median score for both genders remained the same, suggesting similar central tendencies but higher variability among males.

**Interpretation:**
The results suggest possible differences in learning confidence, interest in mathematics, or classroom engagement between genders.

**Strategic Recommendation:**

* Encourage female participation in STEM related programs through mentorship, math clubs, and motivational workshops.
* Incorporate genderresponsive teaching techniques to boost engagement and confidence among female students.

---

## **5. Ethnic/Racial Group Performance**

| Ethnic Group | Mean | Median | 75th Percentile |
| ------------ | ---- | ------ | --------------- |
| Group A      | 61.6 | 61     | 71              |
| Group B      | 63.4 | 63     | 74              |
| Group C      | 64.5 | 65     | 74              |
| Group D      | 67.4 | 69     | 77              |
| Group E      | 73.8 | 74.5   | 85              |

**Observations:**

* **Group E** students recorded the highest performance, followed by **Group D**.
* Groups A–C lagged behind the national average of 66.
* Male students in Group E had the highest median score (78), outperforming all other subgroups.
  
<img width="650" height="400" alt="image" src="https://github.com/user-attachments/assets/43b6cf7e-dcb5-4dd0-ac54-98675e0bed1a" />

**Interpretation:**
Cultural or environmental factors may play a role in these disparities. Students from Groups D and E likely benefit from strong academic motivation, supportive family structures, or access to better educational resources.

**Strategy:**

* Conduct focus group discussions with high performing groups to identify successful study habits and environmental factors.
* Develop targeted academic support for underperforming groups through mentorship and resource access.
* Investigate teaching methods or cultural factors contributing to Group E’s success for replication across other groups.

---

## **6. Impact of Test Preparation**

| Test Preparation | Mean | Median |
| ---------------- | ---- | ------ |
| Completed        | 70   | 69     |
| None             | 64.1 | 64     |

**Findings:**

* Students who completed a test preparation course scored significantly higher.
* Male students benefited slightly more (mean increased from 66.7 → 72.3) compared to females (61.7 → 67.2).
  
<img width="501" height="210" alt="image" src="https://github.com/user-attachments/assets/998346cb-d924-4836-97d3-820aa6429309" />

**Interpretation:**
This demonstrates the strong positive impact of structured test preparation on student performance and confidence.

<img width="496" height="284" alt="image" src="https://github.com/user-attachments/assets/d632602f-ad9f-4fbf-8e80-56b278bd1ae9" />

**Recommendations:**

* Expand access to test preparation programs, especially for lower-income or underperforming students.
* Implement digital and peer-led preparatory platforms for flexible learning.
* Encourage schools to integrate mock assessments as wll as structured revision programs into their teaching schedules.

---

## **7. Effect of Lunch Type (Socio-Economic Indicator)**

| Lunch Type   | Mean | Median |
| ------------ | ---- | ------ |
| Standard     | 70.0 | 69     |
| Free/Reduced | 58.9 | 60     |

**Insights:**
Students with a standard lunch plan outperformed those on free/reduced lunches suggesting a connection between nutrition and academic success. The performance gap was more pronounced among male students.

<img width="550" height="309" alt="image" src="https://github.com/user-attachments/assets/a34bcf8a-63aa-46f2-9862-c27c106d9b28" />

**Interpretation:**
This emphasizes the influence of socio economic factors on educational outcomes. Poor nutrition may limit concentration and learning retention.

<img width="500" height="308" alt="image" src="https://github.com/user-attachments/assets/317b7238-08a6-48c7-bd9a-3852f28f7828" />

**Recommendations:**

* Collaborate with nutrition focused programs to provide balanced meals for low-income students.
* Schools can introduce meal subsidies or sponsorship schemes to minimize inequality.

## **8. Parental Education Level**

| Education Level    | Mean | Median |
| ------------------ | ---- | ------ |
| High School        | 62.1 | 63     |
| Some High School   | 63.5 | 65     |
| Some College       | 67.1 | 67.5   |
| Associate’s Degree | 67.9 | 67     |
| Bachelor’s Degree  | 69.4 | 68     |
| Master’s Degree    | 69.7 | 73     |

**Findings:**

* Student performance improves with higher parental education levels.
* Those with parents holding a Master’s degree achieved the highest median score (73).
* Male students with parents holding a Master’s degree showed exceptional performance (median 79).
  
<img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/fd516a36-8913-4075-928f-f5edaebc6a15" />

**Interpretation:**
Educated parents likely provide more academic guidance, structured learning support, and motivation.

**Recommendation:**

* Establish parent engagement initiatives to guide less educated parents on supporting their children academically.
* Provide home learning materials and regular performance updates to strengthen family involvement.

## **9. Combined Effect of Race and Parental Education**

Students from **Group E** whose parents had a Master’s degree achieved the highest overall median score (81).
This reflects the compounding advantage of cultural, socio economic, and educational factors, creating an environment highly conducive to academic success.

<img width="4800" height="3200" alt="heatmap_math_scores" src="https://github.com/user-attachments/assets/85df5af9-950f-474a-b0ec-dffc60eff449" />


**Strategy:**

* Develop targeted enrichment programs for lower performing race education groups.
* Foster equity focused policies ensuring equal access to learning resources.


## **10. Correlation with Math Pass Rate**

Positive correlation with passing (score > 66):

* Standard lunch
* Race/Ethnicity Group E
* Completed test preparation
* Male gender
* Parents with Bachelor’s or Master’s degree

Negative correlation:

* Free/reduced lunch
* No test preparation
* Lower parental education
  
<img width="900" height="500" alt="image" src="https://github.com/user-attachments/assets/d59d4615-7251-4cd5-8828-3c04129c1549" />

**Interpretation:**
Students’ academic success is most strongly influenced by nutrition, preparation, and parental background factors that can be improved through policy and community intervention.

---

## **11. Strategic Recommendations Summary**

1. **Enhance Academic Support**

   * Implement tutoring sessions, remedial programs, and early performance tracking for at-risk students.
2. **Expand Access to Test Preparation**

   * Offer free or subsidized test prep and digital mock exams for improved readiness.
3. **Strengthen Nutrition Programs**

   * Collaborate with local organizations to ensure balanced meals for underprivileged students.
4. **Increase Parental Involvement**

   * Create parent school collaboration programs that equip parents with learning tools.
5. **Promote Gender Inclusivity**

   * Support female engagement in mathematics through clubs, mentorship, and confidenc -building activities.
6. **Equity and Cultural Learning**
   
   * Study best practices from high performing ethnic groups and replicate them across others.
.

---

## **12. Conclusion**

The analysis reveals that mathematics performance is shaped by multiple interdependent factors gender, race, socio economic background, parental education, and test preparation.
By addressing these through targeted academic initiatives, inclusive education policies, and socio economic support systems, schools can significantly narrow the performance gap and foster a more equitable learning environment.

---

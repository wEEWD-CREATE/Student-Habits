# Student-Habits
## Student Habits vs Academic Performance

Link to Dashboard: 

## Resources

1. Data Source
- Student Habits vs Academic Performance: https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance/data
   
2. Software
- Power BI
- Excel

## 1. Introduction

Problem Description

In the digital age, students are increasingly exposed to various lifestyle choices that may influence their academic performance. Factors such as screen time, sleep habits, mental health, physical activity, and study routines all contribute to student success or struggle. However, it is unclear which of these factors have the most signficant impact on academic outcomes like GPA.
  
Objective

This analysis aims to explore and identify the key lifestyle factors that influence students' academic performance, measured by their exam scores. By leveraging data visualization and statistical techniques (including correlation and regression analysis), the goal is to uncover patterns and relationships between GPA and daily habits such as Netflix usage, TikTok time, sleep duration, diet quality and more.

Ultimately, this project provides data-driven insights to inform healthier habits and better academic planning for students.

## 2. Exploratory Data Analysis (EDA)

Dataset Overview

The dataset contains various features related to student lifestyle and academic performance, including:

- Exam Score, academic_performace: Final exam score (used as a proxu for GPA)
  
- Netflix_hours, social_media_hours: Average daily entertainment time

- Sleep_hours, study_hours_per_day: Time allocation for sleep and study

- mental_health_rating: Self-reported mental well-being (scale 1-10)

- diet_quality, exercise_frequency, extracurricular_participation: Indicators of physical health and engagement

- attendance_percentage: Percentage of classes attended

- age, gender: Student information

Descriptive Statistics

Summary statistics were generated to understand the distribution of key variables:

![image](https://github.com/user-attachments/assets/2b330fce-7927-444a-a414-1e29d41f338c)

Visualization Hightlights

Several visualization were created to explore data distributions and relationships:

- Scatter plot: suggesting that getting more sleep may be associated with better exam performance, though the relationship appears to be quite dispersed.
- Scatter plot: implying that increased on social media may be linked to lower academic performance, regardless of gender.
- Bar Chart compares the correation coefficients between exam scores and two acitivies: Netflix_hour (Corr_Netlix) and Social_media_hours (Corr_SocialMedia)
   
Key Observations

- Both activies, sleep_hours and social_media show a minor impact on exam scores.

## 3. Relationship Analysis

In this section, we explore how individual lifestyle factors relate to academic performance. The goal is to identify whether certain behaviors - such as sleep_hours, study_hours_per_day or entertainment_hours - are associated with higher or lower GPA (exam scores).

Correlation Analysis

To examine linear relationships, Pearson correlation coefficients were calculated between exxam_score and other variables.

![image](https://github.com/user-attachments/assets/5b5a47a3-19fc-4233-99c1-b0da83c0c0ea)

Note: 

Positive values indicate a direct relationship, while negative values suggest an inverse relationship.

I applied simple linear regrssion models to estimate how individual variables impact GPA. For example:

exam_score = a + b * study_hours_per_day

The slope(b) indicates how much the exam score is expected to change with one additional hour of studying.

Visual Insights

Scatter Plots show a noticeable negative correlation between Social Media and Exam Score and a positive correlation with Hours-sleep and Exam Score.

Social Media vs Exam Score

![image](https://github.com/user-attachments/assets/a80b7711-a075-4a62-a9e1-0a2ff7603a92)

Hours-sleep and Exam Score

![image](https://github.com/user-attachments/assets/d8d3e47d-86bf-4682-9a55-3d7cecf717e1)

A bar chart comparing correlation coefficient clearly highlights which habits help or hurt performance the most.

![image](https://github.com/user-attachments/assets/afa20dd5-ad7f-469e-a28b-c890d315e806)

Key Findings

- More study time and mental health rating are strongly an important role in predicting higher academic performance.

- Excessive entertainment time such as social media and Netflix, appears to have a detrimental effect on exam scores.

- Sleep hours and attendance play a moderately positive role, suggesting that better rest may support cognitive performance.

## 4. Conclusion

This analysis highlights the influence of various lifestyle factors on students'academic performance, meansured by exam scores. Based on correlation and regression analysis, several key insight emerged:

Key Takeaways:

- Study time per day and mental health are the strongest positive predictors of higher exam performance.

- Excessive time on social media shows negative correlations with GPA (exam scores).

- Sleep duration and attendance have also a moderate positive impact, reinforce the important of adequate rest.

- Other factor such as diet quality, part-time job, internet quality and parental educational level showed weaker but still meaningful associations with performance.

Practical Implications:

Student aiming to improve academic outcomes may benefit from:

- Reducing time spent on passive entertainment (especially short-form content like Facebook, Tiktok, Instagram,...)

- Prioritizing consistent study schedules and class attendace.

- Maintaining good sleep hygience and mental well-being.

In summary, balanced daily habits-combining focused study, healthy lifestyle, and limited distractions-appear to be the most effective strategy for achieving academic success.
  



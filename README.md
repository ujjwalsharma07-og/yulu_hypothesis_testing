# 🛴 Yulu Hypothesis Testing Case Study

## 📝 Overview  
This project involves a statistical hypothesis testing analysis on Yulu bike-sharing data, completed as part of the **Scaler Data Science program**. The goal is to analyze user behavior and validate key assumptions related to ride patterns, day-wise usage, and other operational metrics to help optimize business decisions.

The project leverages Python libraries such as **Pandas**, **NumPy**, **SciPy**, and **Matplotlib** to clean data, perform hypothesis tests, and visualize results.

---

## 🧰 Tools & Technologies  
- Python (Jupyter Notebook / Google Colab)  
- Pandas, NumPy  
- SciPy (for hypothesis testing)  
- Matplotlib, Seaborn (for visualization)

---

## 📁 Dataset  
The dataset consists of transactional data from Yulu bike rides, including:

- Ride durations  
- Customer demographics (gender, membership type)  
- Usage patterns by day and time  
- Payment types and ride counts

Dataset timeframe: **January 2021 – December 2021**  
Source: Scaler Data Science Program

---

## 🔍 Analysis & Hypotheses Tested

1. **Hypothesis 1: Average ride duration differs between weekdays and weekends**  
   - Used two-sample t-test to compare mean ride durations  
   - Result: Statistically significant difference, with longer rides on weekends

2. **Hypothesis 2: Male and female customers have different average ride counts per month**  
   - Used two-sample t-test for independent groups  
   - Result: No significant difference in ride counts between genders

3. **Hypothesis 3: Membership users have higher average ride durations than casual users**  
   - Applied t-test to membership vs casual user groups  
   - Result: Membership users do have significantly longer rides

4. **Hypothesis 4: Peak usage occurs during evening hours (5 PM–9 PM) vs other times**  
   - Analyzed hourly ride counts using chi-square goodness-of-fit test  
   - Result: Confirmed evening peak usage with significantly higher rides

---

## 🧠 Key Insights  
- 📈 Ride durations are longer on weekends (~12% increase) compared to weekdays  
- 👥 No significant gender difference in ride frequency, indicating equal engagement  
- 🔑 Membership users are more engaged, with ~20% longer average ride times  
- 🕔 Evening hours (5 PM to 9 PM) account for nearly 40% of total rides, confirming peak demand times

---

## 📊 Visualizations  
- Distribution plots of ride durations by day type  
- Bar charts comparing average rides by gender and membership  
- Hourly heatmap showing ride counts across time periods

---
Recommendations:
As casual users are very less Yulu should focus on marketing startegy to bring more customers. for eg. first time user discount, friends and
family discounts, referral bonuses etc.
On non working days as count is very low Yulu can think on the promotional activities like city exploration competition, some health
campaigns etc.
In heavy rains as rent count is very low Yulu can introduce a different vehicle such as car or having shade or protection from that rain.
Based on above if you can provide me good recommendation and how business case should be presented, it will help
Central Limit Theorem - You all must have studies about the CLT in previous classes.
According to this theorem, the distribution of sample means approximates a normal distribution as the sample size gets larger, regardless of
the population's distribution.
In other words, if we find the mean of a large number of independent random variables, the mean will follow a normal distribution,
irrespective of the distribution of the original variables.
In practice, sample sizes equal to or greater than 30-40 are often considered sufficient for the CLT to hold.
Hence, the sample size being large enough, we don't need to worry about the non-normality of distribution of the data set in hand before
applying the tests.
Eventually, as the sample size gets larger, the distribution of sample means will fall into a normal or near normal shape.

## 📌 Conclusion  
This hypothesis testing study highlights critical usage patterns in Yulu’s bike-sharing system. Findings suggest targeted promotions on weekends and evenings and reinforce the value of membership programs for customer retention.

---

## 📄 Project Report  
Detailed analysis and results can be found in the PDF report:  
[📄 Yulu Hypothesis Testing Case Study (Colab)](https://github.com/ujjwalsharma07-og/yulu_hypothesis_testing/blob/main/Yulu_Hypothesis%20Testing%20_case_study.pdf)
 

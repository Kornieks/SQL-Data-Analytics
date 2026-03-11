# SQL-Data-Analytics

# Email Marketing Performance Analysis

## Project Overview

This project analyzes the performance of email marketing campaigns across different countries.
The analysis combines email campaign activity with user registration data to evaluate engagement and acquisition metrics.

The dataset includes information about emails sent, email opens, link clicks, and new user registrations.

The final dataset was used to build a marketing performance dashboard.

---

## Business Problem

Marketing teams need to understand how email campaigns influence user engagement and registrations.

This project answers the following questions:

* How many emails are sent each day?
* What is the email open rate and click rate?
* Which countries generate the most engagement?
* How many new users register each day?


## SQL Analysis

The SQL query performs the following steps:

1. Calculate email campaign activity

   * Emails sent
   * Emails opened
   * Email link clicks

2. Aggregate daily user registrations.

3. Combine marketing activity and registrations using `UNION ALL`.

4. Aggregate results by **date and country** to create a dataset for the dashboard.

---

## [Dashboard](https://public.tableau.com/app/profile/kseniia.kornienko/viz/Emailmetrics_17652032274470/EmailMetricsPerformance)

<img width="1414" height="779" alt="Screenshot 2026-03-10 at 22 02 53" src="https://github.com/user-attachments/assets/7aba161c-d219-40b5-afba-70d07e6f0fa0" />

<img width="1265" height="338" alt="Screenshot 2026-03-10 at 22 04 53" src="https://github.com/user-attachments/assets/ab6ad7c9-d45b-476a-9184-24fd2592d5f3" />

---

## Key Metrics

The analysis focuses on the following marketing metrics:

* **Open Rate** = Opens / Emails Sent
* **Click Rate** = Clicks / Emails Sent
* **CTOR** = Clicks / Emails Open
* **Registrations** = Number of new user accounts

These metrics help evaluate the effectiveness of email marketing campaigns.

## Business insights 

* Email engagement is declining. Open Rate (35.49%), Click Rate (3.85%), and CTOR (10.86%) all show a downward trend compared to last month and last year, indicating decreasing user interaction with email campaigns.

* The biggest drop occurs between opens and clicks. While many users open emails, relatively few click (only ~20K clicks from 187K opens), suggesting that email content or calls-to-action may need improvement.

* Registrations are highest mid-week. Tuesday and Wednesday generate the most registrations (~4.7K–4.9K), while weekends show the lowest activity.

* Engagement metrics are consistent across weekdays. Open, click, and CTOR rates vary only slightly, indicating that send day has limited impact on engagement.

* Key markets drive most activity. The majority of emails and engagement come from a few countries, particularly the United States, India, Canada, and the United Kingdom.

**Recommendations:** Focus on improving email content and CTA effectiveness, prioritize campaigns mid-week, and use segmentation or A/B testing to increase click-through performance.

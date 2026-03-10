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

## Dashboard



## [Tableau](https://public.tableau.com/app/profile/kseniia.kornienko/viz/Emailmetrics_17652032274470/EmailMetricsPerformance)

---

## Key Metrics

The analysis focuses on the following marketing metrics:

* **Open Rate** = Opens / Emails Sent
* **Click Rate ** = Clicks / Emails Sent
* **CTOR ** = Clicks / Emails Open
* **Registrations** = Number of new user accounts

These metrics help evaluate the effectiveness of email marketing campaigns.



# 📊 Customer Churn Analysis with Power BI

> **"Every customer who leaves your business has a reason. My job is to find out why — and help you fix it."**
> — *Rhoda, Data Analyst & Business Storyteller*

---

##  Table of Contents

1. [Introduction](#introduction)
2. [The Business Problem](#the-business-problem)
3. [Project Goal](#project-goal)
4. [Understanding the Dataset](#understanding-the-dataset)
5. [Tools I Used](#tools-i-used)
6. [Step-by-Step Process](#step-by-step-process)
7. [Dashboard Breakdown](#dashboard-breakdown)
8. [What I Found (Key Insights)](#what-i-found-key-insights)
9. [Why These Things Are Happening (Root Causes)](#why-these-things-are-happening-root-causes)
10. [What the Business Can Do (Recommendations)](#what-the-business-can-do-recommendations)
11. [Why This Matters (Business Impact)](#why-this-matters-business-impact)
12. [Dashboard Preview](#dashboard-preview)
13. [About Me](#about-me)
14. [Get In Touch](#get-in-touch)

---

## Introduction

In today’s world, keeping customers is just as important as getting new ones. But what happens when customers start leaving? And why are they leaving in the first place?

That’s the story I wanted to uncover in this project. I took raw customer data from a telecom company and turned it into a powerful, easy-to-understand dashboard using **Power BI**. My goal was to help decision-makers understand what’s really going on — and what they can do about it.

---

## The Business Problem

Imagine owning a business where people can cancel their service at any time. You work hard to bring customers in, but suddenly, they start leaving. You notice the numbers dropping, and you’re not sure why. This is called **customer churn**.

**Churn** simply means customers are **leaving your company**. They might cancel their internet service, switch to a competitor, or stop paying for a product.

For a telecom company, high churn means **lost revenue**, **lower trust**, and **high marketing costs** because now you have to work twice as hard to find new customers.

For this project, I wanted to check through the customer data because I noticed some customers were dropping.

📉 1,869 customers out of 7,043 had churned. That’s a 26.5% churn rate.

But it wasn’t just numbers.

💸 It meant they lost 2.86 million in revenue due to churned customers.

So,  I Asked the Right Questions…
Who exactly are the customers that are leaving?

When do they leave?

How long did they stay?

How were they paying?

What services were they using?

Did tenure or contract type matter?

Were they male or female?

Was the monthly bill too high?

These are the questions every business should be asking, but often don’t — until it’s almost too late.


## Project Goal

My goal was to:

* Understand why customers are leaving (churning)
* Show this information clearly using dashboards
* Help business leaders make smart decisions to reduce churn

---

## Understanding the Dataset

The data came from a telecom company. It contains information about **7,043 customers**.

Each customer record included:

* **Who they are** (age group, gender, partner status)
* **What services they use** (internet, phone, streaming, etc.)
* **How they pay** (credit card, bank transfer, electronic check)
* **How long they’ve been a customer**
* **Whether they left (churned) or stayed**

---

## Tools I Used

* **Power BI**: To build interactive and beautiful dashboards
* **Power Query**: To clean and prepare the data
* **DAX (Data Analysis Expressions)**: To create custom metrics
* **Excel**: For some initial exploration

---

## Step-by-Step Process

### 1. Data Cleaning

* Removed any errors or blanks
* Made sure all the information was in the right format

### 2. Data Modeling

* Connected different parts of the data to each other
* Created calculations like "Churn Rate" and "Total Customers"

### 3. Visualization (Building the Dashboard)

* Created charts, graphs, and slicers to explore patterns
* Made the dashboard easy to navigate for anyone, even non-technical users

### 4. Storytelling

* Organized the visuals to answer business questions step by step

---

## Dashboard Breakdown

Here's what you'll find on the dashboard:

* **Summary Cards**: Total customers, total churned, overall churn rate
* **Customer Profile**: Who is most likely to leave based on age, gender, and more
* **Service Insights**: Are certain services linked to more churn?
* **Payment Behavior**: Does the payment method affect loyalty?
* **Contract Type**: Are short-term customers leaving more?
* **Tenure and Charges**: How long customers stay and how much they pay

---

## What I Found (Key Insights)

### 1. Churn Rate: 26.54%
Out of 7,043 total customers, 1,869 had left. That’s over one in every four customers walking away. Huge red flag 🚩.

### 2. The Monthly Charges Trap
The average monthly charge stood at $64.76.

But here's what the scatter plot (Tenure vs. Monthly Charges vs. Churn) revealed:

➡️ Most of the customers who churned were paying high monthly bills but had low tenure.

Translation? They didn't stay long, because they were likely overwhelmed by the cost early on.

Insight: High monthly bills + low loyalty = high churn risk.

### 3. Contract Type

Month-to-month customers had the highest churn. (1.7k churned)

Two-year contract customers had 0 churn.

One-year contracts had relatively low churn as well.

Insight: The longer the contract, the lower the churn. Month-to-month feels convenient, but it’s also disposable. No skin in the game.

### 4. Internet Service Matters
Among customers:

Those using Fiber Optic had high churn (1.3k).

DSL users had significantly lower churn.

No Internet users also showed lower churn.

Insight: Fiber Optic service users are the ones leaving most. Possibly due to performance, pricing, or unmet expectations.

### 5. Gender? Not the Issue
Both male and female customers had similar churn numbers (approx. 900 each). Gender wasn’t a defining factor.

Insight: Focus should shift to behavior, not demographics.

### 6. Payment Method Patterns
Surprisingly, electronic checks were used by most churned customers.

1.1k churned customers used electronic checks.

All other payment methods had much lower churn.

Insight: Payment method may correlate with churn behavior. Electronic check users could be price-sensitive or find it harder to manage recurring payments.

### 7. Tenure: The Silent Killer
The churn trend over tenure shows a massive drop in churn after just a few months.

Most customers leave within their first 3-6 months.

The longer a customer stays, the less likely they are to churn.

Insight: Retention efforts must focus heavily on the first 6 months.

---

## Why These Things Are Happening (Root Causes)

* **Flexibility Without Value**: Month-to-month users don’t feel locked in, so if service or price doesn’t meet their expectations, they leave easily.

* **Poor Onboarding Experience**: New customers might not fully understand the services or face issues without enough support.

* **Billing Hassles**: Electronic checks may lead to payment delays or confusion, making customers frustrated.

* **Lack of Support**: No technical support means customers feel stranded when issues arise.

* **Perceived Overpricing**: When customers don’t see the value in what they’re paying for, they look elsewhere.
---
## Recommendations

### 1. Shift Focus to Long-Term Contracts
Encourage customers to switch from month-to-month to 1- or 2-year contracts. Offer discounts, loyalty bonuses, or added value for longer contracts. Make the long-term plan feel irresistible.

### 2. Implement a First 90-Day Retention Strategy
The first 3 months are make-or-break. Create onboarding journeys. Assign a customer success manager. Send weekly value emails. Offer check-ins. Make them feel like VIPs early on.

### 3. Re-evaluate Fiber Optic Service Experience
Since churn is highest here: Conduct customer interviews.Check complaint records and service quality. Possibly revise pricing or offer performance guarantees.

### 4. Improve Billing Transparency
Many churned customers were on high bills early. Introduce bill previews. Break down charges more clearly. Allow custom plans or bundle discounts.

### 5. Target Payment Method Optimization
Encourage stable auto-payment methods over electronic checks. Offer discounts for bank drafts or card payments.Create nudges to switch payment methods at sign-up.

### 6. Run Predictive Churn Models
Use this kind of dashboard to not just analyze the past, but predict the future. Identify at-risk customers.Automate retention campaigns for them.

### 7. Segment Customers for Personalization
Different customers churn for different reasons. Segment by tenure, payment method, and contract. Tailor communication accordingly.



## Why This Matters (Business Impact)

If these strategies are implemented, the business could:

* **Reduce churn by up to 20%** in the first year
* **Increase revenue** through higher customer retention
* **Build stronger customer relationships** and trust
* **Save on marketing costs** by not needing to replace lost customers

---

## Dashboard Preview

![image](https://github.com/user-attachments/assets/311bb121-8698-45c7-8d3e-86e31a2e92a7)

---

## About Me

I'm **Rhoda**, a passionate and detail-driven Data Analyst with a First-Class degree in Agricultural Economics. I'm also a certified Six Sigma Yellow Belt and a professional storyteller with data.

I believe data is more than numbers. It’s a voice, and it’s my job to make sure that voice is heard loud and clear by the people who need to act on it.

If you're looking for someone who can connect business goals to real data insights, let's talk.

---

## Get In Touch

* **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/your-profile)
* **Portfolio**: [Your Portfolio Website](https://yourportfolio.com)
* **Email**: [your.email@example.com](mailto:your.email@example.com)

---

> *"Good data shows you what happened. Great data analysis shows you what to do next."*
> — *Rhoda*


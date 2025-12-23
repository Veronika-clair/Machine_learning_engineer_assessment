# Take-Home Assignment: Predicting Next Paycheck Size

## Background

At **Clair**, we're on a mission to create financial freedom for America’s workers by giving them access to free wage advances—so they can be paid as soon as they clock out of work.

Clair partners with Plaid and provider X to receive income data for our users. Using this data, Clair underwrites employees for wage advances to provide liquidity between paychecks. When payday arrives, Clair recoups the advanced funds by debiting the employee’s bank account.

To enable this repayment, Clair must be able to accurately predict when the next paycheck will land, and how much the paycheck is expected to be.

This assignment focuses on predicting the **size of the next paycheck** using historical paycheck deposit data.

---

## Objective

The goal of this exercise is **not** to build a highly optimized or production-ready model.

We expect you to spend **no more than 3–4 hours** on this assignment. As such, we do **not** expect exceptional model performance. Instead, we are primarily interested in:

* How you explore and reason about the data
* Your approach to feature engineering and modeling
* How you evaluate model performance
* How clearly you document your assumptions and decisions

---

## Data Access

You will use a cloud-hosted PostgreSQL database containing historical paycheck information.

**Database details:**
* **Host:** `pg-285c4482-getclair-7a3a.a.aivencloud.com`
* **Port:** `10594`
* **Database:** `assessment`
* **Table name:** `next_paycheck_size`

Username and password credentials will be shared with you separately via email.

---

## Part I: Model Development

### Task

Build a model that predicts the **next paycheck amount** for an employee based on their historical paycheck deposits.

### Deliverable

* A **Jupyter Notebook** demonstrating how did you approach the problem

---

## Part II: Deployment Design (Conceptual)

In a separate section of your notebook or in a document, outline **how you would deploy this model** in a real-world setting.

Please describe, step by step:

* The tools and infrastructure you would use (e.g., cloud services, model hosting, orchestration)
* How the model would be launched and integrated into a production system
* How you would test and validate the model
* How you would monitor performance and handle model updates over time

Clarity and structure matter more than naming specific technologies.


---

If you have any clarifying questions about the assignment or data access, feel free to reach out.

Good luck—we’re excited to see how you approach the problem!

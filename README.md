# Modeling-Credit-Card-Default-Risk-and-Customer-Profitability-Using-MS-Excel


1)Customer Default Binary Classification Model(Train Set and Test Set Default Analysis Sheets)


You work for a bank as a business data analyst in the credit card risk-modeling department. Your bank conducted a bold experiment three years ago: for a single day it quietly issued credit cards to everyone who applied, regardless of their credit risk, until the bank had issued 600 cards without screening applicants.

After three years, 150, or 25%, of those card recipients defaulted: they failed to pay back at least some of the money they owed. However, the bank collected very valuable proprietary data that it can now use to optimize its future card-issuing process.

The bank initially collected six pieces of data about each person:

· Age

· Years at current employer

· Years at current address

· Income over the past year

· Current credit card debt, and

· Current automobile debt

In addition, the bank now has a binary outcome: default = 1, and no default = 0.
Cost per false negative = $5000, cost per false positive = $2500
You have to minimize the cost per event


2)Modeling Profitability instead of Default (Linear Regression wih Mutiple Variables)

3)Modeling Credit Card Default Risk and Customer Profitability

Here we model it as a binary classification model with unprofitable customer = 1, profitable customer = 0
Further we know,
The bank has learned that not all defaulters are unprofitable and not all non-defaulters are profitable. Therefore you should no longer use the bank’s “old” estimates for rate of default (25%), average losses per defaulter (-$5,000) average profits per non-defaulter ($2,500), and average profits per applicant when using no model ($625).
The proportion of applicants that are unprofitable (again 25%, but a different 25%), average losses per unprofitable customer (-$4,900), average profits per profitable customer ($4,000), and average profits per applicant when using no model ($1,775).
Maximize the profitability per customer.

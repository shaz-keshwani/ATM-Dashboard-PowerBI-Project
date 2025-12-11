# ATM-Dashboard-PowerBI-Project

# Dataset description
This dataset shows daily activity for many ATMs in different cities and countries.​
Each row represents one ATM on one date with details about withdrawals, deposits, money amounts, unique cards used, and a flag for suspicious activity.

# Key fields:
ATM and location details: atm_id, address, city, state, country, postal code.​
Date of activity: transaction_date.​
Usage metrics: total_withdrawal_count, total_withdrawal_amount, total_deposit_count, total_deposit_amount, unique_card_count.​
Quality and risk fields: average_withdrawal_amount, average_deposit_amount, suspicious_activity_flag, notes.

# Business Problem:
The bank wants to understand how customers use ATMs across different regions and days.
Leaders need to know which ATMs are high performing, which are underused, and where there may be system issues or fraud risk.

1. Which locations get the highest and lowest daily traffic?
2. How does usage change by city, country, weekday, and event days?
3. Which ATMs show unusual patterns, like very high withdrawal amounts or zero activity?

# Solution provided:
The raw transaction file was cleaned into a structured “cleaned_data.csv” with consistent dates, numeric types, locations, and a clear suspicious_activity_flag. A Power BI dashboard was built to track ATM performance, usage trends, and suspicious activity across locations and time.

## Main solution elements:
Data cleaning: fixed missing values, standardized location fields, validated amounts and counts.
Feature engineering: average withdrawal and deposit amounts, flags for zero-activity ATMs, and suspicious behavior.
Power BI visuals: KPI cards, bar charts by city and country, line charts over time, and tables highlighting ATMs with issues or extreme activity.

## Usage insights
Some ATMs are very busy (many withdrawals, high amounts, many cards used). These are in strong locations and must always have enough cash.
Some ATMs are very quiet or show zero activity. These might be new, under maintenance, or in bad locations and may need action

## Cash and customer patterns
Busy ATMs tell the bank where cash demand is highest, so they can plan refills better.
Dates and notes show spikes on paydays, weekends, and events, which helps plan for short-term high traffic.



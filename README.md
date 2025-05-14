Subject: Data Quality Review & Initial Analysis – August Transactions

Dear Wendy,

I hope this message finds you well.

As part of our initial analysis of your August 2018 transaction data, we conducted a basic data quality check to ensure accuracy and usability for further analytics. Here are our findings:

Data Quality Issues Identified:
Missing Data:

Several entries have blank or missing values for merchant_suburb and merchant_state.

These were filled as “Unknown” during data cleaning for consistency.

Date Formatting:

The date column does not include timestamps. This limits our ability to perform detailed time-based (hourly) transaction analysis.

Card Present Flag:

Some rows under card_present_flag are blank. It's unclear if this implies “0” or an error in data collection.

Inconsistent Transaction Descriptions:

txn_description includes varying terms (example "POS", "SALES-POS", "INTER BANK") without clear definitions, which may hinder categorization.

Recommendations for Future Data Collection:
Ensure mandatory fields (merchant details, card_present_flag) are always captured.

Add timestamps to the date column for richer analysis (e.g., peak transaction hours).

Define standard categories for txn_description and ensure consistent usage.

Include a unique transaction ID per row for tracking and reference.

Initial Insights:
Top Spending Locations: Sydney (NSW) and Melbourne (VIC) are the most common merchant suburbs.

Average Transaction Amount: ~$28.40 per transaction.

Most Active Customer: Kristin appeared most frequently in transactions.

Transaction Type Trends:

POS and SALES-POS dominate transactions (~75%)

INTER BANK and PAYMENT transactions typically have higher values.

We have attached a short presentation summarizing key insights and visual trends.

Please let us know if you’d like a deeper dive or additional metrics for your review.

Best regards,

Dorothy Akoth

Inter Bank

## Here are my slides

https://docs.google.com/presentation/d/1CojutYCnt3XoNt2MfIJlgmBQ8CK2Zw9i54CNBc4Gpfc/edit?usp=sharing

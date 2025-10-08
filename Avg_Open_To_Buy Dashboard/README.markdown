# Avg_Open_To_Buy Dashboard

## What It's About
Think of "Avg_Open_To_Buy" as the extra credit a customer has left on their card – like how much more they can spend before hitting their limit. This dashboard uses simple charts and numbers to show this info for 10,000 bank customers. It breaks it down by things like if they're staying or leaving the bank, their gender, marital status, and card type (like Blue or Platinum).

## Why It Matters
The bank is worried because more customers are canceling their credit cards. Only about 16% have left so far, but that's still a problem. This dashboard teaches us who might leave next by spotting patterns in their unused credit. For example, customers with less leftover credit are more likely to go. By understanding this, the bank can offer better deals to keep them happy and save money on losing customers.

## Dashboard Components
Here's a quick guide to each part, like a map to the dashboard:

- **Key Numbers at the Top**: Shows big-picture stats. Total unused credit across all customers is 75.64 million. On average, it's 37.82 million per group. Men have more (54.83 million max), and staying customers have way more (63.50 million) than those who left (12.14 million). Blue cards top the list at 58.56 million, while Platinum is lowest at 580,000.

- **Pie Chart for Staying vs. Leaving**: A circle split into blue (staying: 83.9%) and green (leaving: 16.1%). It teaches that most customers stick around, but we need to focus on the smaller leaving slice.

- **Bar Chart for Distribution**: Shows how unused credit falls into buckets, like 0-7K (thousands) or over 28K. Most customers have higher amounts, but many leavers are in lower buckets.

- **Marital Status by Card Type Bars**: Compares unused credit for divorced, married, single, or unknown, split by card colors (Blue, Gold, etc.). Married folks often have more, especially with Blue cards.

- **Gender Bars**: Simple bars showing men have about twice the unused credit as women.

- **Gender by Staying/Leaving Bars**: Breaks it down further – staying men have the highest (around 46 million), while leaving women have the lowest (3.58 million).

- **Card Type by Staying/Leaving Bars**: Blue cards dominate for stayers, but all types show leavers have much less unused credit.

- **Ratio Stacked Bars by Gender**: Shows the share of unused credit per card type for men and women. Blue takes the biggest chunk for both.

- **Card Type Pie Chart**: A circle showing Blue as the main slice (77.4%), with smaller pieces for Gold, Silver, and Platinum.

- **Table by Staying/Leaving and Gender**: Lists exact numbers, like leaving females have 3.58 million total unused credit.

## What We Learn (Key Insights)
- Customers who leave have much less unused credit – about 5 times less than stayers. This suggests if someone's leftover credit drops low, they might be unhappy and ready to cancel.
- Men generally have more leftover credit, so women might need extra attention to prevent leaving.
- Blue card users are the happiest (highest leftovers), while Platinum users have the least – maybe upgrade offers could help.
- Overall, this data teaches that low unused credit is a red flag for losing customers.

## Business Impact
By using this dashboard, the bank could cut customer loss by 20-30% (based on similar industry studies). That's like saving millions in revenue, since keeping a customer is cheaper than finding a new one. It turns data into action, like sending personalized emails with credit boosts.

## Where the Data Comes From
From https://leaps.analyttica.com/home – a site with real-world datasets for solving business problems. It includes details on age, salary, credit limits, and more for 10,000 customers.

## What to Do Next (Recommendations)
- Watch customers with under 12 million unused credit – offer them limit increases.
- Give special perks to women and Platinum holders to boost loyalty.
- Build a prediction tool using this data to guess who might leave soon.
- Update the dashboard monthly with new data for ongoing learning.

## Future Ideas
Add filters to drill down by age or salary. Or link to a model that predicts churn risk scores. This could make it even more powerful for the bank.
## Forecasts and Predictions
### Project description:

The gym chain Model Fitness is developing a customer interaction strategy based on analytical data.

In order to fight churn, Model Fitness has digitized a number of its customer profiles. The task is to analyze them and come up with a customer retention strategy.

We will:

* learn to predict the probability of churn (for the upcoming month) for each customer

* draw up typical user portraits: select the most outstanding groups and describe their main features

* analyze the factors that impact churn most and draw basic conclusions

* develop recommendations on how to improve customer service

### Dataset description:

Model Fitness provided us with CSV files containing data on churn for a given month and information on the month preceding it. The dataset includes the following fields:

* `Churn` — the fact of churn for the month in question

* Current dataset fields:

    * User data for the preceding month

    * `gender`

    * `Near_Location` — whether the user lives or works in the neighborhood where the gym is located

    * `Partner` — whether the user is an employee of a partner company (the gym has partner companies whose employees get discounts; in those cases the gym stores information on customers' employers)

    * `Promo_friends` — whether the user originally signed up through a "bring a friend" offer (they used a friend's promo code when paying for their first membership)

    * `Phone` — whether the user provided their phone number

    * `Age`

    * `Lifetime` — the time (in months) since the customer first came to the gym

* Data from the log of visits and purchases and data on current membership status:

    * `Contract_period` — 1 month, 3 months, 6 months, or 1 year

    * `Month_to_end_contract` — the months remaining until the contract expires

    * `Group_visits` — whether the user takes part in group sessions

    * `Avg_class_frequency_total` — average frequency of visits per week over the customer's lifetime

    * `Avg_class_frequency_current_month` — average frequency of visits per week over the preceding month

    * `Avg_additional_charges_total` — the total amount of money spent on other gym services: cafe, athletic goods, cosmetics, massages, etc.
# Hypothesis testing on yellow taxi_data
Apply hypothesis testing on yellow taxi data

Payment_type

1: Credit card

2: Cash

3: No charge

4: Dispute

5: Unknown

![image](https://github.com/user-attachments/assets/e8d55399-b4f3-48f9-a01e-ddfdf6b175a1)

Most of the data are cash and card payment.

![image](https://github.com/user-attachments/assets/924da849-0d4f-4de4-84a8-2c69b36eba14)
Based on above chart, it shows customers who pay in credit card tend to pay a larger fare amount than customers who pay in cash.

$H_0$: There is no difference in the average fare amount between customers who use credit cards and customers who use cash.

$H_A$: There is a difference in the average fare amount between customers who use credit cards and customers who use cash.

![螢幕截圖 2024-09-01 下午1 29 52](https://github.com/user-attachments/assets/35bdd89f-6047-4c8b-86af-07ab0512d0d0)

Since the p-value for the Levene test is less than 0.05, the hypothesis that the variances are equal is rejected.

![螢幕截圖 2024-09-01 下午1 30 10](https://github.com/user-attachments/assets/93a36a1e-1435-4bbb-bd53-3f9ed89fcf94)
Since the p-value is less than 0.05, we can conclude that there is a statistically significant difference between card and cash.

#### What business insight(s) can you draw from the result of your hypothesis test?

Answer: Customers to pay with credit cards can generate more revenue for taxi cab drivers

#### Consider why this A/B test project might not be realistic, and what assumptions had to be made for this educational project.

Answer: Customer may not bring enough money to pay a longer trip (higher amount) in order to choose a different payment method than cash. Theremore, the amount may more likely to determines the payments type.


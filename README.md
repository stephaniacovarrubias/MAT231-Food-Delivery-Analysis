# MAT231-Food-Delivery-Analysis
In this project, my teammate and I analyzed food delivery orders and used our dataset to answer questions that explain the inconsistencies for these orders.

# Questions
1. Is there a relationship between delivery time and customer ratings? Do late deliveries actually lead to worse ratings, and how strong is that effect?

Which holiday has the highest delivery minutes?

How do delivery times vary depending on the size of an order (number of items) or type of food? Do bigger orders take longer, or does it depend more on what you ordered?

## Findings
For our first question, we found out that Labor Day has the highest delivery. Our assumption for this is due to the season and nature of the holiday. Normally, individuals host barbeques and events. In addition, it is a "end of summer" holiday. 

After analyzing 895 successfully delivered orders, the data shows that neither order size nor food type significantly impacts delivery time. Orders were grouped into four size categories (Small, Medium, Large, and XL) based on order value, and all four averaged within one minute of each other, ranging from 51.0 to 51.5 minutes, indicating that bigger orders do not take longer to deliver. Food type showed a slightly larger but still modest effect, with Indian food being the fastest at 49.9 minutes and Bakery orders being the slowest at 52.9 minutes, a difference of only 3 minutes. Overall, delivery time appears to be driven more by external factors such as delivery distance, traffic, or driver availability rather than what or how much a customer orders. 

Our third question, the scatter plot we designed showed the average customer ratings between 3.68 and 3.84 across all delivery speed tiers, with no consistent downward trend. The correlation of 0.019 confirms virtually no linear relationship between delivery time and customer ratings. Contrary to expectations, late deliveries do not lead to meaningfully worse ratings in this dataset.

# Order-late-delivery-analysis

Afer data exploration, it is observed that lots of shipments suffer from late delivery risk, hereby make some hypothesis, and use data to test against.

**Hypothesis:**
1. Is there any relation with **Market**?→No
2. Is there any relation with **Departments**?→No
3. Is there any relation with **Shipping Mode**?→Yes
4. Is there any relation with **Order Delay**[order_date-shipping_date]?→Yes
5. Is there any relation with **shipping day**['week_day']?→No

**Data Analysis:**
Use stacked bar to visualize the contradiction.

**Conclusion and Recommendation:**

It was observed that **shipping method** and **Order Delay** were the two biggest factors in determining whether a package would be delayed.

1.It is recommended that a **program implemented to minimize the amount of time from when the order was placed to the time it was shipped**. Further operational studies may be needed to look into the packing-shipping process and determine the best method to minimize Order Delay. <p>
2. Since shipping method also played a large role in determining whether a package would be late, a **cost/benefit analysis** of either a subscription-based model or a **customer loyalty program** that prioritizes subscribers or loyal customer shipments. <p>
3.  Further effor will be needed to build up a **prediction model**, which will help monitor the order status in time. If the model predicts that a package will be late, then the risk could be mitigated by either expediting the shipment or by setting the shipment method to First Class or same day. If a late delivery is unpreventable, the marketing team could employ a customer loyalty discount program such that the customer received a discount on their next purchase.

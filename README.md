# Netrality GeoSales Insights & Prospect Analysis

### Problem Statement
1) Can we predict which prospective customers are most likely to convert, based on their similarity to Netrality’s current customers?
2) Of those prospective customers, can we predict the monthly revenue they would generate for Netrality?


### Summary of Approach 
JYS leveraged the geodata of each of Netrality’s customers and prospects to look for specific regions where Netrality Sales should focus their efforts. The location of prospective customers in relation to Netrality’s Data Center locations is a feature that JYS strongly feels can be used to select strong candidates that Netrality can convert into valuable customers.

![image](https://github.com/user-attachments/assets/185b2b82-62bf-4697-a7c3-5d34eb1ac2ae)

We used the zipcode of each customer or prospect to assign each a latitude and longitude. Using these coordinates, we mathematically clustered their locations. These clusters, mirroring regions within the continental United States, were used as additional features in our modeling efforts to predict the monthly revenue that Netrality would expect to see from individual customers.

![image](https://github.com/user-attachments/assets/e37f36bb-d816-46e3-a620-546e1c135317)

As we attempted to model potential revenue, it became apparent to us that there are other indicators of a customer’s lifetime value that would be important to predict. Using joined current customer and current billing data as a base, we assigned each customer a value for the number of data centers that they were present in during the last billing cycle. Again using geographic and financial data, we attempted to predict the number of Netrality locations that a customer would place themselves in.

![image](https://github.com/user-attachments/assets/8c137d4b-7469-4672-8803-50885ddbd057)

### Summary of Results and Conclusions 
Based on our analysis of the locations of each of Netrality’s current customers, JYS determined
that Netrality should seek out prospective customers based in Indiana. When plotting each customer’s location, we’d noticed that Netrality’s customers are primarily located in the same metropolitan areas as Netrality data centers. This is true for all Netrality data centers except for Netrality’s Indy Telcom Center.
- Texas (Houston Data Center): 61 Customers
- Missouri (St. Louis and Kansas City Data Centers): 56 Customers
- Pennsylvania (Philadelphia Data Center): 22 Customers
- Illinois (Chicago Data Center): 22 Customers
- Kansas (Kansas City Data Centers): 22 Customers
- Indiana (Indianapolis Data Center): 3 Customers

60% of Netrality’s customers are located in Texas, Missouri, Pennsylvania, Illinois, or Kansas. All have identifiable clusters of customers, presumably providing a revenue stream at each of the data center locations that they surround. This is a trend that Netrality should seek to continue at its Indy Telcom Center.

While there are only 3 active customers located in Indiana, Netrality has 57 prospective customers located in the Hoosier State. But of these 57, who are the best to target? JYS analyzed the average total last month revenue Z-Score for all customers by primary industry. In doing so, we were able to discern which industry had customers which generated above average revenue for Netrality.

![image](https://github.com/user-attachments/assets/c049b11f-12df-45f4-a4b8-d1e2397621f2)

When we filter down the 57 Indiana prospects to those industries which contain higher that average paying customers, we are left with the following 31 prospects to target! 



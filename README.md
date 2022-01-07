# Quantium-Virtual-Project
## Introduction
Quantium is a leading data science and AI firm, founded in Australia in 2002. Quantium combines the best of human and artificial intelligence to power possibilities for individuals, organisations and society.

As a part of Quantium's retail analytics team and have been approached by the client, the Category Manager for Chips, who wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region. Furthermore, the manager also asked us to test the impact of the new trial layouts with a data-driven recommendation as to whether or not the trial layout should be rolled out to all their stores.

All the given information is from the **Quantium Data Analytics Virtual Experience Project** on [Forage](https://www.theforage.com/virtual-internships/prototype/NkaC7knWtjSbi6aYv/Data%20Analytics%20Virtual%20Experience%20Program?ref=H9ARjfcciFq8iXfBx).

## Data Preparation and Customer Analytics
Conduct analysis on client's transaction dataet and identify customer purchasing behaviours to generate insights and provide commercial recommendations.

### Analyze the Transaction Data
#### Sales
According to the transaction data set, we found that the volatility of the transaction of chips does not fluctuate much throughout the year, however, there was large volatility in December.

![total sales](https://user-images.githubusercontent.com/82549782/145315710-398a1be4-8c3a-4653-9fb4-10740e0dcf6c.png)

After we took a closer look at the sales in December, we found that there was an increase in sales before Christmas and no sales on Christmas Day. This makes sense, because Christmas is a family gathering, and chips are a very suitable snack for family gatherings, so people will prepare a lot of chips before Christmas. On Christmas Day, many stores are closed, which is why there were no sales on Christmas Day.

![total sales in december](https://user-images.githubusercontent.com/82549782/145333865-61e8308b-4212-4906-a3b4-5e26eeb7555b.png)

#### Brands and Pack Size
The most popular Brands were Kettle, Smiths, Pringles, and Doritos.

![count brand name](https://user-images.githubusercontent.com/82549782/145334094-b7d4c438-c06b-4582-af27-286eed30bbd2.png)

The most popular pack size were 175g.

![count pack size](https://user-images.githubusercontent.com/82549782/145334070-384bb0d4-a252-42af-825f-cb90328df10c.png)

Based on the graphs above, we recommend our clients purchase more chips from these popular brands with a size of 175g or 150g to make sure stores have an excessive inventory in comparison to the sales level.

### Analyze the Customer Data
![image](https://user-images.githubusercontent.com/82549782/148315783-2c5b52c6-f1d5-401b-85c9-4368c8b07d91.png)

From the plot above, we can see the sales are mostly from the budget older families, mainstream young single/couples and mainstream retirees.

![image](https://user-images.githubusercontent.com/82549782/148315813-d11aa862-43cd-4cdf-b358-420f24299475.png)


## Experimentation and Uplift Testing
Our client has asked us to evaluate the performance of a store trial which was performed in stores 77, 86 and 88.

### Compare the Performance
First, we need to select control stores based on correlations, and then compare the total sales and number of customers between the trial and control stores.

- Trial store 77 and Control store 233:

![comparison 77 233](https://user-images.githubusercontent.com/82549782/145262066-d19c379e-a15f-412a-b9f4-91c2441cca34.png)

- Trial store 86 and Control store 155:

![comparison 86 155](https://user-images.githubusercontent.com/82549782/145262113-6545fd68-611c-478f-a512-d229423ea389.png)

- Trial store 88 and Control store 178: 
  - Store 88 and 178 have similar trends among sales and number of customers, however, control store 178 has lower sales and fewer customers than store 88.

![comparison 88 178](https://user-images.githubusercontent.com/82549782/145262576-74a68d13-0293-4141-856d-68a33b54f959.png)

### Assessment of the Trial
Compare each trial and control pair during the trial period, and test if total sales are significantly different in the trial period.

- Trial store 77 and Control store 233:
  - Trial store 77 showed significant increase in total sales and number of customers in March and April.
  - The driver of changes in total sales is more purchasing customers.

![assessment 77 233](https://user-images.githubusercontent.com/82549782/145265131-d9305a16-15d2-41c1-87fd-f2d2ced7f8f6.png)

- Trial store 86 and Control store 155:
  - Trial store 86 showed significant increase in number of customers during entire trial period, however, only March has significant increase in total sales.
  - An increase in sales in March was driven by the increase in the number of customers.
  - A significant increase in the number of customers but less increase in sales in February and April may be caused by fewer purchases per customer.

![assessment 86 155](https://user-images.githubusercontent.com/82549782/145265595-ae32ee7d-6e65-4206-9eaf-d34ba8bc37e5.png)

- Trial store 88 and Control store 178:
  - Trial store 88 showed significant decrease in total sales in Fabruary, and showed decrease in the number of customers during entire trial period.
  - Trial store 88 should not be rolled out to their stores because there were fewer sales and fewer customers.

![assessment 88 178](https://user-images.githubusercontent.com/82549782/145271758-256bb35e-b671-4e58-8564-9d5c73207e46.png)

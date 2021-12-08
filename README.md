# Quantium-Virtual-Project
## Introduction
Quantium is a leading data science and AI firm, founded in Australia in 2002. Quantium combines the best of human and artificial intelligence to power possibilities for individuals, organisations and society.

As a part of Quantium's retail analytics team and have been approached by the client, the Category Manager for Chips, who wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region. Furthermore, the manager also asked us to test the impact of the new trial layouts with a data-driven recommendation as to whether or not the trial layout should be rolled out to all their stores.

All the given information is from the **Quantium Data Analytics Virtual Experience Project** on [Forage](https://www.theforage.com/virtual-internships/prototype/NkaC7knWtjSbi6aYv/Data%20Analytics%20Virtual%20Experience%20Program?ref=H9ARjfcciFq8iXfBx).

## Data Preparation and Customer Analytics


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

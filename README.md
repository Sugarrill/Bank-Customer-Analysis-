 # Bank Customer Analysis Project



    ## Overview
    
    `Problem Statement`
    
    Bank of England provided a dataset containing key demographic and financial details of bank customers. The bank needs to improve customer retention strategies, optimize financial products, and better understand customer behavior across different segments.
    
    `Objectives`
    
    Utilizing the dataset containing key demographic and financial details of bank customers. We would answer questions that would help us understand the demographic of the bank customers, the financial characteristics of the bank customers, identifying trends and patterns in customer engagement, and highlighting potential areas for business improvement.
    
    `Approach`
    
    To solve this problem, we are going to utilize the standard approach for data mining;
    
     - Proper Understanding of the data.
     - Prepare the data for analysis.
     - Answering the questions to help us achieve our objectives.
     - Draw conclusions.
     - Prepare a summary.
    


     ## Data 
    
     Here is the data dictionary for more insight of the data
    
     `CustomerId`: A unique identifier for each customer.
    
      `Surname`: The customer's last name.
    
      `CreditScore`: A numerical score representing the customer's creditworthiness.
    
      `Geography`: The geographical location of the customer (e.g., country or region).
    
      `Gender`:The gender of the customer.
    
       `Age`: The customer's age.
    
      `Tenure`:Number of years the customer has been with the bank (possibly).
    
      `EstimatedSalary`: The estimated annual salary of the customer.
    
      `Balance`: The current balance in the customer's account.
    
      `Total Products`: The number of products the customer has with the bank (e.g., savings, loans).
    
      `Credit Card`: Whether the customer has a credit card with the bank.
    
     `Active Member`: Whether the customer is an active member of the bank.
    
      `Exited`: The target variable indicating whether the customer has exited the bank.
    
    
      # Insights and Recommendations 
    
     Here are the key insights drawn from analyzing the data.
    
     - In Customer distribution we discovered that;
    
        - France has the highest value, then Germany and Spain has the same values.
        - The male has the highest value than the female.
        - The majority of customers fall within the adult age group, as identified in the age group analysis.
      
     The Age group have been categorised using the keys below:
    
        <18:Teenager
        
         18<=>30:Youth
       
         
         
         >30:Adult
    
    
     - The analysis between Credit Score and Balance reveals a similar relationship across genders. Both men and women exhibit a positive correlation between credit score and balance, with individuals holding higher balances tending to have higher credit scores. There is no significant difference in the strength or nature of the relationship between genders.
    
     - The analysis of the relationship between customer tenure and total products reveals that customers with 3 or 4 products represent the largest group over the past six years, while those with fewer than 3 products constitute the smallest group.
    
     - The analysis of the relationship between customer tenure and credit card owned reveals that the majority of customers who have been with the bank for more than seven years do not have a credit card, while those who have been with the bank for less than seven years are more likely to have a credit card.
    
     - The analysis of the relationship between customer tenure and active members reveals that for more than six years, the number of inactive members has consistently exceeded the number of active members.
    
     - In examining the impact of tenure on customer behavior, we found that short-term customers tend to have more products and higher balances than long-term customers.
    
     -  In exploring the distribution of credit scores across age, gender, and geography, it reveals no significant differences.The distributions appear to be fairly consistent and likely equal across these factors.
    
     -  When comparing the customer balance and estimated salary by gender,it was discovered that both genders have equal balances and similar estimated salaries.
    
     -  When comparing customer balance and estimated salary by geography,it was discovered:
    
         - Germany has a higher balance than both Spain and France, with Spain and France displaying similar balance levels.
         -  Germany has a slightly higher estimated salary compared to Spain and France, while Spain and France have similar salary            levels.
           
     -  When comparing customer balances by age, the data shows that balances are consistent across age groups. In contrast, the estimated salary analysis indicates that all salary values are equally distributed across age groups.
    
    
     -  When comparing the demographics characteristics of customers,we found out that:
    
          - The age group classified as adults has a higher number of exited customers than active customers.
         - The male gender make up the highest number of active customers, as well as the lowest number of exited customers,then the          females have the highest number of the exited customers.
         - France has the highest number of active customers, while Germany has the lowest. It also indicates that France and                 Germany have the same number of exited customers, with Spain having the fewest exited customers.
    
     - When comparing the financial characteristics of customers,we found out that:
    
         - Credit score by customer status indicate that the values are equal.
         - The balance of the exited customers is slightly higher than active customer's balance.
         - The estimated salary of the exited customers is slightly higher than active customer's estimated salary.
        - Active customers with two products have the highest value, while exited customers with four products have the lowest value.
    
    
    
     - Based on the analysis, we can interpret the unique characteristics of each segement:
    
        - High-Balance Customers:
          
         - These customers are adult that have a higher average balance and credit scores.
         - These customers have been with the bank for a long period.
         - These customers hold more financial product.
    
        - Low-Balance Customers:
    
         - These customers have lower balances and might be teenagers.
         - They have fewer products with the bank,indicating a lower level of engagemnt.
         -  Low-balance customers may have a shorter tenure, possibly because they haven’t fully engaged with the bank.
    
        -  Medium Balance Segment:
      
         -  Customers with moderate balances and engagement levels.
         -  Likely to be open to new products if incentivized correctly.
         -  Often fall between high-engaged segments.
    
    
      - High-Balance,High-Credit Score Customers
    
        - Characteristics:
    
          - These customers are adult that have a higher average balance and credit scores.
         - These customers have been with the bank for a long period.
         - These customers hold more financial product.
    
         - Optimization Strategies:
       
         - Create a tiered loyalty program that provides perks such as fee waivers,enhanced interest rates,or dedicated relationship          managers.
         - Offer personalized financial advice,access to wealth management services, or invitation to VIP events.
         - Provide tailored product offerings like high-yield saving accounts, investment opportunities,or insurance products.
        - Send targeted communications highlighting exclusive products and benefits for high-value client.
    
      - Low-Balance,Low-Product Customers
    
         - Characteristics:
    
          -  These customers have lower balances and might be teenagers.
          -  They have fewer products with the bank,indicating a lower levelof engagemnt.
          -  Low-balance customers may have a shorter tenure, possibly because they haven’t fully engaged with the bank.
    
         -  Optimization Strategies:
    
         -  Offer incentives like referral bonuses or discounts for adopting additional products.
          -  Promote low-cost bundled packages(budget-friendly insurance options)to increase product adoption.
         -  Use gamification techniques to increase engagement(e.g,rewards for completing financial milestones or challenges).
         -  Create educational content on financial literacy to guide them toward better financial decisions.
         -  Offer digital rewards like loyalty points for transactions.
    
    
       - Moderate-Balance,Mid-Tier Customers
    
        - Characteristics:
    
         -  Customers with moderate balances and engagement levels.
         -  Likely to be open to new products if incentivized correctly.
         -  Often fall between high-engaged segments.
       
         -  Optimization Strategies:
       
          -  Leverage data to recommend the next best product based on their transaction history(e.g., offering a personal loan to              those frequently using credit).
          -  Provide targeted offers for products like fixed deposits,personal loans, or travel-related perks.
          -  Assign customer success managers to proactively reach out and offer product recommendations.
         -  Implement lifecycle marketing campaigns based on tenure(e.g., special offers for anniversaries or birthdays).
          -  Reward loyal customers for continued engagement with perks like free account upgrade.
    
       - Customers with High Tenure but Low Product Adoption
    
        - Characteristics:
    
         - Customers who have been with the bank for a long time but only limited range of services.
         - These customers may be at risk of becoming inactive.
    
        - Optimization Strategies:
    
        - Create targeted email or sms campaigns with incentives to use existing or new services.
    - Send personalized offers encouraging them to explore new products(e,g., introductory offers for investment products or  upgraded credit cards).
         - Use insights from surveys to improve service offerings or address pain points that may be preventing them from engaging            further.
         - Utilize automated notifications to remind them of account benfits, product updates, or relevent financial opportunities.
         - Gather feedbacks to understand why they haven't adopted more products and adjust offerings accordingly.
    
      - Customers at Risk of Churn
    
      - Characteristics:
    
        - Customers showing signs of low engagement(e.g., reduced product usage, balance drops, or frequent complaints).
         - Typically dissatisfied with current services or seeking better offer elsewhere.
    
        - Optimization Strategies:
    
         - Implement retention offers, such as fee waivers or better rates, for customers identified as high-risk.
         - Create win-back campaigns targeting recently inactive customers with limited time offers to re-engage them.
         - Offer special incentives for customers who are close to anniversary or account review date.
    
     # Conclusion 
    
       By implementing these strategies,the bank can effectively optimize its services,enhance customer satisfaction, and improve  overall profitability. 
    
    
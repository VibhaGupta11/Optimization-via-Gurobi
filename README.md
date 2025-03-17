# Guroble Food Truck

## Table of Contents
- [Overview](#overview)
- [Project Description](#project-description)
- [Rounds and Key Metrics](#rounds-and-key-metrics)
- [Conclusion](#conclusion)
- [Future Enhancements](#future-enhancements)
- [Contact](#contact)

## Overview
The **Guroble Food Truck** project is an optimization challenge where the goal is to maximize profit by strategically placing burrito trucks to serve customer demand. Using Gurobi's optimization engine, we evaluate different operational scenarios and compare the algorithmically optimal solution with our own strategy.

## Project Description
The project simulates a series of operational rounds, each representing a different day and set of conditions. We analyze factors such as sales revenue, ingredient costs, and truck deployment costs to determine the most efficient truck placements. By comparing our solutions against Gurobi’s optimal results, we identify performance gaps and recommend improvements for better demand coverage and profitability.

## Rounds and Key Metrics

### Round 1 Day 1: Grand Opening
- **Objective:** Determine maximum profit through strategic truck placement.
- **Optimal Solution:**
  - **Sales Revenue:** $2,770
  - **Ingredient Cost:** $1,385
  - **Truck Cost:** $500 (2 trucks at $250 each)
  - **Total Profit:** $885
  - **Truck Placement:** Truck 17, Truck 38
- **Profit Breakdown:** Each burrito generates a net profit of $5 (i.e., $10 sales revenue minus $5 ingredient cost), with a fixed cost of $250 per truck.
- **Conclusion:** Our placement strategy achieved the optimal profit of $885, confirming its efficiency.

### Round 1 Day 2: Rising Demand
- **Objective:** Manage increased demand while controlling costs.
- **Optimal Solution:**
  - **Sales Revenue:** $12,550
  - **Ingredient Cost:** $6,275
  - **Truck Cost:** $1,500
  - **Total Profit:** $4,775
  - **Truck Placements:** Trucks 12, 17, 23, 34, 38, 43
- **Our Solution:**
  - **Sales Revenue:** $11,340
  - **Ingredient Cost:** $5,670
  - **Truck Cost:** $1,000
  - **Total Profit:** $4,670
- **Comparison & Recommendations:**  
  Although our solution performed strongly, it achieved a profit about 2% lower than the optimal. This suggests that while minimizing truck costs, we may miss revenue opportunities in some demand zones. Future rounds should consider expanding truck placements in high-demand areas to capture additional revenue.

### Round 1 Day 3: Supply Chain Disruption
- **Scenario:** A cheese supply chain disruption increases the ingredient cost to $7 per burrito.
- **Optimal Solution:**
  - **Sales Revenue:** $11,850
  - **Ingredient Cost:** $8,295
  - **Truck Cost:** $1,000
  - **Total Profit:** $2,555
  - **Truck Placements:** Trucks 14, 18, 34, 38
- **Our Solution:**
  - **Sales Revenue:** $11,670
  - **Ingredient Cost:** $8,169
  - **Truck Cost:** $1,000
  - **Total Profit:** $2,501
- **Comparison & Recommendations:**  
  Our solution fell short by $54 (about a 2% difference). This highlights the need to optimize truck placement further—even when ingredient costs increase—to serve more customers in high-demand areas.

### Round 1 Day 4: Weather Impact
- **Scenario:** With the cheese supply restored but rainy weather, customers are less willing to travel far.
- **Both Solutions:**
  - **Sales Revenue:** $5,510
  - **Ingredient Cost:** $2,755
  - **Truck Cost:** $1,500
  - **Total Profit:** $1,255
- **Conclusion:**  
  Both our solution and Gurobi's optimal approach achieved identical results, validating our strategy under adverse weather conditions.

### Round 1 Day 5: Peak Business
- **Scenario:** Business booms with favorable weather and supply conditions.
- **Optimal Solution:**
  - **Sales Revenue:** $20,200
  - **Ingredient Cost:** $10,100
  - **Truck Cost:** $2,250
  - **Total Profit:** $7,850
  - **Truck Placements:** Trucks 3, 7, 15, 21, 26, 28, 40, 45, 56
- **Our Solution:**
  - **Sales Revenue:** $18,630
  - **Ingredient Cost:** $9,315
  - **Truck Cost:** $2,000
  - **Total Profit:** $7,315
- **Comparison & Recommendations:**  
  Our approach was about 7% less efficient, likely due to suboptimal truck allocations in high-demand areas. Future improvements could include real-time demand forecasting and dynamic truck allocation to better capture revenue.

## Conclusion
This project demonstrates the practical application of optimization techniques using Gurobi to maximize profit under varying conditions. By comparing our solutions with the optimal ones, we have gained valuable insights into balancing revenue generation, cost management, and strategic resource allocation. These insights pave the way for further enhancements, such as integrating real-time data analytics to dynamically adjust truck placements.

## Future Enhancements
- **Real-Time Demand Forecasting:** Integrate live data to adapt truck placements dynamically.
- **Dynamic Truck Allocation:** Use real-time analytics to optimize truck routes and better serve high-demand zones.
- **Enhanced Cost Analysis:** Further refine cost management strategies to improve overall profitability.

## Contact
Feel free to reach out for collaboration, feedback, or questions.  
**Created by:** [Vibha Gupta]  

Connect with me:  
* **Email:** [vgupta14@horizon.csueastbay.edu] 
* **GitHub:** [https://github.com/VibhaGupta11]
* **LinkedIn:** [https://www.linkedin.com/in/vibha-gupta-42307699/]


# task-4
Dashboard 1 — Sales Profit Analysis (`task-4.pdf`)

### Dataset
`Sales_Dataset.csv` — Sales transactions with Category, Profit, Amount, Quantity, State, Payment Mode, and Order Date fields.

### Objective
Visualize monthly profit trends across product categories over time to identify seasonal patterns and category performance.

### Visual Created
- **Chart Type:** Clustered Bar Chart
- **Title:** Sum of Profit by Category, Year and Month
- **X-axis:** Month (grouped by Year)
- **Y-axis:** Sum of Profit
- **Categories Shown:** Electronics, Furniture

### Key Insights
- Electronics category shows a strong spike in **January 2025** (~21K profit peak)
- Furniture category peaks around **July–August 2022** (~20K)
- Both categories show consistent seasonality with higher profits mid-year and year-end
- Overall profit trend shows **growth from 2020 to 2023**

  

 Dashboard 2 — Agent Performance Analysis (`venky.pdf`)

### Dataset
`Product_Sales.csv` — Call center records with 9,939 rows across 11 agents, tracking calls picked up and products sold.

### Objective
Compare agent-wise performance across total calls handled, pick-up rate, and product conversion.

### Visual Created
- **Chart Type:** Clustered Bar Chart
- **Title:** Sum of ProductSold, Count of CallID, Count of AgentID, Count of CustomerID and Sum of PickedUp by Agent_Name
- **X-axis:** Agent_Name (11 agents)
- **Y-axis:** Multiple metrics — ProductSold, CallID count, PickedUp

### Agents Covered
Gloria Singh, Todd Morrow, Lisa Cordova, Michele Williams, Agent X, Paul Nunez, Christopher Moreno, Jocelyn Parker, Dana Hardy, Randy Moore, Angel Briggs

### Key Insights
- **Michele Williams** handles the highest call volume (~976 calls)
- All agents show consistent pick-up rates around **69–70%**
- Product sold count (blue bars) remains the lowest metric across all agents, indicating a **~21% overall conversion rate**
- Performance is fairly uniform across agents with minor variations

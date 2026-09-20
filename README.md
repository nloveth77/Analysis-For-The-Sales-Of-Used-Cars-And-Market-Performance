
# Analysis-For-The-Sales-Of-Used-Cars-And-Market-Performance



Introduction


This technical report evaluates a automotive dataset comprising 50,000 transaction records across major car manufacturers. The analysis evaluates key attributes such as manufacturing year, engine specifications, fuel type, vehicle mileage, and sales price to uncover price determinants, buyer preferences, and manufacturer revenue performance.



Objective


Revenue Drivers: Identify which vehicle manufacturing eras and brand portfolios contribute the highest cumulative revenue.
Feature Value Impact: Determine the influence of engine size, fuel type, and mileage on market valuation and sales volume.
Portfolio Optimization: Highlight high-performing vehicle models and isolate underperforming assets to optimize inventory and sales strategy.









<img width="1086" height="635" alt="Car Sales Dashboard" src="https://github.com/user-attachments/assets/21d6103d-a78e-4513-8c22-4aa4b26da80b" />












Dependent and Independent Variables


Dependent Variable



Price/ Total Revenue: The main continuous variable indicating total valuation or gross revenue generated.



Independent Variables


Manufacturer and Model: Categorical factors defining brand power and model demand.

Engine Size: Continuous factor representing vehicle performance capability.

Fuel Type: Categorical factor representing powertrains (Petrol, Diesel, Hybrid).

Year of manufacture: Temporal factor driving vehicle depreciation and technological generation.

Mileage: Continuous metric indicating vehicle wear and remaining operational lifespan.
Pre-Analysis Board

Data Ingestion & Integrity Check: Validated schema type consistency across all 50,000 records.

Anomaly & Boundary Inspection: Outliers evaluated in mileage (ranges from low tens of thousands to >250,000) and price.

Feature Grouping: Aggregated production years into 5-year cohort brackets (e.g., 1984–1988 through 2014–2018) to measure epoch-based revenue trajectories.




In-Analysis Board (Dashboard Key Metrics & Findings)


Core Metrics Summary


Top Revenue Manufacturing Era: 2014–2018 producing $234,598,733 in revenue.

Highest Grossing Manufacturer: Toyota leading gross sales at $180,028,908.

Model with Best Engine Size: RAV4 with 8,987.4 total engine displacement aggregate.



Visualization Breakdown


1. Revenue by Manufacturing Cohort (Line Chart)

Production models from 2014–2018 reached the peak revenue mark ($234,598,733), followed by 2009–2013 ($142,298,818) and 2019–2023 ($141,867,472).

Older cohorts (1984–1988) yield minimal aggregate valuation ($2,860,407), showing standard vehicle depreciation dynamics.



2. Manufacturer Revenue Distribution (Pie Chart)
Toyota: $180,028,908
Ford: $159,646,767
VW: $154,545,496
BMW: $121,292,265
Porsche: $75,931,722

3. Powertrain Preference (Area Chart)
Petrol dominates overall revenue generation at $287,491,4835 aggregate.
Diesel ranks second at $149,487,2212, while Hybrid accounts for $125,507,8988.

4. Low Mileage Leaders by Manufacturer (Bar Chart)
VW leads overall low-mileage inventory volume ($169,206,0192 cumulative score), closely followed by Ford ($168,327,4711) and Toyota ($139,802,7582).
Porsche exhibits significantly lower cumulative mileage count ($291,264,204), reflective of specialized/niche market footprint.

5. Top Models by Engine Size (Horizontal Bar Chart)
RAV4 leads displacement capacity (8,987.4 aggregate displacement $L$).
Followed by Mondeo (8,567.6), Passat (8,277.8), Golf (8,050.6), and Focus (7,753).

6. Models with Low Revenue Contribution (Donut Chart)
Identified lowest revenue contributing models: Z4 ($26,775,192), 718 Cayman ($24,981,675), and Cayenne ($18,664,487).





Post-Analysis Board (Observations & Recommendations)
Observations

Sweet Spot Manufacturing Years: Vehicles manufactured between 2014 and 2018 represent the highest value retention and customer demand, driving peak sales figures.

Volume vs. Premium Segment: Toyota, Ford, and VW drive total market volume and revenue through consumer models (RAV4, Mondeo, Golf). High-end sports lines like the Porsche 718 Cayman and BMW Z4 operate as low-volume sales drivers.

Powertrain Realities: Traditional internal combustion engines (Petrol) remain dominant in aggregate sales volume compared to hybrid alternatives.



Recommendations


Inventory Sourcing Strategy: Focus dealership procurement on 2014–2018 production models, particularly Toyota and Ford units under 100,000 miles to maximize turnover speed and margin.

Targeted Stock Allocation: Prioritize high-displacement utility and family vehicles (Toyota RAV4, Ford Mondeo, VW Golf/Passat) as core stock holdings.

Selective Niche Pricing: Implement adjusted margin pricing or specialized marketing for low-volume luxury models (e.g., BMW Z4, Porsche 718 Cayman) to shorten holding periods.




Summary


This analysis highlights that overall vehicle sales revenue is primarily driven by mid-age vehicles (2014–2018) from volume manufacturers like Toyota, Ford, and VW. While petrol engines continue to lead total transaction values, utility models with moderate-to-high engine displacement yield superior demand. Aligning inventory acquisition toward high-turnover models will maximize capital return and streamline stock management.





Reference


kaggle.com

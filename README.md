# Car_Analysis_Dashboard

## 1. Introduction

The Car Performance Analysis report provides an in-depth examination of car models based on various performance and pricing parameters. This analysis helps users make informed decisions by exploring vehicle attributes such as engine size, horsepower, mileage, drivetrain, and MSRP. The report spans four analytical dimensions: Region, Type, Make, and Model, enabling multi-level drill-through to ultimately guide the user toward choosing the ideal car.

## 2. Regional Performance Analysis

Objective:

To compare the overall performance and value of cars across different regions of origin such as Asia, Europe, and the USA.

Key Visualizations:

•	Bar Chart: Comparison of average Horsepower, MPG (City/Highway), and Weight by Region.
•	Column Chart: Total and Average MSRP by Region.
•	Pie Chart: Distribution of car count by region.
Insights:
•	Asian cars tend to offer better fuel efficiency at lower prices.
•	European cars often have higher horsepower and premium pricing.
•	The USA region contributes the largest volume of car models.

✅ Drill-through Enabled: Users can click on any region to filter data down to relevant Makes and Types.

3. Car Type Performance Analysis
Objective:
To evaluate car performance based on their type (SUV, Sedan, Coupe, etc.), enabling users to choose based on usage preference and budget.
Key Visualizations:
•	Clustered Column Chart: Comparison of Horsepower, MPG, and Weight by Type.
•	Scatter Plot: Weight vs Horsepower by Type to assess power-to-weight ratio.
•	Column Chart or Histogram: Price variation across types (alternate to box plot).
Insights:
•	SUVs are heavier and more powerful but less fuel-efficient.
•	Sedans and Coupes provide a good mix of performance and affordability.
•	Certain types are better suited for city driving, while others excel off-road.
✅ Drill-through Enabled: Clicking on a car type filters the models belonging to that type, narrowing user preferences.

4. Brand (Make) Performance Analysis
Objective:
To assess how different car brands perform in terms of power, price, efficiency, and design characteristics.
Key Visualizations:
•	Treemap: Count of Models per Make to show brand variety.
•	Radar Chart: Avg Horsepower, MPG, Weight, Cylinders, and Engine Size by Make.
•	Bubble Chart: Weight vs Length vs Engine Size for each Make.
•	Stacked Column Chart: Drivetrain distribution by Make.
Insights:
•	Brands like Toyota and Honda dominate in efficiency and price.
•	Luxury brands (like BMW, Audi) offer high performance with higher MSRP.
•	Drivetrain options vary across brands—some specialize in AWD or RWD systems.
✅ Drill-through Enabled: Clicking on a Make leads to model-level analysis for deeper insight.

5. Model-Level Decision Page
Objective:
To provide a detailed, comparative view of individual car models to help users finalize their choice based on their preferences.
Key Visualizations:
•	Table: All model attributes (Make, Type, Horsepower, MPG, Weight, MSRP).
•	Scatter Plot: Horsepower vs Weight to assess acceleration potential.
•	KPI Cards:
o	💰 Best Budget Car: MIN(MSRP)
o	🛣️ Best Fuel Efficiency: MAX(MPG_City)
o	🏎️ Most Powerful: MAX(Horsepower)
o	🚐 Best Comfort: MAX(Wheelbase) and MAX(Weight)
•	Multi-row Cards: Final recommendation shortlist based on filtered criteria.
•	Gauge Chart: Composite score of overall performance, affordability, and comfort.
Insights:
•	Drill-through filters allow users to dynamically adjust preferences (budget, power, efficiency) and shortlist the most suitable models.
•	Models offering the best trade-offs across multiple dimensions are highlighted clearly, helping users make a confident choice.

6. Conclusion
This analysis offers a 360-degree view of car performance across regions, types, brands, and models. By leveraging drill-through capabilities, users can seamlessly move from broad-level comparisons to specific model evaluations. The KPI cards, composite visualizations, and interactivity are designed to support real-world decisions like:
•	“Which car offers the best mileage under ₹20 lakh?”
•	“Which SUV brand is the most powerful and spacious?”
•	“What’s the best overall car for comfort and price balance?”
Ultimately, this Power BI dashboard empowers consumers and analysts alike to make data-driven car purchase decisions.


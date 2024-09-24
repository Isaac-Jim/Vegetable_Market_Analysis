**Project Overview**

This project analyzes how seasonality, quality, and external factors—such as natural disasters—affect vegetable prices. By leveraging Python for data cleaning, visualization, and statistical analysis, this study uncovers valuable insights for both businesses and consumers. The goal is to help stakeholders make more informed decisions about purchasing, storing, and pricing vegetables, ultimately aiding in better market strategies and consumer savings.


**Folder Structure**

•	Vegetable_Analysis_Project.ipynb: Jupyter notebook containing the code and analysis.

•	vegetable_market.csv: The dataset used, consisting of vegetable types, conditions, prices, and related attributes.


**Dependencies**
Ensure the following Python libraries are installed:

•	Pandas
•	Matplotlib
•	Seaborn
•	Numpy

**Project Outline**

**Data Import and Cleaning**

Loaded the vegetable_market.csv dataset.

**Cleaned the dataset by**  
1.	Dropping duplicates 
2.	Reseting index of dataframe after dropping duplicates
3.	renaming columns for clarity.
4.	Correcting mispelled Vegetable names
5.	Standardising  Vegetable names by capitalising each vegetable and removing whitespace
6.	Replacing missing months with the right month based on vegetable and season of missing month
7.	Correcting mispelled vegetable condition

**Exploratory Data Analysis (EDA)**

Conducted descriptive analysis on the dataset, including data types, unique vegetable types,Season,Temperature,Months, and price variations.

Some other explorations I made:

- Count of unique Vegetables
- Count of unique Vegetables by Season
- Count of Vegetables by Month
- Count of Vegetables by vegetable condition
- Count of Vegetables by disaster happened
- Highest Price per month for each vegetable
- Lowest Price per month for each vegetable
- Top 5 expensive Vegetables
- Top 5 cheapest Vegetables
- Total Vegetable Prices per season
- Price distribution of vegetables by Season based on vegetable condition
- Price Distribution by Season
- Total Price for each Vegetable by condition
- Temperature by Vegetable condition
- Proportion of vegetable condition by each season
- Price Distribution Based on the occurrence of Disaster
- Price distribution per Vegetable

    
**Key Insights**

1.**⁠Heatmap for Cheapest and Most Expensive Months for Each Vegetable**

 Timing is crucial. The heatmap reveals when it's most economical to buy certain vegetables in bulk, providing a clear cost-saving strategy for both consumers and businesses. For example, cabbage is at its cheapest in January, offering opportunities to lower household or operational expenses. Conversely, knowing when prices peak helps stakeholders make informed stocking decisions.

2.⁠**Top 5 Most Expensive and Least Expensive Vegetables**

  Ginger and garlic consistently appear as the priciest vegetables,   especially during off-peak seasons. On the other hand, vegetables like potatoes and cauliflower remain among the most affordable year-round.  Understanding these trends equips buyers and sellers to navigate price fluctuations and better manage their market strategies.

3.⁠**⁠Seasonal Price Variation Based on Vegetable Freshness**

 A standout trend shows scrap vegetable prices rising sharply from early winter and peaking at late winter , reaching 175 per kg .Due to the absence of scrap vegetables in summer, the price  of scrap vegetables drops significantly during the monsoon season. In contrast, fresh vegetables experience more moderate price fluctuations, with constant increase from summer to  autumn, and then decrease significantly in the spring season,Average vegetables peak in summer, showing how the market's dynamics shift based on season and freshness. This insight could be valuable for businesses and households seeking to adjust purchasing patterns.
   
4.**Vegetable Condition Distribution by Type**

 The bar chart provides a detailed breakdown of fresh, scrap, and average vegetables for each vegetable type. For instance, Garlic, Chilly,cauliflower Brinjal were the only vegetables  that were completely in fresh condition, showing that most of the supply was of higher quality. However, other vegetables like potato,pumpkin,peas had a significant portion classified as scrap, highlighting potential handling or storage issues. Knowing the exact number of fresh, scrap, or average vegetables for each type gives deeper insights into the quality of the market supply, allowing businesses to prioritize based on availability and condition.

5.**Price  Distribution of vegetables per season**

 I identified the price distribution of vegetables by season. Using a box plot, finding the quartiles, min and max values for each season was easy. Outliers for the various seasons were determined. Outliers presence could be investigated.
   
6.**Price of Vegetale based on its condition**

For each vegetable , I determined the price based on the vegetable condition . So comparisons can be made to know which vegetable condition of a particular vegetable cost the most.

7.**Vegetable condition Per Season**

I found out the vegetable conditions per season. Only autumn and summer had hundred percent fresh vegetables. The distribution of fresh vegetables, scrap and average vegetable for each season is displayed on a pie chart for each season

8.**Vegetable-Specific Price Trends:**

I explored price distributions for various vegetables, and here's what I found:
**Stable Pricing** Vegetables like potato, radish, onion, and pumpkin  show tightly clustered prices, reflecting a more stable market.
**Volatile Pricing** Tomato, peas, garlic, chilly , ginger,and pointed gourd exhibit broader price variations, hinting at market volatility due to seasonality or supply-demand swings.
**Moderate Variation** Cucumber, brinjal, cabbage, bitter gourd, and onion  land in between, with moderate price shifts.

9.**Disaster-Driven Price Spikes**

When disasters strike, fresh vegetable prices soar. For instance, prices jump from 23 units per kg  in normal conditions to 45 units per kg  during disasters.
Even scrap vegetables see drastic hikes, climbing from  25 units  to 175 units  per kg—supply scarcity drives demand.
Average-quality vegetables  remain relatively stable but still feel the pinch of inflation during disruptions.

10.**Supply Shocks During Disasters**

Certain vegetables—like peas, chilly, pointed gourd,  and radish—face severe availability drops, making them highly vulnerable.
Others, like brinjal, cabbage, garlic, and ginger, stand resilient, with some even thriving during crises.

11.**How Availability of Vegetables per season Impact prices?**

As certain vegetables dwindle during specific seasons, their prices rise dramatically! Take ginger, for instance—its sharp drop in quantity is directly linked to a significant price spike. This new insight reveals a potential solution to rising prices: ensuring bulk availability in peak seasons and preserving surplus for off-seasons.
It's a simple yet powerful approach that could stabilize prices for everyone across the supply chain.


**Visualizations**

**The project includes several visualizations to highlight these insights:**

- Heatmaps showing price trends for vegetables in their cheapest and most expensive months
- Line plots revealing price distribution by season and condition
- Bar charts comparing total price for each vegetable by condition (fresh, scrap, average)
- Pie charts displaying the distribution of fresh, scrap, and average vegetables across seasons

**Conclusion**

This analysis shows the dynamic relationship between vegetable prices, quality, seasonality, and external factors like disasters. Businesses can leverage these insights to optimize their supply chain, purchasing strategies, and pricing models. Consumers, on the other hand, can use the data to time their purchases, especially when buying in bulk or preserving vegetables for off-peak seasons. By understanding these price fluctuations, stakeholders can better navigate market volatility and stabilize costs in the long run.

<img width="778" alt="Screenshot 2024-09-05 at 14 06 16" src="https://github.com/user-attachments/assets/75b0a3e8-5da1-40ae-99f5-b2dcd5723244">
<img width="699" alt="Screenshot 2024-09-05 at 14 22 07" src="https://github.com/user-attachments/assets/23f4c145-264c-4345-9e9e-efcc12c8cd2b">
<img width="752" alt="Screenshot 2024-09-10 at 17 37 37" src="https://github.com/user-attachments/assets/63d83e43-21a1-46be-a704-07c32703d9a4">
<img width="759" alt="Screenshot 2024-09-10 at 17 52 34" src="https://github.com/user-attachments/assets/1597c9ea-09ac-4713-8cab-68b512477cbf">
<img width="511" alt="Screenshot 2024-09-10 at 18 05 07" src="https://github.com/user-attachments/assets/c48f9214-e0a3-41dc-9e5c-ca92465f8f16">
<img width="747" alt="Screenshot 2024-09-13 at 23 18 30" src="https://github.com/user-attachments/assets/1b661a73-2ff3-4959-9ea9-c0e927e56fbe">
<img width="650" alt="Screenshot 2024-09-13 at 23 59 52" src="https://github.com/user-attachments/assets/12fe0efd-4c56-4c07-b62e-57107f7d563a">
<img width="772" alt="Screenshot 2024-09-16 at 22 24 57" src="https://github.com/user-attachments/assets/b2b203b2-9b4f-4d57-81ab-7816aece68bf">
<img width="687" alt="Screenshot 2024-09-17 at 22 05 54" src="https://github.com/user-attachments/assets/e05c2345-60a9-49c2-824f-acc5350db0ba">
<img width="751" alt="Screenshot 2024-09-17 at 22 32 58" src="https://github.com/user-attachments/assets/3f0d2bcf-8970-42d8-b0ef-e14e4b415a11">
<img width="683" alt="Screenshot 2024-09-19 at 12 49 59" src="https://github.com/user-attachments/assets/8ff776ee-d2bf-422b-b876-87c6ede44abe">
<img width="729" alt="Screenshot 2024-09-19 at 13 30 19" src="https://github.com/user-attachments/assets/da3913a5-c01c-4148-88b0-9d47523aa531">
<img width="575" alt="Screenshot 2024-09-19 at 13 33 01" src="https://github.com/user-attachments/assets/7cab6f20-29fe-4614-9182-d385e077b09d">
<img width="729" alt="Screenshot 2024-09-19 at 13 43 05" src="https://github.com/user-attachments/assets/58b9fff9-0541-4d9e-aadf-0b2d53ae6754">
<img width="810" alt="Screenshot 2024-09-19 at 20 35 43" src="https://github.com/user-attachments/assets/a07abccc-56e2-44a0-ab97-e2f25e236635">
<img width="736" alt="Screenshot 2024-09-19 at 20 35 59" src="https://github.com/user-attachments/assets/fe19c07a-7c41-4a1f-8583-97df41a4e7a2">
<img width="774" alt="Screenshot 2024-09-23 at 18 26 57" src="https://github.com/user-attachments/assets/7e49932d-9e63-492a-948a-dd749f6a98df">
<img width="656" alt="Screenshot 2024-09-24 at 18 05 18" src="https://github.com/user-attachments/assets/4621bbe6-8655-44b2-ac7b-166b6ebe633b">
<img width="960" alt="Screenshot 2024-09-24 at 18 05 54" src="https://github.com/user-attachments/assets/19f03f0f-b3ad-44b5-90eb-98e4dbf4e9d6">
<img width="659" alt="Screenshot 2024-09-24 at 18 09 40" src="https://github.com/user-attachments/assets/e01f0bdf-7594-4625-9291-98b7a3ebffc2">
<img width="787" alt="Screenshot 2024-09-24 at 18 29 41" src="https://github.com/user-attachments/assets/305f9417-bacf-465c-8caf-11dd9e34fff9">











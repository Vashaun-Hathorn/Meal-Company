[meal_info.csv](https://github.com/user-attachments/files/20069273/meal_info.csv)
Meal & Fulfillment Center Analysis
This project analyzes two datasets: meal_info.csv and fulfilment_center_info.csv, focusing on cuisine trends, meal pairings, and fulfillment center distribution.
 Datasets
meal_info.csv: Meal details (ID, cuisine, category)

fulfilment_center_info.csv: Fulfillment center details (ID, region, city, type)

Key Insights
Most Common Cuisine: Thai (15 entries)
Thai Beverage Meal IDs: [1885, 1993, 2539]

Sample Meal Combos:
[(2539, 1754), (1885, 1971)] (Thai beverage + Italian sandwich)

Exclusive Categories: Salad (Italian), Biryani (Indian), Pizza (Continental), etc.

Shared Categories: Beverages (across 4 cuisines)

 Fulfillment Centers
Region 77: 17 centers

Most TYPE_A Centers: City code 590 (4 centers)

TYPE_B Center IDs: [10, 13, 24, 34, ..., 161]

Most Centers in Region: Region 56 (30 total), with city code 590 appearing 9 times
This project provides a high-level analysis of two datasets: one detailing meal offerings and another describing fulfillment center locations and types. The goal is to identify cuisine trends, interesting cross-cuisine meal pairings, and patterns in the distribution of fulfillment centers.

The analysis reveals that Thai cuisine is the most frequently offered, with beverages being a highly shared category across multiple cuisines. Some meal categories are exclusive to specific cuisines, such as Biryani for Indian or Pizza for Continental. There are also potential cross-cuisine pairings of interest—such as Thai beverages paired with Italian sandwiches or Indian wraps.

On the logistics side, the data shows that Region 56 contains the most fulfillment centers overall, while Region 77 has fewer but still significant coverage. City code 590 appears frequently, especially in Region 56, and hosts the highest number of TYPE_A centers. A specific list of TYPE_B centers was also identified for operational segmentation.

Overall, the insights from this project can be used to inform targeted menu development and regional fulfillment strategy.

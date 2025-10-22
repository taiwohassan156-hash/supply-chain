
# Supply Chain Analysis
 ### Project Overview
 The Supply Chain Dashboard project was developed to provide a clear, data-driven understanding of how products move through a company’s supply chain from production to customer delivery. The goal of this analysis was to uncover insights that could improve efficiency, reduce costs, and optimize overall performance across product categories, transportation modes, and shipping carriers.
Using business intelligence techniques, this dashboard visualizes key metrics such as Total Revenue, Total Shipping Cost, Total Sales, and Average Defect Rate, helping decision-makers quickly identify strengths and bottlenecks in the supply chain process.





### Data sources 

The dataset used in this project was obtained from Quantum Analytics NG.

### Tools 
- Power Bi - incorporating data cleaning, transformation and visualisation techniques
  
###  Data cleaning and Preparation 

The data used for this project was sourced from Quantum Analytics, a dataset containing key operational records on product sales, transportation modes, customer demographics, and shipping activities across multiple supply chain channels.
Before analysis, the raw data underwent a comprehensive data cleaning and preparation process to ensure accuracy, consistency, and reliability. The following steps were taken:

- Data Import and Inspection:
The dataset was imported into Power BI and Excel for an initial review. Basic checks were performed to identify missing values, duplicate records, and inconsistencies in product or carrier names.

- Handling Missing Values:
Missing entries in key columns such as product type, shipping cost, and transport mode were either imputed using average or median values (where applicable) or removed when incomplete records could not be verified.

- Data Standardization:
Categorical variables (e.g., product types, carriers, and transport modes) were standardized to maintain uniform naming conventions ensuring that “Air,” “air,” and “AIR” were treated as one category.

- Outlier Detection and Treatment:
Unusually high or low revenue and cost values were reviewed to ensure they reflected legitimate transactions. Outliers resulting from data entry errors were corrected or removed.

- Data Type Conversion:
Columns containing numerical metrics such as Total Sales, Revenue, and Shipping Cost were converted to appropriate data types (numeric or currency) for accurate aggregation and visualization.

- Data Modeling and Relationships:
Relevant tables such as Product Table, Carrier Table, and Customer Demographics Table—were linked through defined relationships using unique identifiers like Product ID and Order ID. This step ensured seamless cross-table analysis within Power BI.

- Data Validation:
After transformation, data integrity checks were carried out to confirm that totals and averages matched across different dimensions (e.g., by product type).

### Exploratory Data Analysis 

- Which product category (Skincare, Haircare, or Cosmetics) generates the highest total sales and revenue?

- What is the distribution of transportation costs across different transportation modes (Road, Rail, Air, and Sea)?

- Which shipping carrier contributes the highest revenue, and which one incurs the highest shipping cost?

- How does customer demographics (Male, Female, Non-binary, Unknown) affect total revenue generation?
- How can the company leverage these insights to make data-driven decisions for better operational performance?

### Result and Findings 

The analysis of the supply chain data revealed several key insights into the company’s operational efficiency, cost management, and product performance. The findings are summarized as follows:

- Product Performance
Skincare products recorded the highest total sales and revenue, making them the company’s most profitable category.
Haircare and Cosmetics followed, indicating consistent but lower performance.
This highlights the need for increased marketing investment and supply prioritization for skincare products to sustain profitability.
- Transportation Cost Distribution
Road and Rail transport accounted for the majority of shipping costs, reflecting heavy reliance on land-based logistics.
Air transport, though faster, showed higher cost per shipment suggesting it is best reserved for high-value or time-sensitive deliveries.
Sea transport was the most cost-effective, ideal for bulk or non-urgent shipments.
- Carrier Performance
Carrier B emerged as the top-performing logistics partner, contributing the highest revenue but also incurring the highest shipping cost.
The dual outcome indicates strong handling capacity but potential inefficiencies in cost structure.
Carrier A, with lower costs, may be underutilized or limited in capacity, suggesting an opportunity to balance load distribution among carriers.
- Customer Demographics
The “Unknown” customer category generated the highest revenue, indicating a gap in demographic data collection.
Among identifiable groups, Female customers contributed more revenue than Male and Non-binary customers.
Improving customer data recording can support more personalized marketing and better segmentation strategies.
- Operational Efficiency
The Total Revenue stood at 577.60K, while the Total Shipping Cost was 554.81, suggesting that logistics costs consume a significant portion of overall earnings.
The Average Defect Rate of 228% is abnormally high and may point to data inconsistencies or operational challenges such as product damage or poor handling.
Addressing these inefficiencies could lead to substantial cost savings and improved product quality.
- Overall Business Insight
The results show a need for:
Cost optimization across transportation and carrier services.
Enhanced data quality and completeness in customer records.
Targeted improvement in logistics performance and defect control.
By leveraging these insights, the company can make informed decisions that strengthen operational efficiency, reduce waste, and boost overall profitability within the supply chain.

### Recommendation

From the findings of this analysis, it is recommended that the company prioritizes cost optimization, operational efficiency, and data quality improvement across its supply chain activities. The analysis revealed that skincare products are the most profitable category, hence efforts should be focused on maintaining adequate stock levels and expanding marketing strategies to sustain and increase demand in this segment. At the same time, attention should be given to the haircare and cosmetics lines by exploring new promotional strategies or customer feedback mechanisms to enhance their sales performance.

To reduce transportation and logistics costs, the company should re-evaluate its dependence on road and rail transportation, which currently account for the highest expenses. Utilizing sea transport for bulk and non-urgent shipments can help minimize cost while still maintaining delivery efficiency. Additionally, adopting a hybrid logistics strategy that balances speed and cost between different transportation modes will further enhance cost control.

Carrier performance also requires close monitoring, especially for Carrier B, which incurs the highest shipping costs despite strong revenue contributions. Management should review its pricing structure and explore negotiations for better contract terms or consider redistributing loads among other carriers such as Carrier A and Carrier C to achieve balance and cost efficiency.

Another crucial recommendation is to improve the quality and completeness of customer demographic data. The large number of “Unknown” entries limits effective market segmentation and customer understanding. Strengthening data collection systems at the point of sale or customer registration will provide deeper insights for personalized marketing and better decision-making.

Finally, the company must address the high average defect rate recorded in the data. This could be due to handling inefficiencies, poor packaging, or data inaccuracies. Implementing stronger quality control measures across all stages of the supply chain, along with regular staff training, will help minimize product losses and improve overall customer satisfaction.

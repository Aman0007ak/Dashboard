
# 📊 **Dynamic Retail Dashboard in Excel**

## 📝 **Overview**

This repository contains a **Dynamic Retail Dashboard** created in **Microsoft Excel** to visualize retail data and provide valuable insights into sales, profit, and order trends. The data is sourced from three tables — **Order Table**, **Return Table**, and **People Table** — which are hosted on GitHub. The dashboard dynamically connects to the GitHub-hosted data and uses various transformations to create insightful visualizations and key performance indicators (KPIs).

### 🎯 **Key Features**

- **Dynamic Data Connection**: Excel workbook connected to GitHub-hosted tables for real-time updates.
- **Transformations**: Data cleansing and transformation for accurate reporting.
- **Interactive Dashboard**: Segmented dashboard for easy navigation and insights.
- **KPIs and Metrics**: Visual representation of key metrics like total sales, profit, and orders.
- **Visualization Segments**: Sales, profit, and trend analysis by category, segment, country, and sub-category.

---

## 📂 **Dataset**

The dataset used for this dashboard comprises three primary tables:

1. **Order Table**
2. **Return Table**
3. **People Table**

Let's explore each of these tables in detail.

### 1️⃣ **Order Table**

This table contains detailed order information, including sales, profit, customer details, and shipping details.

| **Order ID**      | **Returned** | **Order Date**       | **Ship Date**        | **Ship Mode**     | **Customer ID** | **Customer Name** | **Segment** | **City**          | **State**      | **Country**       | **Postal Code** | **Market** | **Region** | **Product ID**     | **Category**   | **Sub-Category** | **Product Name**                                                                 | **Sales**  | **Quantity** | **Discount** | **Profit**  | **Shipping Cost** | **Order Priority** |
|-------------------|--------------|----------------------|----------------------|------------------|----------------|------------------|-------------|------------------|----------------|------------------|----------------|------------|-----------|-------------------|---------------|-----------------|----------------------------------------------------------------------------------|------------|--------------|--------------|-------------|------------------|-------------------|
| CA-2012-124891    | No           | 31-07-2020 00:00    | 31-07-2020 00:00    | Same Day         | RH-19495       | Rick Hansen      | Consumer    | New York City    | New York        | United States    | 10024          | US         | East      | TEC-AC-10003033   | Technology     | Accessories     | Plantronics CS510 - Over-the-Head monaural Wireless Headset System                | 2309.65    | 7            | 0            | 762.1845    | 933.57           | Critical           |
| IN-2013-77878     | Yes          | 05-02-2021 00:00    | 07-02-2021 00:00    | Second Class     | JR-16210       | Justin Ritter    | Corporate   | Wollongong       | New South Wales| Australia        |                | APAC       | Oceania   | FUR-CH-10003950   | Furniture      | Chairs          | Novimex Executive Leather Armchair, Black                                        | 3709.395   | 9            | 0.1          | -288.765    | 923.63           | Critical           |
| IN-2013-71249     | No           | 17-10-2021 00:00    | 18-10-2021 00:00    | First Class      | CR-12730       | Craig Reiter     | Consumer    | Brisbane         | Queensland      | Australia        |                | APAC       | Oceania   | TEC-PH-10004664   | Technology     | Phones          | Nokia Smart Phone, with Caller ID                                                | 5175.171   | 9            | 0.1          | 919.971     | 915.49           | Medium             |

(*This table contains more rows. See the full dataset in the repository.*)

### 2️⃣ **Return Table**

This table contains information about returned orders.

| **Returned** | **Order ID**     | **Market**     |
|--------------|------------------|---------------|
| Yes          | MX-2013-168137   | LATAM         |
| Yes          | US-2011-165316   | LATAM         |
| Yes          | ES-2013-1525878  | EU            |
| Yes          | CA-2013-118311   | United States |
| Yes          | ES-2011-1276768  | EU            |

### 3️⃣ **People Table**

This table contains information about personnel and their respective regions.

| **Person**          | **Region**       |
|---------------------|------------------|
| Anna Andreadi       | Central          |
| Chuck Magee         | South            |
| Kelly Williams      | East             |
| Matt Collister      | West             |
| Deborah Brumfield   | Africa           |
| Larry Hughes        | AMEA             |
| Nicole Hansen       | Canada           |

---

## 📊 **Dashboard Segments**

The Dynamic Retail Dashboard is divided into the following segments for easy visualization and analysis.

### 1️⃣ **KPIs**

This segment provides key performance indicators to track overall retail performance.

| **Metric**                  | **Name**           | **Symbol** |
|------------------------------|--------------------|------------|
| Sum of Sales                | Total Sales        | 💰         |
| Sum of Profit               | Total Profit       | 📈         |
| Sum of Quantity             | Total Quantity     | 📦         |
| Count of Order ID           | Total Orders       | 🛒         |
| Sum of Profitability        | Profitability      | 💹         |

### 2️⃣ **Sales and Profit Analysis**

![image](https://github.com/user-attachments/assets/934fe42c-faa3-4109-82ea-b52ec3eeab20)

- **Visuals**: Scatter Plot.
- **Description**: Analysis of total sales and profit trends over time.

### 3️⃣ **Category-Wise Profit**

![image](https://github.com/user-attachments/assets/9c65e3c1-629d-40e9-b64d-c9d336c35753)



- **Visuals**: Pie chart.
- **Description**: Breakdown of profits by product category (e.g., Furniture, Technology, Office Supplies).

### 4️⃣ **Segment-Wise Sales Share (%)**

![image](https://github.com/user-attachments/assets/a44a6ed0-fd14-4577-8a41-65c3528b9851)




- **Visuals**: Donut chart.
- **Description**: Sales distribution across different customer segments (Consumer, Corporate, Home Office).

### 5️⃣ **Sales by Country**

![image](https://github.com/user-attachments/assets/21b64f54-0e0a-4404-96a2-f59357b84073)

- **Visuals**: Geo-mapped chart.
- **Description**: Visualization of sales performance by country.

### 6️⃣ **Top 5 Subcategories**

![image](https://github.com/user-attachments/assets/44894346-db14-4cdd-917a-1343d66f02a4)


- **Visuals**: Vertical bar chart.
- **Description**: Displays the top 5 performing subcategories based on sales.

### 7️⃣ **Bottom 5 Subcategories**

![image](https://github.com/user-attachments/assets/d0a4b3ba-7727-44a0-8304-405a44abae5e)


- **Visuals**: Horizontal bar chart.
- **Description**: Displays the bottom 5 subcategories based on sales performance.

### 8️⃣ **Yearly Sales Trend**

![image](https://github.com/user-attachments/assets/bb50096e-a1ee-46c7-b3e1-7f7edd894528)



- **Visuals**: Line chart.
- **Description**: Yearly trend of sales to identify seasonal or annual patterns.

---

## ⚙️ **Data Transformations**

Several transformations have been applied to clean and prepare the data for analysis:

1. **Data Cleaning**: 
   - Removing unnecessary spaces and null values.
   - Standardizing date formats.

2. **Merging Tables**:
   - Joining **Order Table** with **Return Table** to identify returned orders.
   - Adding region data from **People Table** to enrich customer information.

3. **Calculations**:
   - Calculating total sales, profit, and quantity.
   - Creating derived metrics such as profit margin and profitability.

---

## 🚀 **How to Use**

1. **Download the Repository**:
   - Clone the repository or download the ZIP file.

   ```bash
   git clone https://github.com/yourusername/dynamic-retail-dashboard.git
   ```

2. **Open the Excel File**:
   - Open `dynamic_retail_dashboard.xlsx` in Microsoft Excel.

3. **Ensure Data Connections**:
   - Make sure you are connected to the internet for GitHub data connections to refresh.

4. **Refresh Data**:
   - Go to **Data** > **Refresh All** to fetch the latest data.

---

## 📚 **Dependencies**

- **Microsoft Excel** (version 2016 or later recommended)
- Internet connection for live data updates.

---

## 🏆 **Key Insights**

- **Total Sales and Profit Trends** over time.
- **Top and Bottom Subcategories** to identify best and worst performers.
- **Sales Distribution by Segment and Country** for targeted analysis.
- **Profit Margins** to assess overall business profitability.

---

## 🤝 **Contributions**

Contributions are welcome! Feel free to:

- Fork the repository.
- Create a new branch.
- Submit a pull request.

---

## 📧 **Contact**

For any queries or feedback, please contact:

**Name**: Aman Kumar  
**Email**: amankumar00007ak@gmail.com  
**GitHub**: Aman0007ak

**Dashboard**
![image](https://github.com/user-attachments/assets/02774262-9cfb-4a3f-b81a-68740b8deaef)																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										
																										



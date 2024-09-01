<h1 align = center style="color: aqua;"> <span style="color:aqua;">🍕PIZZA SALES REPORT </h1>


<img src="https://github.com/user-attachments/assets/c085ee54-b802-4e6f-9286-5f5ff71af9e8" alt="Power BI Report" style="width: 45%;"> &nbsp;&nbsp;  <img src="https://github.com/user-attachments/assets/c8615af6-2067-46bc-a823-d7caeaf817a0" alt="Power BI Report" style="width: 45%;">

<div style = " margin-top: 30px;text-align : center">

![GitHub forks](https://img.shields.io/github/forks/usmanbvp/pizza-sales-report?style=flat-square&logo=github)
![GitHub Repo stars](https://img.shields.io/github/stars/usmanbvp/pizza-sales-report?logo=GitHub)
![GitHub contributors](https://img.shields.io/github/contributors/usmanbvp/pizza-sales-report?logo=github&color=blue)
[![MIT License](https://img.shields.io/badge/MIT%20License-blue?style=flat-square&logo=Github&logoColor=black)](https://github.com/usmanbvp/pizza-sales-report/blob/main/LICENSE)
![GitHub pull requests](https://img.shields.io/github/issues-pr/usmanbvp/pizza-sales-report?style=flat-square&logo=github&logoColor=black)
![GitHub issues](https://img.shields.io/github/issues/usmanbvp/pizza-sales-report?logo=github&logoColor=black)


</div>

## 📜 Description
This project features a Power BI dashboard that provides an in-depth analysis of pizza sales data. The dataset used was sourced from Kaggle and includes detailed information on sales transactions, pizza categories, and customer orders. The objective of this project is to uncover insights into sales performance, customer preferences, and product profitability.

## ⭐ Key Features

 <ul>
 <li> <b>Interactive Visualizations:  </b>  Explore sales performance by region, product, and time period.</li>

 <li> <b> Customer Segmentation: </b> Identify different customer groups based on their purchasing behavior. </li>

<li> <b> Profitability Analysis:  </b> Understand which products are most profitable. </li>

<li> <b> Time-Based Analysis: </b>Discover peak sales periods and seasonal trends. </li>

 </ul>

## 📊 Data Source
The data for this project was obtained from the [Kaggle](https://www.kaggle.com/datasets/nextmillionaire/pizza-sales-dataset?select=pizza_sales.csv). The dataset contains the following columns:

    pizza_id: Unique identifier for each pizza.

    order_id: Unique identifier for each order.

    pizza_name_id: Identifier linking each pizza to its name.

    quantity: Number of pizzas ordered.

    order_date: Date when the order was placed.

    order_time: Time when the order was placed.

    unit_price: Price per unit of pizza.

    total_price: Total price for the quantity ordered.

    pizza_size: Size of the pizza (e.g., Small, Medium, Large).

    pizza_category: Category of the pizza (e.g., Veg, Non-Veg).

    pizza_ingredients: Ingredients used in the pizza.

    pizza_name: Name of the pizza.

## 🔄 Data Transformation

### SQL Analysis

The raw data was first processed using SQL, with the following key transformations:
 <ul>
 <li> <b>Data Cleaning: </b>  Removed duplicates and handled missing values.</li>

 <li> <b> Metric Calculations:</b> Calculated key metrics such as total sales, average order value, and profit margins. </li>

<li> <b>Data Aggregation: </b> Grouped data by various dimensions (e.g., date, pizza category) to prepare for analysis in Power BI. </li>

 </ul>

### Power BI Processing

After SQL processing, the data was imported into Power BI for further analysis. In Power BI, additional transformations were applied:

- <b>Calculated Columns:</b> Created columns for metrics like sales growth and customer lifetime value.

## 📈 Visualizations
The Power BI dashboard features the following visualizations:
<ul>
    <li> <b>Sales Performance:</b> A bar chart showing total sales broken down by pizza category and region.
    </li>
   
 <li> <b> Customer Segmentation: </b> A pie chart categorizing customers based on order frequency and pizza preferences.
    </li>
    <li> <b> Time Series Analysis: </b> A line graph illustrating sales trends over time, highlighting peak periods. </li>

</ul>

## 🔍 Insights

 <ul>
 <li> <b>Top-Selling Pizzas:  </b>  The dashboard reveals which pizzas are most popular and contribute the most to overall sales.</li>

 <li> <b> Customer Behavior: </b> It identifies key customer segments and their ordering patterns, helping to tailor marketing strategies. </li>

<li> <b>Profit Margins: </b> Analyzes which pizza sizes and categories yield the highest profit margins, providing actionable insights for pricing and promotions. </li>

 </ul>

## 🚀 How to Use
### SQL File:

- Run the SQL queries in the [data_analysis_with_sql.sql](data_analysis_with_sql.sql) file to clean and analyze the raw data.
- Export the cleaned and processed data for use in Power BI.

### Power BI File:

- Download the Power BI file Pizza Sales Report.pbix.
- Open it in Power BI Desktop.
- Interact with the dashboard by using filters, drilling into specific data points, and exploring the various visualizations.
- Customize the data model or visualizations for deeper analysis or specific use cases.

## 🔧 Future Enhancements
 <ul>
 <li> <b>Real-Time Data Integration:  </b>  Implement a live connection to update the dashboard in real time with new sales data.</li>

 <li> <b> Advanced Analytics:  </b> Use predictive modeling to forecast future sales trends and customer behaviors. </li>

<li> <b>Customer Feedback: </b>  Integrate customer feedback data to correlate with sales and identify areas for improvement. </li>
 </ul>


## 📄 License

This project is licensed under the GPL License - see the [LICENSE](LICENSE) file for details.

## 📝Feedback and Support
If you have any feedback, suggestions, or questions regarding the project, please create an issue in the repository or contact me at usman.bvp@gmail.com. or [LinkedIn](https://www.linkedin.com/in/usmanbvp/)
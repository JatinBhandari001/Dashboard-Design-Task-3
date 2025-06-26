<h1>Dataset use</h1>
This project is based on a dataset named Amazon_sales.xlsx, which contains sales records for an e-commerce platform resembling Amazon. The dataset includes detailed transactional data such as: 

->Order ID<br>
->Product Name<br>
->Category & Sub-Category<br>
->Sales, Quantity, and Profit<br>
->Shipping Cost<br>
->Order & Ship Dates<br>
->Customer Segments<br>
->Geographical Information (State, Country)<br>
->Delivery Status<br>

This dataset was used to build an interactive Power BI Dashboard for business insights and decision-making.<br>

<i> Data Source: E-Commerce Sales Dataset.csv </i> 

**Tools used**
-> Excell for data cleaning<br>
->PowerBI for Dashboard 

<h2>Data visualization</h2>
<p><strong> Description :</strong>Interactive Power BI dashboard showcasing data visualization and storytelling techniques, focusing on key insights, trends, and actionable findings..</p>
![image](https://github.com/user-attachments/assets/c170cf87-b07b-4939-b0a1-a1e286d18d23)

**New meassures:-**

1. Cancelled Orders = 
CALCULATE(
    DISTINCTCOUNT('E commerce sales data'[Order ID]),
    'E commerce sales data'[Status] = "Cancelled"
)<br>
2. MonthYear = FORMAT('E commerce sales data'[Date], "MMM YYYY") 


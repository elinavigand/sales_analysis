# Sales Data Analysis

### Objective: 
Analyse and visualise sales data.

## Step 1: Generate dummy data

**Data Source:** Synthetic sales data
**Data Size:** 500 sales records, 8 columns, period: 01.01.2023-31.12.2023
**Data:**
- CustomerID: unique identifier for each customer.  
- PurchaseID: unique identifier for each purchase.  
- PurchaseAmount: the amount paid for devices.  
- DevicesPurchased: the number of devices bought.  
- AddedSalesAmount: the amount for add-on sales.  
- PurchaseDate: the date of the purchase.  
- TotalAmount: the total purchase amount (sum of devices and additional sales).  
- AvgDeviceAmount: the average device amount; 100 records have missing values (NaN) because there was no device purchase made.  

## Step 2: Get Insights

**Overall Insights:**
- Total sales: CHF 480,454.22  
- Device sales: CHF 407,512.46  
- Add-on sales: CHF 72,941.76  

- Number of devices purchased: 995  
- Maximum device price: CHF 1,996.07  
- Average device price: CHF 409.56  
- Minimum device price: CHF 108.80  

- Maximum add-on sales: CHF 498.35  
- Average add-on sales: CHF 145.88  
- Minimum add-on sales: CHF 2.16  

**Quarterly performance insights:**
- The number of sales remains stable across quarters(Q1 124, Q2 125, Q3 126, Q4 125), indicating consistent sales activity.  
- Q2 stands out with the **highest purchase amount (CHF 115,910.14)** and **average device price (CHF 445.81)**, suggesting a successful quarter for device sales.  
- Q3 has the **lowest purchase amount (CHF 97,164.57)** and **average device price (CHF 369.45)**, potentially indicating lower-priced devices or discounts.


## Where to find the files
1. Data processing/transformation scripts are being kept [here.](https://github.com/elinavigand/sales_analysis/blob/main/Sales_Analysis_20240802.ipynb)
2. Data visualisation examples are being kept [here.](https://github.com/elinavigand/sales_analysis/tree/main/pictures)



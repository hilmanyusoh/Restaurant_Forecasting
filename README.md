# Balaji Fast food Sales

## **Overview** 
- 1.Load the data: Load the CSV file into a pandas DataFrame.
- 2.Removing rows with missing values (NaN) from the dataset
- 3.Categorizing sales into daytime and nighttime
- 4.Group by time and items:
- 5.Visualize the data (Optional):
  * 5.1 Total Sales Distribution by Time of Sale
  * 5.2 Daytime: Menu vs Beverages
  * 5.3 Nighttime: Menu vs Beverages

## **About dataset**           
This dataset provides sales information for Balaji Fast Food Restaurant, including various food items. The dataset includes the following fields:
- The data is a CSV file with 10 columns and 1001 rows.
    * Date
    * Item Name
    * Item Type
    * Item Price
    * Quantity
    * Transaction Amount
    * Transaction Type
    * Received By
    * Time of Sale
  

## **Objective**
 To explore sales data of menu items in restaurants during day and night and predict which food and beverage items customers buy during day and night and at what price in 'Balaji Fast Food' restaurants the most.

## 1.Load the data: Load the CSV file into a pandas DataFrame.
Load the CSV file into a pandas DataFrame using the pd.read_csv() function. This function reads the CSV file and creates a DataFrame, which allows for easy data manipulation and analysis.

### 2.Removing rows with missing values (NaN) from the dataset
Removing Rows with Missing Values,Remove any rows that contain missing values (NaN) from the dataset using the dropna() method. This ensures that subsequent analyses are based on complete data.

## 3.Categorizing sales into daytime and nighttime
Create a new column in the DataFrame to categorize sales as either daytime or nighttime based on the time of sale. This categorization allows for easier analysis of sales patterns throughout the day.

## 4.Group by time and items
Group the data by the newly created Time_Category and item name to aggregate sales data. This step helps to summarize the total sales amount and quantity for each item during daytime and nighttime.

## 5.Visualize the data (Optional):
Visualizations can provide insights into sales patterns. Using libraries like Matplotlib or Seaborn, you can create several types of plots:
  * 5.1 Total Sales Distribution by Time of Sale
  Visualize the overall sales distribution across different times of the day to identify peak sales periods.
  * 5.2 Daytime: Menu vs Beverages
  Compare the sales of menu items against beverages during the daytime to determine which category performs better.
  * 5.3 Nighttime: Menu vs Beverages
  Similar to daytime, analyze nighttime sales to observe differences in consumer preferences.





 
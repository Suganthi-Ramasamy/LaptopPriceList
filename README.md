# LaptopPriceList

**Usecases**

**Use Case 1: Data Cleaning and Basic Statistics**
- Load Dataset into dataframe ,

- Inspect Data (View the first few rows and get a summary of the DataFrame.),

- Handle Missing Values (Check for any missing values and handle them by filling them with appropriate values or dropping the rows.)

- Summary Statistics : Calculate basic summary statistics (mean, median, mode) for numerical columns like Price, RAM, and SSD.

- Count Unique Values for categorical data ( try to use for loop which will run on all the columns and get the count of values)
 
**Use Case 2: Data Filtering and Sorting**

- Filter Laptops by Brand : Extract all laptops from a specific brand, e.g., "Dell".
  
- Filter by RAM and SSD : Extract laptops that have at least 8 GB of RAM and an SSD of 256 GB or more.

- Sort by Price : Sort the filtered laptops by price in ascending and descending order.

- Filter Touchscreen Laptops : Extract laptops that have a touchscreen feature.

- Combine Filters : Extract laptops that meet multiple criteria, e.g., brand "HP", at least 8 GB RAM, and touchscreen.
 
**Use Case 3: Data Grouping and Aggregation**

- Group by Brand : Group laptops by brand and calculate the average price for each brand.
  
- Group by Processor Brand : Group laptops by processor brand and calculate the total count and average rating.

- Multiple Aggregations : Perform multiple aggregation operations (e.g., count, mean, median) on price and rating grouped by brand.
  
- Pivot Tables : Create a pivot table that shows the average price and the number of laptops for each combination of brand and processor brand.

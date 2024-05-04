# Car Showroom Analysis Project

## Overview
This project involves the analysis of a car showroom dataset using Microsoft SQL Server. The dataset includes information on cars, sales, and salespersons within the showroom. The primary objective is to identify key insights, analyze the business, and provide recommendations for improvement.

## Database Setup
The project begins by creating a database named `Car_Showroom` and three tables within it: `Cars`, `Sales`, and `salespersons`. The tables are structured as follows:

### Cars Table
- `car_id`: Unique identifier for each car
- `make`: Make or manufacturer of the car
- `type`: Type of car (e.g., sedan, SUV)
- `style`: Style of the car (e.g., coupe, hatchback)
- `cost_$`: Cost of the car

### Sales Table
- `sale_id`: Unique identifier for each sale
- `car_id`: Foreign key referencing the `car_id` in the `Cars` table
- `salesman_id`: Foreign key referencing the `salesman_id` in the `salespersons` table
- `purchase_date`: Date of purchase

### Salespersons Table
- `salesman_id`: Unique identifier for each salesperson
- `name`: Name of the salesperson
- `age`: Age of the salesperson
- `city`: City where the salesperson is located

## Objectives
The primary objectives of the analysis are as follows:
1. Identify details of all cars purchased in a specific year.
2. Determine the total number of cars sold by each salesperson.
3. Calculate the total revenue generated by each salesperson.
4. Determine the total revenue generated by each car type.
5. Retrieve details of cars sold by a specific salesperson in a particular year.
6. Calculate the total revenue generated by a specific car style (e.g., hatchback).
7. Calculate the total revenue generated by a specific car type (e.g., SUV).

## Queries
The project includes several SQL queries to achieve the objectives outlined above. Some of the key queries include:
- Retrieving details of cars purchased in a specific year.
- Calculating the total number of cars sold by each salesperson.
- Calculating the total revenue generated by each salesperson.
- Calculating the total revenue generated by each car type.
- Retrieving details of cars sold by a specific salesperson in a particular year.
- Calculating the total revenue generated by specific car styles and types.

## Recommendation
   💡 **Optimize Sales Strategies for High-Revenue Car Types**

Based on the insights gleaned from the analysis, the car showroom can benefit significantly by optimizing its sales strategies, particularly focusing on high-revenue car types. By identifying the top-selling car types and styles, the showroom can allocate resources more effectively, such as targeted marketing efforts or tailored sales incentives.

Additionally, leveraging the performance data of salespersons can help tailor training programs and incentives to enhance overall sales effectiveness. For instance, recognizing top-performing salespersons and incentivising them accordingly can boost morale and motivation, leading to improved sales performance across the board.

Moreover, investing in customer segmentation analysis can provide deeper insights into customer preferences and behaviors. By understanding the needs and preferences of different customer segments, the showroom can tailor its inventory, marketing campaigns, and sales approaches to better meet customer demands, thereby increasing customer satisfaction and loyalty.

Overall, by leveraging the insights gained from data analysis, the car showroom can make informed decisions to optimize its sales strategies, enhance salesperson performance, and ultimately maximize revenue.


## Conclusion
This project demonstrates the use of SQL for data analysis and provides valuable insights into the car showroom dataset. By analyzing sales data and salesperson performance, the business can make informed decisions to improve operations and maximize revenue.

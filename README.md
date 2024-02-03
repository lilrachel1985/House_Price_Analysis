# Rent_Price_Analysis  
Airbnb data for 250,000+ listings across 10 major cities, along with ~5 million guest reviews.
First we profile and QA the data
1.Import/Open the Listings.csv file
2.Cast any date columns as a datetime format
3.Filter the data down to rows where the city is Paris, and keep only the columns ‘host_since’, ‘neighbourhood’, ‘city’, ‘accommodates’, and ‘price’
4.We check for missing values, and calculate the minimum, maximum, and average for each numeric field

Second,
We Prepare the data for visualization

1.Create a table named paris_listings_neighbourhood that groups Paris listings by 'neighbourhood' and calculates the mean price (sorted low to high)
2.Create a table named paris_listings_accomodations, filter down to the most expensive neighborhood, group by the ‘accommodations’ column, and add the mean price for each value of ‘accommodates’ (sorted low to high)
3.Create a table called paris_listings_over_time grouped by the ‘host_since’ year, and calculate the average price and count of rows representing the number of new hosts

Third, 
We Visualize the data and summarize findings
1.Create a horizontal bar chart of the average price by neighborhood in Paris, and make sure to add a title and change axis labels as needed
2.Create a horizontal bar chart of the average price by ‘accommodates’ in Paris’ most expensive neighborhood, and make sure to add a title and change axis labels as needed
3.Create two line charts: one showing the count of new hosts over time, and one showing average price. Set the y-axis limit to 0, add a title, and change axis labels as needed
4.Based on your findings, what insights do you have about the impact of the 2015 regulations on new hosts and prices?
5. Finally, we Create a dual axis line chart to show both new hosts and average price over time


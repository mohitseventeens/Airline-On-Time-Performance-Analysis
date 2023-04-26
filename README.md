# Airline On-Time Performance Analysis

This repository contains an analysis of the Airline On-Time Performance dataset from the Data Expo 2009 competition organized by the American Statistical Association. The dataset consists of domestic flights in the United States between 1987 and 2008, and is sourced from the United States Department of Transportation's (DOT) Bureau of Transportation Statistics.

The goal of this project is to explore, analyze, and visualize the dataset to uncover interesting patterns, trends, and relationships that can provide insights into factors affecting flight delays and cancellations.

## Dataset

The dataset contains information on approximately 120 million domestic flights, including:

1. Year, month, and day of the flight
2. Day of the week
3. Carrier (airline) code
4. Flight number
5. Origin and destination airports (by IATA code)
6. Scheduled and actual departure and arrival times
7. Flight delays and cancellations
8. Reason for delay or cancellation (e.g., weather, carrier, National Air System, or security)
9. Air time and distance
10. Taxi in and out times

The data is split into separate files for each year from 1987 to 2008. You can download the dataset files from the following webpage: http://stat-computing.org/dataexpo/2009/the-data.html

For now I am using data from year 2005 and 2006. The whole dataset is huge and later I'll try to use the whole dataset in the future.

## Research Questions

This project aims to answer the following research questions:

1. How has the on-time performance of airlines evolved over time?
2. What are the main factors affecting flight delays and cancellations?
3. How do different airlines compare in terms of on-time performance?
4. Are there any specific airports or routes that are more prone to delays and cancellations?
5. Can we identify patterns in flight delays based on the day of the week, time of day, or season?
6. When is the best time of day, day of the week, or time of the year to fly to minimize delays?
7. Do older planes suffer more delays?
8. How does the number of people flying between different locations change over time?
9. How well does weather predict plane delays?
10. Can you detect cascading failures as delays in one airport create delays in others? Are there critical links in the system?

## Contributing

Contributions to this project are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch with a descriptive name.
3. Make your changes and commit them with clear and concise commit messages.
4. Submit a pull request with a description of your changes.

## License

This project is released under the MIT License. For more information, please refer to the `LICENSE` file in the repository.

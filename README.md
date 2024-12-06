# Simulating Ride-Sharing Service Dispatch System 

## Project Overview
This project simulates and analyzes rideshare data from Uber and Lyft, using a custom event-driven simulation built with SimPy. The analysis includes ride cancellations, price trends, driver availability, ride durations, and more. It incorporates weather conditions, ride types, and surge pricing to simulate realistic scenarios.

You can download the dataset from the following link: [Download rideshare_kaggle.csv](https://www.kaggle.com/datasets/mohan28169/rideshare-kagglecsv)

## Key Features
- **Ride Simulation**: Simulate real-time ride processes, including cancellations, driver availability, and pricing adjustments.
- **Event Logging**: Detailed event logging for every ride, including timestamp, price, weather conditions, and cancellation reasons.
- **Data Analysis**: Perform statistical analysis on cancellations, ride prices, driver availability, and ride durations.
- **Geospatial Visualization**: Visualize the rides on a map using Folium, with weather data and pricing information.

## Data Analysis
- **Cancellation Rates**: The cancellation rate of rides is computed and displayed.
- **Price Trends**: Average price analysis based on ride types, including adjustments for weather and surge pricing.
- **Driver Availability**: Analyze the rate of unavailable drivers based on simulated events.
- **Ride Duration**: Calculate and display the average ride duration for completed rides.
- **Cancellation and Completion Trends**: Visualize cancellation and ride completion trends over time.

## Requirements
- Python 3.x
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Folium, SimPy


# Real-Time Order Book Visualization and Analysis

## Description
This Python script fetches real-time order book data from the Binance API, visualizes it using Plotly, and performs analysis on the top 5 highest total value prices for both bids and asks. It provides a comprehensive overview of the order book dynamics for a specified cryptocurrency trading pair.

## Features
- **Order Book Data Retrieval**: Fetches order book data for a specified cryptocurrency trading pair from the Binance API.
- **Visualization with Plotly**: Creates a line chart to visualize the order book dynamics, showing the cumulative total value at each price level for both bids and asks.
- **Top 5 Price Analysis**: Identifies and analyzes the top 5 highest total value prices for both bids and asks, providing insights into market depth and liquidity.
- **Data Export**: Saves the analyzed data to a CSV file with a timestamp for further analysis or reporting purposes.
- **Integration with Telegram (Optional)**: Can be extended to send the analyzed data to a Telegram channel or chat for real-time monitoring.

## Usage
1. Modify the `symbol` variable to specify the cryptocurrency trading pair (e.g., 'BTCUSDT').
2. Adjust the `limit_values` list to define the desired limit values for the order book data.
3. Run the Python script in a Python environment.
4. The script will fetch real-time order book data, create a visualization, and analyze the top 5 highest total value prices.
5. The analyzed data will be printed to the console and saved to a CSV file with a timestamp.

## Dependencies
- Python 3.9.18
- plotly: Interactive visualization library.
- pandas: Data manipulation library.
- requests: HTTP library for making API requests.

## Note
- Ensure you have an active internet connection to fetch real-time data from the Binance API.
- This script is for educational purposes and demonstrates order book visualization and analysis techniques.

## Contact
For any inquiries or support, please contact arman13m99@gmail.com

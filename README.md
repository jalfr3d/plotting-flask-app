# Flask Stock Plot Web App

A Flask web application that allows you to plot stock or cryptocurrency data using Yahoo Finance (yfinance) and Bokeh for interactive candlestick charts. You can visualize the historical data of your favorite stocks or cryptocurrencies.

## Features

- **Candlestick Charts**: Create interactive candlestick charts to visualize stock or cryptocurrency price data.

- **Date Range**: Choose a specific date range to view historical data.

- **Navigation**: Navigate through the web app with options like 'Home', 'About', and 'Plot'.

## Dependencies

- Python 3.x
- Flask: A micro web framework for Python.
- yfinance: A Python library to fetch financial data from Yahoo Finance.
- Bokeh: An interactive visualization library.
- HTML/CSS templates: Used for rendering web pages.

## Usage

1. Clone the repository to your local machine.

2. Install the required Python libraries using pip:

   ```bash
   pip install Flask yfinance bokeh
3. Run the Flask web application:
   ```
   python main.py
   ```
4. Access the web app through a web browser by opening the URL http://127.0.0.1:5000/.

5. Use the navigation links to go to the 'Plot' page.

6. Input the desired stock or cryptocurrency symbol, and the app will display an interactive candlestick chart of historical data.

## Web Pages
### Home
The default landing page with navigation links.
Accessible at http://127.0.0.1:5000/.

### About
A page with information about the web app.
Accessible at http://127.0.0.1:5000/about/.

### Plot
The main page for generating interactive candlestick charts.
Enter the stock or cryptocurrency symbol to view its historical data in the form of candlestick charts.
Accessible at http://127.0.0.1:5000/plot/.

## Customize and Enhance
- You can customize the design and layout of the HTML templates to match your preferences.

- Extend the functionality by adding more technical indicators and interactive features to candlestick charts.

- You may explore other data sources and APIs to gather financial data beyond Yahoo Finance.

- Secure the application if you plan to deploy it to a production environment.

Feel free to use, modify, and distribute this project for your purposes. Contributions and feedback are welcome!

Happy stock plotting!

## License
This project is licensed under the MIT License. You are free to use and modify the code for your own purposes.

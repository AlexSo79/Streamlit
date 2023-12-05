# Fantasy Football Analysis

This is a Streamlit app that allows users to explore and visualize data from the Fantasy Premier League (FPL) 2020/21 season. The app uses a dataset of FPL player statistics scraped from the official website. The app allows users to filter the data by position, team, and price, and to see various charts and tables of player performance.

## Requirements

To run this app, you will need the following packages:

- pandas
- numpy
- streamlit
- vega-lite

You can install them using pip or conda.

## Usage

To run this app, simply navigate to the folder where the app.py file is located and type the following command in the terminal:

```bash
streamlit run app.py
```

This will launch the app in your default browser. You can then use the sidebar to select the filters and see the results in the main area.

## Features

The app has the following features:

- A sidebar that allows users to choose the position, team, and maximum price of the players they want to see.
- A dataframe that shows the filtered players and their FPL statistics, such as points, goals, assists, cost, etc.
- A scatter plot that shows the relationship between cost and points for the filtered players, colored by position.
- A scatter plot that shows the relationship between goals per 90 minutes and assists per 90 minutes for the filtered players, colored by position.

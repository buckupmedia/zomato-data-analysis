# zomato-data-analysis

This repository contains a Python project that performs data cleaning and analysis on a dataset of restaurants, specifically using the zomato.csv file. The dataset includes various attributes of restaurants such as rating, location, cost, and type of cuisine. This project uses libraries such as Pandas, NumPy, Matplotlib, and Seaborn to perform the analysis and visualization of the data.
Project Overview

    Data Cleaning:
        Removal of unwanted characters and formatting issues from the rate and cost2plates columns.
        Handling of missing values using mean, mode, or placeholder values.
        Renaming columns for better clarity and dropping redundant columns.

    Data Analysis:
        Analyzing the distribution of restaurants based on online order availability, table booking options, restaurant types, and price ranges.
        Visualizing data using pie charts, bar plots, and count plots.

    User Interaction:
        Providing an interactive feature to query the dataset based on user input for ratings and locations.

Getting Started
Prerequisites

Make sure you have the following libraries installed:

    numpy
    pandas
    matplotlib
    seaborn

You can install them using pip:

bash

pip install numpy pandas matplotlib seaborn

Dataset

The dataset used in this project is zomato.csv, which should be placed in the same directory as the script. The dataset includes the following columns:

    rate: Restaurant ratings
    approx_cost(for two people): Estimated cost for two people
    cuisines: Types of cuisine offered
    location: Location of the restaurant
    dish_liked: Dishes liked by customers
    rest_type: Type of restaurant
    online_order: Availability of online ordering
    book_table: Availability of table booking
    phone: Contact phone number
    listed_in(type): Type of restaurant listing
    listed_in(city): City of the restaurant
    name: Name of the restaurant
    address: Address of the restaurant

Running the Analysis

    Clone this repository:

    bash

git clone https://github.com/your-username/zomato-analysis.git
cd zomato-analysis

Place the zomato.csv file in the repository directory.

Run the Python script:

bash

    python analysis.py

    Follow the prompts to interact with the data and view the visualizations.

Code Explanation

    Data Cleaning: Handles missing values and cleans data columns.
    Data Visualization: Uses Matplotlib and Seaborn for plotting various charts.
    User Interaction: Allows users to query the dataset based on rating and location.

Examples
Pie Chart for Online Orders

Bar Plot for Restaurant Types

Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements or bug fixes.
License

This project is licensed under the MIT License - see the LICENSE file for details.

Airbnb NYC 2019 Data Analysis

📌 Overview
This project analyzes Airbnb listings in New York City for the year 2019. Using publicly available data, it explores trends in pricing, availability, location distribution, and other features of short-term rentals. The analysis is conducted in Python using a Jupyter Notebook.

📂 Project Structure
yaml
Copy
Edit
├── Airbnb_Analysis.ipynb   # Main Jupyter Notebook with code and analysis
├── Airbnb NYC 2019.csv     # Dataset containing NYC Airbnb listings for 2019
└── README.md               # Project documentation
📊 Dataset
The dataset (Airbnb NYC 2019.csv) contains information on over 48,000 Airbnb listings, including:

Listing details: name, host ID, host name, room type, price, minimum nights

Location: neighbourhood group (borough), neighbourhood, latitude, longitude

Engagement: number of reviews, last review date, reviews per month

Host activity: calculated host listings count, availability over the year

Source: Inside Airbnb

🛠️ Tools & Libraries
The analysis uses:

Python 3

pandas – data manipulation

numpy – numerical operations

matplotlib & seaborn – data visualization

Jupyter Notebook – interactive development

🔍 Analysis Highlights
The notebook covers:

Data Cleaning – handling missing values, correcting datatypes

Exploratory Data Analysis (EDA) – summary statistics and feature distributions

Geospatial Insights – borough-wise and neighbourhood-wise trends

Price Analysis – how prices vary by location and room type

Availability & Reviews – seasonal and popularity patterns

📈 Key Insights
Manhattan and Brooklyn dominate the NYC Airbnb market.

Entire homes/apartments tend to be significantly more expensive than private rooms.

Certain neighbourhoods show extreme outlier prices, requiring careful filtering in analysis.

Availability varies widely, with some listings open year-round and others seasonally.

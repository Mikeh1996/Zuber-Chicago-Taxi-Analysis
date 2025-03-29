# Chicago Taxi Data Analysis (SQL)
## Inspiration
This project marks an end to end analysis combining SQL and Python to investigate real world transportation data. My goal was to explore how external factors like weather influence passenger behavior and taxi service dynamics in Chicago. A major breakthrough came from writing SQL queries to extract structured insights and using Python for deeper analysis and visualization. It was also my first time parsing HTML to extract weather data, which helped shape a more complete picture of ride behavior. This project pushed me to work across tools and apply statistical reasoning to support insights.

## Problem Statement
The dataset focuses on taxi rides in Chicago during November 2017. The objective is to assist a new ride sharing startup, Zuber, in understanding passenger behavior and market dynamics. This project uses SQL to parse, explore, and test hypotheses on taxi data, while Python is used for data cleaning, visualization, and interpretation. The project involves:

* Extracting and preparing weather data from an HTML file

* Analyzing ride patterns by company and time frame using SQL

* Testing if rainy weather influences trip durations between key locations

* Visualizing trends using Python and drawing actionable insights

## Key Questions Explored
* What companies dominate the taxi market during high-traffic days?

* How do ride frequencies change under specific weather conditions?

* Do weather patterns like rain affect trip durations to major airports?

* Which neighborhoods see the most taxi drop-offs?

* How can Zuber use this information to gain a market advantage?

## What I Learned from This Project
This was my first project applying SQL at scale alongside Python for full cycle analysis. Key learning milestones included:

* Writing complex SQL queries to filter and aggregate data

* Using pattern recognition and regular expressions in Python for data cleaning

* Parsing HTML content to extract structured weather data

* Combining SQL-extracted data with Python visualizations to communicate insights

* Structuring a hypothesis test with statistical reasoning

* Integrating weather data into ride data for more nuanced insights

## Project Execution
### Setting Up the Environment
To run this project locally, ensure you have the following Python libraries installed:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scipy re statistics
You will also need access to a database (e.g., PostgreSQL) to run the SQL queries.

### Data Collection
This project uses multiple datasets:

* Taxi ride data for November 2017

* Weather data parsed from a provided HTML file

* Neighborhood and company reference tables

### Analysis Overview
* Parsed and cleaned HTML based weather data using regular expressions

* Queried taxi ride data using SQL for insights into volume and duration

* Joined ride and weather data to support hypothesis testing

* Visualized neighborhood drop offs and company performance

* Conducted statistical tests to explore the effect of weather on trip durations

## How to Run the Project Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/YOUR-USERNAME/Zuber-Chicago-Taxi-Analysis.git
cd Zuber-Chicago-Taxi-Analysis
Set up a virtual environment and install dependencies:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
Launch the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook SQL.ipynb

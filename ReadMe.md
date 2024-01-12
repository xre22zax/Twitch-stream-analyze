# Uncover Viewer Insights and Trends: Twitch Gaming Data Analysis


## Overview


Here's an enhanced version of your README, incorporating suggestions for improvement:

# Uncover Viewer Insights and Trends: Twitch Gaming Data Analysis

## Overview

Dive into the world's leading gaming live streaming platform! This project analyzes Twitch user behavior and preferences by exploring two datasets: stream viewing data and chat room usage data. Discover key insights into popular games, viewer locations, streaming sources, game genres, hourly viewership patterns, and more.

---

## Empowering the Analysis :

+ SQL: Interact with databases for efficient data retrieval and manipulation.
+ SQLite: Manage and query the datasets locally.
+ pandas: Create and manipulate DataFrames for seamless data analysis.
+ numpy: Perform numerical computations and array operations.
+ matplotlib.pyplot: Generate compelling visualizations to communicate insights.

---

### Methods Employed :

1. Data manipulation:

`range`, `FOR loop`, `GROUP BY`, `DISTINCT`, `ORDER BY`, `COUNT`, `WHERE()`, `WHEN()`, `strftime`, `JOIN`


    
</br>

2. Data visualization:

`fill_between`, `set_yticks`, `y_lower, y_upper`, `tight_layout`, `explode`, `shadow`, `startangle`, `autopct`, `pctdistance`, `gca()`

---

## Graphs :

* Bar chart
* plt.hist (histogram plot)
* Line Chart with error



---

## Key Findings :

* Identify unique games and channels in streams.
* Uncover the most popular games captivating viewers.
* Pinpoint the geographical hotspots for LoL stream viewership.
* Discover preferred streaming sources among users.
* Categorize games into genres for deeper insights.
* Explore hourly viewership patterns to uncover peak engagement times.

---

## Getting Started: Join the Exploration

1. **Clone the Repository:**
   - Bring the project to your local machine.

2. **Install Essential Libraries:**
   - `pip install pandas numpy matplotlib`

3. **Activate the SQLite Environment:**
   - **Using a terminal:**
      - Open a terminal window and navigate to the project directory.
   - **Using a Python IDE:**
      - Open the project in your preferred Python IDE.

4. **Connect to the SQLite Database:**
   - Execute the following command in your terminal or IDE:

     ```bash
     sqlite3 twitch_gaming_data.db  # Replace with your actual database file name
     ```

5. **Explore Data and Run Queries:**
   - Use the SQLite command prompt to interact with the database:

     ```sqlite
     .tables  # View available tables
     .schema table_name  # View table structure
     SELECT * FROM table_name;  # Retrieve all data from a table
     -- Execute other SQL queries as needed
     

6. **Ignite the Analysis:**
   - Run the main Python script: `Visualize Twitch Gaming Data.ipynb`

</br>

**Additional Tips:**

- If using a Python IDE, consider installing a plugin for SQLite integration, often providing a user-friendly interface for running commands.
- Provide specific examples of SQL queries relevant to your analysis to guide users further.



---

## Usage

- Explore Visualizations: Gain valuable insights from the generated charts and plots.
- Experiment and Customize: Modify the code to tailor analyses and visualizations to your specific interests.

---


## Contributing

Feel free to submit issues or pull requests for improvements or additions.

---

## Author

[Reza Sadeghi](https://github.com/xre22zax/)

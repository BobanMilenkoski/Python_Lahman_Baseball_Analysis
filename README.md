# Lahman Baseball Database Analysis

## Overview
This project performs an analysis of the Lahman Baseball Database using Python. The database contains detailed statistics on Major League Baseball (MLB) players, teams, and games, and this project focuses on extracting, analyzing, and visualizing various aspects of the dataset.

Key analyses include:
- Active players in the database
- Top players by RBIs from 2015 to 2018
- Players with missing batting data
- Active players with batting data
- Visualizations of triples, stolen bases, and team performance metrics (such as runs and wins)
- College player production analysis

---

## Requirements
To run this project, you will need the following Python packages:
- `pandas` - For data manipulation and analysis
- `matplotlib` - For creating visualizations
- `sqlite3` - To interact with the SQLite database

---

## Project Structure
- `lahman.sqlite` - SQLite database file containing Lahman’s baseball data.
- `Lahmans_Baseball_Project_Boban_Milenkoski.ipynb` - Python script with the code for querying and analyzing the database.
- `README.md` - This readme file that provides details about the project.

---

## Queries and Analyses

1. **Active Players**  
   Identifies players who are still active by checking if their `finalGame` date is NULL or in the future.

2. **Top Players by RBIs (2015-2018)**  
   Finds the players with the most RBIs between 2015 and 2018.

3. **Players with Missing Batting Data**  
   Finds players in the People table who do not have corresponding batting data in the Batting table.

4. **Active Players with Batting Data (2015-2018)**  
   Identifies active players who have batting data available from 2015 to 2018.

5. **Top RBI Player from 2015-2018**  
   Calculates and identifies the player with the most total RBIs between 2015 and 2018.

6. **Triples (3B) Per Year**  
   Aggregates the total number of triples hit each year, providing insight into triples trends.

7. **Triples vs Steals**  
   Explores the relationship between triples hit and stolen bases for each player through a scatter plot.

8. **Percentage of Players Who Hit Triples and Stole Bases**  
   Shows the percentage of players who hit triples and also stole bases in a given year using a pie chart.

9. **Correlation Between Runs and Wins**  
   Analyzes the correlation between the number of runs scored and the number of wins a team achieves.

10. **Top Colleges Producing Baseball Players**  
    Identifies the top colleges that have produced the most baseball players by counting players in the CollegePlaying table.

---

## Visualizations
The project also includes various visualizations to help interpret the data:
- Histogram of total triples per year.
- Scatter plot of triples (3B) vs stolen bases (SB).
- Pie chart of players who hit triples and stole bases.
- Scatter plot of runs scored vs wins for teams.
- Bar plot of the top 20 colleges producing the most baseball players.

---

## Running the Project
To run the project:
1. **Download the Lahman Database**: Ensure that the `lahman.sqlite` SQLite database is available in your working directory.
2. **Run the Python Script**: Execute the script `baseball_analysis.py` to perform the analysis and visualize the results.

---

## Conclusion
This project provides an insightful analysis of the Lahman Baseball Database using Python, enabling users to extract meaningful insights about MLB players, teams, and statistics. It also demonstrates how to interact with and analyze a large database using SQL queries and Python libraries.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



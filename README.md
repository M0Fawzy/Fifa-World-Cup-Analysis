## Data Source

The Data Set Used In The Project: <https://www.kaggle.com/datasets/piterfm/fifa-football-world-cup?select=matches_1930_2022.csv>

## Target Audience

- Sports Analysts and Journalists: Professionals who need to analyze and report on football statistics, trends, and historical comparisons.
- Football Historians and Researchers: Individuals who study the history of football and the World Cup.
## Data Cleaning

Types Of Data Cleaning Applied:

-   Fixing Typos
-   Splitting Columns
-   Replacing Null Values With (0)
-   Removing Unnecessary Columns
-   Changing Data Types
-   Correcting Stadium And City Names
-   Data Parsing

    Transforming Rows From (['68&rsquor;\|2:0\|Cristian Romero', '71&rsquor;\|3:0\|Nicolás Otamendi']) To The Number Of Yellow Cards Received Using Regex:

    ![image](https://github.com/user-attachments/assets/674f9c74-7996-4107-8713-efde1db34046)


    ## Data Modeling

    A Star Schema Was Implemented:

    ![image](https://github.com/user-attachments/assets/acdf0855-aa07-4e64-a49e-9fa51716480b)


    Fact Table: Match

    Dimension Tables: World Cup-Stadium-Teams-Date

    ## Dashboards

    There Was A Total Of Four Dashboards:

    ### Refereeing Stats
    ![image](https://github.com/user-attachments/assets/e184ee2d-4d2f-4014-abf1-e6d1bccc2a7e)


-   **Comprehensive Referee Statistics**: The dashboard showcases the participation and performance of referees, highlighting top referees based on total matches officiated and knockout stage appearances.
-   **Card Analysis Over Time**: It provides trends for yellow and red cards issued over the years, allowing users to observe changes in disciplinary actions throughout different World Cup editions.
-   **Disciplinary Insights Per Match**: Key metrics such as average yellow and red cards per match are displayed, offering a quick understanding of the frequency of bookings in World Cup history.

    ### World Cup Stats

    ![image](https://github.com/user-attachments/assets/19a0959d-b899-42ac-8859-44453d5360e9)


-   **World Cup Historical Overview**: The dashboard presents a high-level summary of World Cup history, including total matches played, the number of participating teams, unique champions, and tournament editions.
-   **Team Achievements Visualized**: It highlights the most successful teams with charts showing the number of championships, runner-up finishes, and final appearances, providing insights into team performance across different tournaments.
-   **Participation Analysis**: The dashboard tracks the total number of matches played by various national teams, helping users understand team consistency and participation over the years.

    ### Attendance Stats

    ![image](https://github.com/user-attachments/assets/6008fc1a-33f9-4705-aa27-cf922dce1931)


-   **Stadium Overview**: The dashboard highlights the top stadiums in terms of matches hosted and finals held, providing insights into the most frequently used venues in World Cup history.
-   **Geographical Distribution**: It includes a map visualization to show the global distribution of matches hosted across different continents, offering a geographical perspective of World Cup events.
-   **Attendance Analysis**: The dashboard tracks average attendance by host country, allowing users to see which nations attracted the most spectators and comparing attendance trends across different World Cups.

    ### Scoring Stats

    ![image](https://github.com/user-attachments/assets/d205b835-961c-4a07-95ad-61f7e522bd58)


-   **Top Scorers Analysis**: The dashboard showcases the top goal scorers in a single World Cup, highlighting legendary players like Just Fontaine, Sándor Kocsis, and Gerd Müller, along with the latest top scorer, Kylian Mbappé.
-   **Team Performance**: It provides an overview of the top-scoring teams in World Cup history, with Brazil, Argentina, and France leading the list, allowing for a comparison of scoring prowess across different nations.
-   **Scoring Trends**: The dashboard tracks the total goals scored over time and identifies the most common scorelines in matches, offering insights into historical trends and patterns in World Cup goal scoring.

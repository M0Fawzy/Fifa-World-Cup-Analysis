**Data Source**

The Data Set Used In The Project: <https://www.kaggle.com/datasets/piterfm/fifa-football-world-cup?select=matches_1930_2022.csv>

**Data Cleaning**

Types Of Data Cleaning Applied:

-   Fixing Typos
-   Splitting Columns
-   Replacing Null Values With (0)
-   Removing Unnecessary Columns
-   Changing Data Types
-   Correcting Stadium And City Names
-   Data Parsing

    Transforming Rows From (['68&rsquor;\|2:0\|Cristian Romero', '71&rsquor;\|3:0\|Nicolás Otamendi']) To The Number Of Yellow Cards Received Using Regex:

    ![](media/ba990de14c180045274e44132b1ec9b9.png)

    **Data Modeling**

    A Star Schema Was Implemented:

    ![](media/77b344b572d0d3c7b75b9e09b31ab14b.png)

    Fact Table: Match

    Dimension Tables: World Cup-Stadium-Teams-Date

    **Dashboards**

    There Was A Total Of Four Dashboards:

    **Refereeing Stats**: ![A screenshot of a computer screen Description automatically generated](media/c1b4d99de90b0070fc170d40ba204c3d.png)

-   **Comprehensive Referee Statistics**: The dashboard showcases the participation and performance of referees, highlighting top referees based on total matches officiated and knockout stage appearances.
-   **Card Analysis Over Time**: It provides trends for yellow and red cards issued over the years, allowing users to observe changes in disciplinary actions throughout different World Cup editions.
-   **Disciplinary Insights Per Match**: Key metrics such as average yellow and red cards per match are displayed, offering a quick understanding of the frequency of bookings in World Cup history.

    **World Cup Stats**:

    ![](media/71032c7e4eb59b64bcaac40b911aa153.png)

-   **World Cup Historical Overview**: The dashboard presents a high-level summary of World Cup history, including total matches played, the number of participating teams, unique champions, and tournament editions.
-   **Team Achievements Visualized**: It highlights the most successful teams with charts showing the number of championships, runner-up finishes, and final appearances, providing insights into team performance across different tournaments.
-   **Participation Analysis**: The dashboard tracks the total number of matches played by various national teams, helping users understand team consistency and participation over the years.

    **Attendance Stats**:

    ![A screenshot of a football match Description automatically generated](media/dcfe1f57aefd887dca331d7938d75f78.png)

-   **Stadium Overview**: The dashboard highlights the top stadiums in terms of matches hosted and finals held, providing insights into the most frequently used venues in World Cup history.
-   **Geographical Distribution**: It includes a map visualization to show the global distribution of matches hosted across different continents, offering a geographical perspective of World Cup events.
-   **Attendance Analysis**: The dashboard tracks average attendance by host country, allowing users to see which nations attracted the most spectators and comparing attendance trends across different World Cups.

    **Scoring Stats:**

    **![A screenshot of a computer screen Description automatically generated](media/f91200557c2ac418a9a42481d2ea8083.png)**

-   **Top Scorers Analysis**: The dashboard showcases the top goal scorers in a single World Cup, highlighting legendary players like Just Fontaine, Sándor Kocsis, and Gerd Müller, along with the latest top scorer, Kylian Mbappé.
-   **Team Performance**: It provides an overview of the top-scoring teams in World Cup history, with Brazil, Argentina, and France leading the list, allowing for a comparison of scoring prowess across different nations.
-   **Scoring Trends**: The dashboard tracks the total goals scored over time and identifies the most common scorelines in matches, offering insights into historical trends and patterns in World Cup goal scoring.

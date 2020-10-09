|**This is EDA project based on ISL Data 2014-2017 season**   |[![ISL](https://github.com/pathakchiranjit1988/EDA_Projects_INSAID_June2020_batch/blob/master/ISL_pics.jpg?raw=true "ISL")](https://github.com/pathakchiranjit1988/EDA_Projects_INSAID_June2020_batch/blob/master/ISL_pics.jpg?raw=true "ISL")   |
| :------------: | :------------: |
| **Data Source:**  |  https://data.world/ajaigovindg/hero-indian-super-league |
| **EDA with Pandas profiling will be very much helpful as one line code is sufficient and here is a graphical representation of the same. The use of describe(), info() has also been depicted here.**  | [![ISL2](https://github.com/pathakchiranjit/EDA_Projects_INSAID_June2020_batch/blob/master/EDA_snaps.JPG?raw=true "ISL2")](https://github.com/pathakchiranjit/EDA_Projects_INSAID_June2020_batch/blob/master/EDA_snaps.JPG?raw=true "ISL2")  |

## Table of Contents

1. [Objective: Problem Statement](#section1)<br>
2. [Tools: Importing Packages](#section2)<br>
3. [Collecting & Loading Data](#section3)<br>
  - 3.1 [Importing Data sets & Description](#section301)<br>
  - 3.2 [Pandas Profiling before Data Preprocessing](#section302)<br>
4. [Data Preprocessing](#section4)<br>
  - 4.1 [Data Preprocessing](#section401)<br>
  - 4.2 [Pandas Profiling after Data Preprocessing](#section402)<br>
5. [Exploratory Data Analysis](#section5)<br>
  - 5.1 [**Identification of challanges:**](#section501)<br>
    - 5.1.1 [How the Matches Distributed across all the seasons?](#section50101)<br>
    - 5.1.2 [How the no of Matches played season wise?](#section50102)<br>
    - 5.1.3 [How the Attendance distributed ?](#section50103)<br>
    - 5.1.4 [What is the mean Attendance season wise?](#section50104)<br>
    - 5.1.5 [How the percentage of Attendance w.r.t. total stadium capacities distributed?](#section50105)<br>
    - 5.1.6 [How the percentage of Attendance varies season wise ?](#section50106)<br><br>
  - 5.2 [**Analysis w.r.t the Quality Of Games:**](#section502)<br>
      - 5.2.1 [How the Home team winning varies across seasons?](#section50201)<br>
      - 5.2.2 [How the match results favoring respective teams?](#section50202)<br>
      - 5.2.3 [How the match deciding moments are distributed?](#section50203)<br>
      - 5.2.4 [How the goals are distributed?](#section50204)<br>
      - 5.2.5 [What is the Team wise performances?](#section50205)<br> 
      - 5.2.6 [How the Goal difference occures throughout the seasons?](#section50206)<br> 
      - 5.2.7 [How does the attendance influnece the Goal difference, Total goals? influenced?](#section50207)<br>
      - 5.2.8 [Which teams became champion during all the seasons?](#section50208)<br>
      - 5.2.9 [How Teams were performed across all seasons?](#section50209)<br>
      - 5.2.10 [How does the total goals, goal differences, match days and attendance are correlated ?](#section50210)<br>
      - 5.2.11 [How does all the team stretegise their games?](#section50211)<br> <br>
  - 5.3 [**Analysis w.r.t the Quality Of Players:**](#section503)<br>
      - 5.3.1 [How does the Player's anthropometry distributed?](#section50301)<br>
      - 5.3.2 [What is the overall combination of players across different positions?](#section50302)<br>
      - 5.3.3 [What is the overall combination of players across different positions in each seasons?](#section50303)<br>
      - 5.3.4 [Whether players are getting replaced in each season?](#section50304)<br>
      - 5.3.5 [How player's physics/strength are mapped in each season?](#section50305)<br><br>
  - 5.4 [**Analysis w.r.t the Infrastructural & Organizational aspects:**](#section504)<br>
      - 5.4.1 [How does the stadiums and referees are being utilized for the games?](#section50401)<br>
      - 5.4.2 [How does the attendance varies across all stadiums?](#section50402)<br>
      - 5.4.3 [How does the team performances distributed across all stadiums?](#section50403)<br><br>
  - 5.5 [**Analysis w.r.t the Stretegical & Geographical/Regional aspects:**](#section505)<br>
      - 5.5.1 [How does the weekdays/weekend games are influencing the popularity?](#section50501)<br>
      - 5.5.2 [How does the regional/geographical factors are influencing the popularity?](#section50502)<br>
      - 5.5.3 [Summary: Correlation among all the columns](#section50503)<br><br> 
6. [Conclusion](#section6)
  - 6.1 [Actionable Insights](#section601)
  - 6.2 [Limitation of this study](#section602)

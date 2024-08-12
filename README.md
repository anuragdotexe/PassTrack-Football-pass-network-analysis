# Champions League Final 2019: Passing Network Analysis using Network Science

## Scope 
In this project, a comprehensive analysis of the **UEFA Champions League Final 2019** game is performed. The **passing network** of both teams is created and studied. Meaningful insights are extracted by applying **network science techniques** on the passing networks of both teams.

The analysis performed **aims to answer the following questionsI** regarding the game: 

- Who is the most valuable player in terms of ball circulation for each team?
- Which tactical plan was followed by each team, and how was it respectively countered by the opponent?
- Which are the "subgroups" of players of each temam who frequently interact during the game?
- Who was the team-player and the individual during the game?
- What alternative tactics could be followed?
- Ultimately, is ball possession a significant factor in winning a football game?

The **full report** of the analysis can be found [here](/2019%20Champions%20League%20Final.pdf).

## Dataset

The dataset utilized for this analysis was sourced from StatsBomb's Open Data platform, a reputable and comprehensive resource for football-related statistics. More specifically, StatsBomb, one of the leading companies in the collection and analysis of data from sports events, freely provides statistics for passes, interceptions, and crosses for a total of 4 Champions League finals in its GitHub repository [statsbomb/open-data](https://github.com/statsbomb/open-data).

## Passing Network Visualization

Matplotlib, in conjunction with [mpsoccer](https://github.com/andrewRowlinson/mplsoccer), was employed for visualizing the passing networks. The latter is a comprehensive library specifically designed for visualizing soccer teams on the pitch, offering a holistic approach to football data visualization. The code which generates the passing networks can be found in the [`generateCharts.py`](/Code/generateCharts.py) file. 

<br>

![2019 UCL Final Passing Network](/Output/Passing%20Network.png)

## Network Science Metrics 

The network analysis part of the project was performed using Gephi, an open-source network analysis software package.
Insights were extracted from the passing networks by applying popular network science metrics : 

- Weighted Degree
- Weighted In-Degree
- Weighted Out-Degree
- Closeness Centrality
- Betweenness Centrality
- Eigen Centrality
- PageRank
- Node Clustering Coefficient
- Modularity
- Bridging Centrality
- Bridging Coefficient


## Sample Passing Networks 

![Passing Network : Weighted Degree](/Output/Weighted%20Degree.png)

<br>

![Passing Network : Modularity](/Output/Modularity.png)

## Author 

- [Dimitris Bouris](https://github.com/dbouris)
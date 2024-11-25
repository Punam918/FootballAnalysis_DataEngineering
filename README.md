
# Football Data Engineering
This Python-based project extracts data from Wikipedia using Apache Airflow, cleans it and pushes it Azure Data Lake for processing and further processing and visualization is done on Azure Data Factory, Azure Synapse and Tableau.

# Requirements
- Python 3.10
- Docker
- MySql
- Azure
- Apache Airflow 2.6

# System Architecture

![Alt text](https://raw.githubusercontent.com/punam42/FootballAnalysis_DataEngineering/refs/heads/master/FootballProject_Image/system_architecture.png)

# Fetching And Processing Data
Football Data based on stadium by capacity was fetched from wikipedia page https://en.wikipedia.org/wiki/List_of_association_football_stadiums_by_capacity using Apache Airflow and the fetched data was trasnformed and stored in Azure Data Lake and further queried using Synapse.
![Alt text](https://raw.githubusercontent.com/punam42/FootballAnalysis_DataEngineering/refs/heads/master/FootballProject_Image/Synapse_Chart_Germany.jpg)




# Visualization
For visualizing data, Tableau was used
![Alt text](https://raw.githubusercontent.com/punam42/FootballAnalysis_DataEngineering/refs/heads/master/FootballProject_Image/Stadium_Region_Tableau.jpg)

![Alt text](https://raw.githubusercontent.com/punam42/FootballAnalysis_DataEngineering/refs/heads/master/FootballProject_Image/Top10_Stadium_By_Capacity.jpg)


![Alt text](https://raw.githubusercontent.com/punam42/FootballAnalysis_DataEngineering/refs/heads/master/FootballProject_Image/Geographical_Distribution_By_Stadium.jpg)




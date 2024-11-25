
# Football Data Engineering
This project leverages Python and Apache Airflow to extract data from Wikipedia. The extracted data is cleaned and stored in Azure Data Lake for further processing. Subsequent data transformation and analysis are performed using Azure Data Factory and Azure Synapse Analytics. Finally, the processed data is visualized using Tableau, enabling actionable insights and decision-making.

# Requirements
- Python 3.10
- Docker
- MySql
- Azure
- Apache Airflow 2.6

# System Architecture

![Alt text](https://raw.githubusercontent.com/Punam918/FootballAnalysis_DataEngineering/refs/heads/master/FootballProject_Image/system_architecture.png)

# Fetching And Processing Data
Football Data based on stadium by capacity was fetched from wikipedia page https://en.wikipedia.org/wiki/List_of_association_football_stadiums_by_capacity using Apache Airflow and the fetched data was trasnformed and stored in Azure Data Lake and further queried using Synapse.
![Alt text](https://raw.githubusercontent.com/Punam918/FootballAnalysis_DataEngineering/refs/heads/master/FootballProject_Image/Synapse_Chart_Germany.jpg)




# Visualization
For visualizing data, Tableau was used
![Alt text](https://raw.githubusercontent.com/Punam918/FootballAnalysis_DataEngineering/refs/heads/master/FootballProject_Image/Stadium_Region_Tableau.jpg)

![Alt text](https://raw.githubusercontent.com/Punam918/FootballAnalysis_DataEngineering/refs/heads/master/FootballProject_Image/Top10_Stadium_By_Capacity.jpg)


![Alt text](https://raw.githubusercontent.com/Punam918/FootballAnalysis_DataEngineering/refs/heads/master/FootballProject_Image/Geographical_Distribution_By_Stadium.jpg)




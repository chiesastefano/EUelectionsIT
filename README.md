# Relationship between Turnout and Votes for PRO-EU Parties in Italy
**Author:** [Stefano Chiesa](https://www.linkedin.com/in/stefano-chiesa-8a0502184/)


Is there a relationship between the turnout of the European Parliament elections in Italy and the percentage of votes received by pro-EU parties? In this project, I will analyze the data from the European Parliament elections in Italy to answer this question. 

I performed the following steps:
- Load and inspect the data;
- Calculate the correlation between the turnout and the votes for pro-EU parties;
- Create a scatter plot to visualize the relationship between turnout and votes for pro-EU parties.


**Data Sources:**
- Europa Elections: https://results.elections.europa.eu/en/tools/download-datasheets/
- BiDiMedia: https://www.youtube.com/watch?v=WGWWdETT0Kk


## Guide to the files
In the repository you can find the following files and directories:
- **EUelectionsIT.ipynb**: Jupyter Notebook presentation of the analyses; 
- *data/*: containing all the Italian election data;
- *data/all_data.xlsx*: excel file with the information about the Italian parties' results per each year.
  You can find the csv version [here](https://www.kaggle.com/datasets/ilchurch/european-parliament-elections-1979-2019-italy);
- *data/turnout.xlsx*: excel file with the turnout data per each year. You can find the csv version [here](https://www.kaggle.com/datasets/ilchurch/european-parliament-elections-turnout-italy);
- *requirements.txt*: a text file containing the packages used in the code.

## Methodology Note
The parties are classified through the binary column "PRO_EU", indicating whether the party is pro-EU (1) or not (0). 
This value is assigned based on my knowledge of Italian politics and internet research. When I wasn't sure about the classification, I assigned a value of NA.
Someone might disagree with my classification, feel free to contact me if you have any suggestions.


## Limits of the Analysis
The analysis has some limitations:
- The classification of parties as pro-EU or not is subjective and based on my knowledge of Italian politics and internet research. There might be disagreements about the classification of some parties;
- The data only includes the European Parliament elections in Italy, and the relationship between voter turnout and votes for pro-EU parties might differ in other elections or countries.

Don't hesitate to contact me if you have any suggestions or questions.



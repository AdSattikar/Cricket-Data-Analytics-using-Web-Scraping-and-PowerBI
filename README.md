# Women's Premier League Dream 11 Predictor

This is a project to predict the best playing 11 for the recently concluded Womens Premier League (WPL) 2023 cricket tournament.
![WPL Dream 11](https://github.com/AdSattikar/WPL-Dream-Team-Prediction/assets/78402053/dd6b0fba-027d-4842-92d9-40638f1dd76e)

## Data Collection

The data is collected using BeautifulSoup (bs4) to scrape data from [ESPNCricinfo](https://www.espncricinfo.com/records/tournament/team-match-results/women-s-premier-league-2022-23-15174) for match details, batter details, bowler details, and player details, and images from [WPL](https://www.wplt20.com/teams). The data is collected in the form of a dictionary and then converted to JSON. The JSON files are then loaded into the Data Preprocessing.ipynb file, where data preprocessing is performed using pandas, and respective dataframes are created. The dataframes are then converted to CSV files that are loaded into Power Query and DAX for data modeling.

### ESPNCricinfo Data Collection:
- The project utilizes BeautifulSoup (bs4) to scrape data from the ESPNCricinfo website.
- Specifically, data is scraped from the [Women's Premier League 2022-23](https://www.espncricinfo.com/records/tournament/team-match-results/women-s-premier-league-2022-23-15174) tournament page.
- Match details, batter details, bowler details, and player details are extracted from the HTML structure of the webpage.
- The collected data is structured in the form of a dictionary, where each entry represents a specific match, batter, bowler, or player.
- The dictionary is then converted to JSON for easier handling and storage.

### WPL Website Data Collection:
- Player details and images are collected from the official WPL website located at [wplt20.com/teams](https://www.wplt20.com/teams).
- BeautifulSoup is used to extract relevant information such as player names, teams, and images from the webpages.
- The collected data is added to the existing dictionary in JSON format.

### Data Preprocessing:
- The JSON data is loaded into the Data Preprocessing.ipynb file for further processing.
- Pandas is utilized for data preprocessing tasks.
- The JSON data is loaded into pandas dataframes, enabling easy manipulation and analysis.
- Data cleaning operations are performed to handle missing or inconsistent values, ensuring the data is in a suitable format for analysis.
- Additional data transformations may be applied, such as converting categorical variables into numerical representations.

### Data Modeling:
- The preprocessed dataframes are converted to CSV files for further modeling.
- Power Query is used for data transformation, merging, and filtering, to create refined datasets.
- DAX (Data Analysis Expressions) is employed in Power BI to perform advanced calculations, define relationships between tables, and create measures and calculations for the desired predictive models.

By following this data collection, preprocessing, and modeling pipeline, the Women's Premier League Dream 11 Predictor project ensures that the collected data is transformed into a suitable format for analysis and prediction. This empowers users to make informed decisions while selecting their dream teams for the WPL.

## Download Dataset
[Womens Premier League 2023 (WPL) Dataset by Adnan Sattikar](https://www.kaggle.com/datasets/adnansattikar/womenspremierleague2023)

## Technologies Used

- Python 3
- BeautifulSoup (bs4)
- Pandas
- NumPy
- Data Modeling 
- Power Query
- DAX
- Power BI

## Methodology

- Data collection and cleaning
- Exploratory data analysis
- Feature engineering
- Model selection and training
- Model evaluation and validation

## Dashboard

### Player Performance Evaluation: 
- I have conducted comprehensive analyses of individual player performances throughout the tournament, evaluating batting averages, strike rates, bowling economy, wicket-taking abilities, and fielding efficiencies. These insights help teams identify standout performers, identify areas for improvement, and make informed decisions when it comes to team selection and player roles.

### Team Strategy Optimization: 
- By analyzing team performance metrics, such as run rates, partnerships, bowling variations, and fielding strategies, I have identified winning patterns and strategies employed by successful teams in the WPL 2023. Teams can leverage these insights to optimize their game plans, devise effective batting and bowling strategies, and enhance their chances of success in future tournaments.

### Data Visualization for Enhanced Understanding: 
- I have employed visually appealing and intuitive dashboards to present complex cricket analytics in a user-friendly manner. These interactive visualizations enable coaches, players, and analysts to grasp key trends and performance patterns at a glance, facilitating data-driven decision-making processes and enhancing communication within the team.


The final outcome of this project is the formation of a combined team of 11 players from across all teams participating in the Women's Premier League (WPL). The selection of these players is based on the valuable insights derived from the Power BI dashboard visualizations. By considering various performance metrics and patterns observed in the tournament, this combined team represents a culmination of data-driven decision-making processes to create a strong and competitive lineup. This selection helps showcase the potential impact of analytics and visualization in forming a formidable team in women's cricket.

### By focusing specifically on the Womens Premier League (WPL), my project aims to contribute to the growth and development of women's cricket. The insights derived from this project can help teams, cricket boards, and stakeholders in the women's cricket ecosystem to harness the power of data and drive positive changes in the sport.

## Contributors

- [Adnan Sattikar](https://github.com/AdSattikar)

## License

This project is licensed under the [GNU General Public License v3.0](https://github.com/AdSattikar/WPL-Dream-Team-Prediction/blob/master/LICENSE). 

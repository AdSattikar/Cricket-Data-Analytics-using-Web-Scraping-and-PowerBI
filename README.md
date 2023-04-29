# Women's Premier League Dream 11 Predictor

This is a project to predict the best playing 11 for the recently concluded Womens Premier League (WPL) 2023 cricket tournament.

## Data Collection

The data is collected using BeautifulSoup (bs4) to scrape data from [ESPNCricinfo](espncricinfo.com) for match details, batter details, bowler details, and player details and images from [WPL](wplt20.com). The data is collected in the form of a dictionary and then converted to JSON. The JSON files are then loaded into the Data Preprocessing.ipynb file, where data preprocessing is performed using pandas, and respective dataframes are created. The dataframes are then converted to CSV files that are loaded into Power Query and DAX for data modeling.

## Technologies Used

- Python 3
- BeautifulSoup (bs4)
- Pandas
- NumPy
- Matplotlib
- IPLT20.com
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

The dashboard is built using Power BI visualization to provide interactive and insightful visualizations for the predicted best playing 11 for the Women's Premier League cricket tournament.

## Contributors

- [Adnan Sattikar](https://github.com/AdSattikar)

## License

This project is licensed under the [GNU General Public License v3.0](https://github.com/AdSattikar/WPL-Dream-Team-Prediction/blob/master/LICENSE). 

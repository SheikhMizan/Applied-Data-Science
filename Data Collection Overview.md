    Collecting Data with an API: Utilizing the SpaceX REST API to gather past launch data, including information about rockets, payloads, launch and landing specifications, and outcomes.

    Data Wrangling: Normalizing the JSON data obtained from the API into a structured DataFrame. Additionally, utilizing web scraping techniques with BeautifulSoup to extract Falcon 9 launch records from HTML tables, parsing and converting them into a Pandas DataFrame.

    Data Cleaning: Filtering out Falcon 1 launches from the dataset, dealing with NULL values in the PayloadMass column by calculating the mean of non-null values and replacing NULLs with this mean.

    Data Analysis Preparation: Ensuring the dataset is cleaned and prepared for further analysis by addressing NULL values and preparing for one-hot encoding for the LandingPad column.

    Prediction Objective: The ultimate goal is to use this cleaned dataset to predict whether SpaceX will attempt to land a rocket or not, utilizing various machine learning techniques.

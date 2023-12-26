# <Your Project Name>

## Overview
This Jupyter Notebook project performs web scraping on Amazon's T-shirt section, extracting product titles, prices, and ratings. The data is then loaded into a Pandas DataFrame, filtered, and sorted based on ratings. Additionally, the information is stored in a local PostgreSQL database.

## Project Structure

- **`main.ipynb`**: The main Jupyter Notebook containing the web scraping script, data manipulation, and database loading operations.
- **`requirements.txt`**: Lists the required Python packages for this project.
- **`README.md`**: Provides an overview of the project, including instructions on how to use the web scraper and load data into a local database.

## How to Use
1. Open the `main.ipynb` Jupyter Notebook.
2. Execute the cells in the notebook one by one.
   - The web scraping script extracts product titles, prices, and ratings.
   - The Pandas DataFrame is displayed, showing the details of the scraped T-shirts.
   - Data is loaded into a local PostgreSQL database. Ensure to modify the connection details in the notebook accordingly.

3. Confirm data loading in the database.
   - Query the PostgreSQL database to ensure that the scraped T-shirt data has been successfully loaded.

## Important Notes
- This project uses Python, BeautifulSoup, Pandas, and psycopg2.
- Ensure you have the required libraries installed before running the notebook.
- Adjust the user-agent in the web scraping script if needed for web scraping.

Feel free to contribute, report issues, or suggest improvements!

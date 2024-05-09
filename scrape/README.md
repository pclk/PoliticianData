# Wikipedia Scraper

This project contains a Jupyter notebook (`wiki_scrape.ipynb`) that scrapes data from Wikipedia about Singaporean politicians. The scraped data is then processed and stored in a JSON file (`singapore.json`).

## Functionality

The `wiki_scrape.ipynb` notebook performs the following steps:

1. Retrieves a list of Singaporean politicians from Wikidata using a SPARQL query.
2. Iterates over each politician and extracts relevant information such as name, image URL, alternate names, gender, email, birth date, death date, description, and positions held.
3. Stores the extracted data in a dictionary format.
4. Saves the scraped data as a JSON file named `singapore.json`.
5. Loads the JSON file and creates a Pandas DataFrame to display the scraped data.

## Data Structure

The scraped data is stored in the `singapore.json` file with the following structure:


## Dependencies

The notebook requires the following dependencies:

- Python 3.x
- Jupyter Notebook
- Pandas
- Requests

Make sure to have these dependencies installed before running the notebook.

## Usage

1. Clone the repository or download the `wiki_scrape.ipynb` notebook and `singapore.json` file.
2. Open the `wiki_scrape.ipynb` notebook in Jupyter Notebook or JupyterLab.
3. Run the notebook cells in sequential order to execute the scraping process and generate the JSON file.
4. The scraped data will be displayed as a Pandas DataFrame at the end of the notebook.
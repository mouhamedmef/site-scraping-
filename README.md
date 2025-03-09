## Scraping Football Tunisian Federation Site

I have successfully scraped the data from the Tunisian Football Federation site: [Calendrier et résultats Ligue 1](https://www.ftf.org.tn/fr/calendrier-et-resultats-ligue-1/?journee=1&season=2024-2025). 

![This is the site](ftf.png)

### Data Extracted

The following information has been extracted:

- **Match Rounds**: The rounds of matches played in the current season.
- **Clubs**: The names of the clubs participating in the matches.
- **Match Scores**: The scores for each match played.

### Example of Scraped Data

Here's a brief overview of the data structure:
![This is the exemple](result.png)

### Usage

You can use this data for analysis, visualization, or to keep track of the league's progress. The scraping script is designed to run periodically to keep the data updated.

### Requirements

Make sure you have the following installed:

- Python 3.x
- Important Libraries:
  - **Requests**: For making HTTP requests.
  - **BeautifulSoup4**: For parsing HTML and XML documents.
  - **lxml**: For fast parsing of XML and HTML.
  - **Workbook**: For handling spreadsheet operations.

To install the required libraries, run the following commands in your terminal:

```bash
pip install python
pip install requests
pip install beautifulsoup4
pip install lxml
pip install workbook

# Web_Scraper_App_gpt-4o_Firecrawl
This project is a web scraper application built using the Firecrawl API and OpenAI's GPT-4o. The original code was created by Reda Marzouk, and this app extends its functionality by increasing the data extraction limit. The app scrapes data from specified URLs, formats it into structured JSON, and saves both the raw and formatted data to disk. For demonstration purposes, the app has been tested on the CoinMarketCap website to extract important fields.

## Features
Scrape data from specified URLs using the Firecrawl API.
Extract and format structured information using OpenAI's GPT-4o.
Save raw and formatted data in Markdown, JSON, and Excel formats.
Extract important fields such as Name, Price, Market Cap, and more from websites like CoinMarketCap.


## Installation
Clone the repository:
git clone `arad1367/Web_Scraper_App_gpt-4o_Firecrawl.git`

- Install the required packages
pip install -r requirements.txt
- Set up environment variables:
Create a .env file in the root directory of the project and add your API keys:

FIRECRAWL_API_KEY=your_firecrawl_api_key
OPENAI_API_KEY=your_openai_api_key


## Usage
Modify the URL to scrape in the main block of the script:
url = 'https://coinmarketcap.com/'
Run the script:

`python app.py`
The scraped raw data will be saved in the output folder as rawData_<timestamp>.md, and the formatted data will be saved as sorted_data_<timestamp>.json and sorted_data_<timestamp>.xlsx.

## Dependencies
firecrawl
openai
python-dotenv
pandas
Credits
Original code by `Reda Marzouk`. This app enhances the functionality by increasing the data extraction limit and integrating OpenAI's `GPT-4o` for better data formatting.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
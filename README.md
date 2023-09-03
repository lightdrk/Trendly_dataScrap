# Trendly_dataScrap
scraps from trenldly for data .


![Screenshot_2023-09-03_08-03-47](https://github.com/lightdrk/Trendly_dataScrap/assets/108566237/25344a3f-a95c-4a55-8cea-0be13f648c6e)


# Stock Data Scraper with Web Navigation

## Overview
This Node.js script is designed to scrape stock data from a financial website. It utilizes Puppeteer for web scraping, CSV handling for data storage, and the CLI progress bar for tracking scraping progress.

## Requirements
Before running the script, ensure you have the following prerequisites installed:
- Node.js
- npm (Node Package Manager)

## Installation
1. Clone or download this repository to your local machine.
2. Open your terminal or command prompt and navigate to the project directory.
3. Install the required dependencies by executing the following command:



## Usage
1. Customize the script to match your requirements by modifying the email, password, and stock list filename variables at the beginning of the script:
- `Email`: Your login email for the financial website.
- `Pass`: Your password for the financial website.
- `stock_file`: The name of the text file containing the list of stocks you intend to scrape.

2. Execute the script using the following command:



Replace `your-script-name.js` with the actual filename of your script.

3. The script will launch a headless Chromium browser, navigate to the financial website, and log in using the provided email and password.

4. It will read the list of stocks from the specified text file and commence the data scraping process for each stock.

5. Keep an eye on the progress bar, which tracks the scraping progress.

6. The scraped data, including stock details, will be saved in a CSV file named `data.csv` in the project directory.

7. Upon completion of scraping all the stocks, the script will display a confirmation message.

## Additional Notes
- This script serves as a basic example and may require adjustments based on the specific structure of the financial website you intend to scrape.

- Ensure a stable internet connection while running the script since it relies on web navigation.

- The `cli-progress` package is used to create the progress bar for monitoring the scraping progress. You can customize the appearance of the progress bar within the script.

- Always consider the legality and ethical aspects of web scraping. Respect the terms of use and policies of the website you are scraping.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for detailed licensing information.

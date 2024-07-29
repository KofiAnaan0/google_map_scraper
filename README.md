# Google Map Scraper for Hotels & Apartments in Tulum, Mexico.

## Overview.

This project scrape a specified number of apartments & hotels in Tulum, Mexico from Google Maps using playwright. The scraped data include name, address, phone number & website if any, the review count and the average review.

## Features.

- **Automated Scraping:** Uses playwight to automate scraping of hotels & apartments from Google Maps.
- **Data Storage**: Creates a folder in the working directory & saves the scraped data in csv & xlsx file using pandas & openpyxl
- **Configuration search and Limit:** Allows users to configure search term & the limit on the results.

### Prerequisites

- Python 3.x
- [Visual Studio Code (VS Code)](https://code.visualstudio.com/)

### Setup

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd google-map-scraper-tulum
   ```
2. **Create a virtual environment (optional but recommended):**

- python -m venv venv

3. **Activate the virtual environment on Windows:**

- .\venv\Scripts\activate

4. **Install the dependencies:**

- pip install -r requirements.txt

### Usage

**To scrape data, run the following command:**

- python main.py -s="Apartments & Hotels in Tulum, Mexico" -t=100

### Arguments

**-s:** The search term used to find hotels and apartments in Tulum.
**-t:** The maximum number of results to scrape.

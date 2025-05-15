# WTJ Scraper

A Python-based web scraper for extracting company information from Welcome to the Jungle (WTJ).

## Description

This scraper automates the collection of company profiles from Welcome to the Jungle, including:
- Company names and locations
- Official websites and social media links
- Industry sectors
- Company descriptions and presentations
- Recruitment information
- Additional company insights

## Installation

1. Clone the repository:
```bash
git clone https://github.com/zaidkx7/WTJ_Scrapper.git
cd WTJ_Scrapper
```

2. Create Virtual Environment
```bash
python -m venv .venv
.venv\Scripts\activate
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Simply run the main script:
```bash
python main.py
```

The scraper will:
1. Fetch company data from WTJ
2. Save the results in two formats:
   - JSON file (`response/data.json`)
   - Excel file (`response/companies_info.xlsx`)

## Output

The scraper generates two types of output files in the `response` directory:

1. `data.json`: Contains all scraped data in JSON format
2. `companies_info.xlsx`: An Excel file with formatted columns containing:
   - Company name
   - Location
   - Website
   - URL
   - Sectors
   - Social media links
   - Description
   - Presentation
   - Recruitment information
   - Additional insights

## Dependencies

- beautifulsoup4
- openpyxl
- requests

## Note

This scraper is for educational purposes only. Please ensure you comply with WTJ's terms of service and robots.txt when using this tool.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 

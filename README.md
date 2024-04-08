# Project Description

## Purpose
The goal of this project is to develop a web scraping tool using Selenium to extract data from the Charities Bureau Website, specifically focusing on parsing a table containing information about charitable organizations operating in New York State. The extracted data will then be stored in a CSV file and uploaded to an S3 bucket on AWS.

## Aim
The primary objective of this project is to create a reliable and efficient web scraping script using Selenium, which can iteratively extract data from multiple pages of the website and compile it into a single CSV file. Additionally, the project aims to demonstrate the integration of Selenium with AWS services, particularly S3, for storing the extracted data securely and efficiently.

## Dependencies
- **Python Packages:**
  - `awscli`: Command-line interface for AWS services.
  - `boto3`: AWS SDK for Python, used for interacting with AWS services programmatically.
  - `pandas`: Data manipulation and analysis library in Python.
  - `selenium`: Web scraping library for automating web browsers.

- **Additional Software:**
  - **Google Chrome**: Web browser required for Selenium web scraping.
  - **Chrome WebDriver**: WebDriver executable for Google Chrome, necessary for Selenium to control the browser programmatically.

By leveraging these dependencies, the project aims to streamline the process of web scraping and data extraction from the Charities Bureau Website, ultimately facilitating the analysis of charitable organizations in New York State.


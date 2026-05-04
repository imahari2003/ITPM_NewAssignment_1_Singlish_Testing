# Singlish Transliteration Accuracy Testing

## How to install dependencies
- Install Python 3.11 or 3.12
- Run the following command to install required libraries:
  `pip install playwright openpyxl`
- Install Playwright browsers:
  `playwright install`

## How to run the tests
- Open terminal in the project folder and run:
  `python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 8000 --type-delay-ms 100 --slow-mo-ms 300 --save-every 1 --keep-open`

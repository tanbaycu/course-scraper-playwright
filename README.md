# Course Scraper with Playwright - @T7C 

This project uses Playwright to automate the extraction of online course from Udemy information from a specified website. It includes features for handling pagination, filtering courses, and exporting data to Word and PDF formats.


Websites used: [real.discount](https://www.real.discount/)
## Features

- Automatically clicks "Load More" to load additional courses.
- Filters out courses based on specific criteria.
- Extracts course names and Udemy coupon links.
- Exports course data to Word and PDF formats when a certain number of courses are reached (20, 40, 60).

## Requirements

- Python 3.x
- Playwright
- python-docx
- reportlab

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tanbaycu/course-scraper-playwright.git
   ```
2. Navigate to the project directory:
   ```
   cd course-scraper-playwright
   ```
3. Install the required packages:
   ```
   pip install playwright python-docx reportlab
   playwright install
   ```
## Usage
Run the script to start scraping courses:
```
python freeudemytool.py
```
The script will process the courses and export data to Word and PDF files when the number of courses reaches 20, 40, or 60. free


## Contact

| Type    | Detail                     |
|---------|----------------------------|
| Name    | Tan 7 Cu                   |
| Email   | [tranminhtan4953@gmail.com](mailto:[tranminhtan4953@gmail.com) |
| Telegram| [TRAN MINH TAN](t.me/tanbaycu)                 |
| Facebook| [Tran Minh Tan](https://facebook.com/tanbaycu) |





# Business Quant Table Extraction - Shivam Navik

This project extracts data from HTML tables and saves it to a CSV file.

## How to Run

1.  **Put HTML files:** Place your HTML files (like `table_12.html`, `table_62.html`, `table_9.html`) in the same folder as `table_extractor.py`.
2.  **Run the script:** Open a terminal in that folder and run: `python table_extractor.py`
3.  **Get the data:** The extracted data will be in `output.csv`.

## What it does

The Python script `table_extractor.py` reads the HTML files, finds the tables, and extracts the data. It handles different table layouts and combines all the data into one CSV file.  The CSV file has these columns:

*   `file_name`: Which HTML file the data came from.
*   `label`:  The first column of the table.
*   `table_title`: The table's title (if it has one).
*   `column_header`: The name of the column.
*   `value`: The data itself.

## Requirements

You need Python 3 and these libraries:

*   `BeautifulSoup4`:  `pip install beautifulsoup4`
*   `pandas`: `pip install pandas`

## Video

I've included a video explaining the code.

## Author

Shivam Navik (Jabalpur Engineering College)
(Your Email Address)
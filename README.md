# Sales Summary Web App

This is a single-page web application that fetches sales data from a `data.csv` file, calculates the total sales, and displays it on the page.  It uses Bootstrap 5 for styling and loads it from jsdelivr.

## Features

*   Fetches data from `data.csv`.
*   Calculates the sum of the sales column.
*   Sets the title to "Sales Summary 600".
*   Displays the total sales in the `#total-sales` element.
*   Uses Bootstrap 5 for styling.

##  Checks

The application includes JavaScript checks to ensure:

*   The document title is "Sales Summary 600".
*   Bootstrap is loaded correctly (link tag exists).
*   The total sales displayed equals 600 (within a tolerance of 0.01).

## Setup & Running

1.  **Save the files:** Create `index.html`,  `data.csv`, and a `LICENSE` file in the same directory.
2.  **data.csv:** Create a  `data.csv` file with the following content.
```csv
Item,Sales
ProductA,100
ProductB,200
ProductC,300
```
3.  **Open in Browser:** Open `index.html` in your web browser.

##  Files

*   `index.html`: The main HTML file containing the structure, styling, and JavaScript logic.
*   `data.csv`:  A CSV file containing sample sales data.
*   `LICENSE`: The MIT license.

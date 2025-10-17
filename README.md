# Sales Summary Dashboard

This project provides a simple, single-page web application to display a summary of sales data fetched from a local `data.csv` file. The application is built with vanilla JavaScript for data processing and uses Tailwind CSS for a modern, responsive user interface.

## Features

*   Fetches `data.csv` to process sales figures.
*   Calculates the total sum of the 'sales' column.
*   Displays the total sales in a clear, easy-to-read format.
*   Responsive design powered by Tailwind CSS.
*   Dynamically sets the page title.

## Setup and Usage

To run this application:

1.  **Ensure `data.csv` is Present:** Make sure the `data.csv` file is located in the same directory as `index.html`.
2.  **Open `index.html`:** Simply open the `index.html` file in your web browser.

The application will automatically load `data.csv`, calculate the total sales, and display it on the page.

## File Structure

*   `index.html`: The main single-page application.
*   `data.csv`: The comma-separated values file containing sales data. (Required for the application to function)
*   `README.md`: This README file.
*   `LICENSE`: The MIT License for this project.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **CSS (Tailwind CSS CDN):** Styling and responsive design.
*   **JavaScript:** Data fetching, parsing, and dynamic content updates.

## Data Format

The `data.csv` file is expected to have a header row, and at least one column named `sales`. The `sales` column should contain numerical values.

Example `data.csv`:
```csv
id,product,sales
1,Laptop,1200.50
2,Mouse,25.00
3,Keyboard,75.25
4,Monitor,300.75
```
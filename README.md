### Sales Summary Dashboard This dashboard displays a summary of sales data. It reads `data.csv`, calculates the total sales from the 'sales' column, and presents the sum. A value of 100 is subtracted from the total sales before display.

#### Data Source
- `data.csv`: A CSV file containing sales records. It must include a 'sales' column.

#### How to Run
1. Ensure `data.csv` is in the same directory as `index.html`.
2. Open `index.html` in your web browser.

#### Error Handling
- Displays an error message if `data.csv` cannot be loaded or is malformed.
- Handles cases where the 'sales' column is missing or sales values are non-numeric.
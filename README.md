# Sales Summary Application

This is a simple, single-page web application designed to fetch sales data from a `data.csv` file, calculate the total sales, and display it prominently on a responsive user interface. The application dynamically updates its title and content based on the fetched data.

## Features

*   **Dynamic Data Fetching:** Automatically retrieves sales data from `data.csv`.
*   **Sales Calculation:** Parses the CSV to sum the values in the 'sales' column.
*   **Responsive Design:** Built with Tailwind CSS for a modern and adaptable user experience across various device sizes.
*   **Dynamic Title:** Updates the page title with a unique summary ID after data is processed.
*   **Error Handling:** Provides visual feedback in case of data fetching or parsing errors.

## How to Run

1.  **Save Files:** Place `index.html`, `README.md`, and `LICENSE` in the same directory.
2.  **Add `data.csv`:** Ensure a `data.csv` file is present in the same directory. This file should contain a header row, and one of the columns must be named `sales` with numeric values.
    *   **Example `data.csv` structure:**
        ```csv
        id,product,sales,region
        1,Laptop,1200.50,North
        2,Mouse,25.00,North
        3,Keyboard,75.25,South
        4,Monitor,300.00,East
        5,Webcam,50.75,West
        ```
3.  **Open `index.html`:** Open the `index.html` file directly in your web browser.

The application will automatically fetch `data.csv`, calculate the total sales, and display it on the page.

## Technologies Used

*   **HTML5:** For the basic structure of the web page.
*   **Tailwind CSS:** For styling and ensuring responsiveness.
*   **JavaScript (ES6+):** For fetching data, parsing CSV, and dynamic content updates.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

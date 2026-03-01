# Vault - Offline Financial Tracker

Vault is a minimalist financial dashboard designed to track income and expenses using the Philippine Peso (PHP).

It works entirely offline. It runs in your web browser but saves your data directly to a local JSON file on your computer.

## Technologies Used

*   **HTML5**
*   **CSS3** (Modern, minimalist design)
*   **JavaScript** (Vanilla, no frameworks)

**Note:** This project does not use a backend database or the PHP programming language. It is a single HTML file.

## Features

*   **Offline Storage:** Data is saved to a local JSON file on your hard drive. No data is sent to the internet.
*   **Modern Design:** Clean interface with a dashboard and transaction list.
*   **Currency:** Formatted specifically for the Philippine Peso (PHP).
*   **Visual Charts:** Includes a doughnut chart to visualize spending by category.
*   **Backup:** Supports exporting and importing data JSON files.

## How to Run

1.  Download the `index.html` file.
2.  Open the file using a desktop web browser like **Google Chrome** or **Microsoft Edge**.
3.  No server installation is required.

## How to Use

### Starting for the first time
1.  Open the `index.html` file in your browser.
2.  Click **New Data File**.
3.  The browser will ask where to save a file named `vault_data.json`.
4.  Select a folder (e.g., Documents) and click **Save**.
5.  The dashboard will appear.

### Opening next time
1.  Open the `index.html` file.
2.  Click **Open Existing**.
3.  Select the `vault_data.json` file you created previously.

### Adding Transactions
1.  Click the **Income** or **Expense** button.
2.  Enter the amount and description.
3.  Click **Save Record**.
4.  The application automatically saves the data to your local file.

## Browser Support

This application uses the **File System Access API** to modify files on your computer.

*   **Supported:** Google Chrome, Microsoft Edge, Opera, Brave (Desktop versions).
*   **Not Supported:** Mozilla Firefox, Apple Safari, and Mobile Browsers.

## License

This project is open source.

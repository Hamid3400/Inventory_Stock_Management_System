# Kinplus Inventory & Stock Management System

A responsive inventory application built with HTML5, CSS3 and vanilla JavaScript.

## Run the project
1. Extract the ZIP file.
2. Open the extracted `Inventory_Stock_Management_System` folder.
3. Double-click `index.html` to open it in Chrome, Edge, Firefox or another modern browser.

No server or package installation is required.

## Main features
- Dashboard with product count, available units, estimated stock value and low-stock alerts
- Add, edit and delete products
- Unique SKU validation and category/status filtering
- Stock-in and stock-out recording
- Prevention of stock-out quantities exceeding available stock
- Transaction history, search and movement filters
- Inventory valuation and stock status report
- CSV export for products, transactions and inventory report
- Responsive desktop and mobile layout
- Browser localStorage persistence

## Data and limitations
This is a client-side prototype. Data is stored in the browser's localStorage on the current device/browser profile. It is not a central database and does not synchronise across devices. The Administrator label is a demonstration profile, not secure authentication. Sample products and transactions are demonstration data; replace them with genuine project data before capturing final academic screenshots. There is no remote server, backend API, multi-user access or role-based security in this version.

## Structure
- `index.html` — application pages and forms
- `css/styles.css` — layout and visual styling
- `js/app.js` — application logic and local data storage

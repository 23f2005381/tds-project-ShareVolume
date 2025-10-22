# CarMax Share Volume Web Application

This is a simple web application that displays the maximum and minimum number of common stock shares outstanding for CarMax (CIK: 0001170010) over recent fiscal years.

## Features

- Fetches data from the SEC's XBRL API for a given company's CIK.
- Displays the maximum and minimum shares outstanding for fiscal years greater than 2020.
- Supports dynamic fetching and updating of data using URL query parameters (e.g., `index.html?CIK=0001018724`).

## Technologies Used

- HTML, CSS, JavaScript
- Bootstrap 5.3 for responsive design
- Fetch API for data retrieval

## How to Use

1. Open `index.html` in a web browser.
2. By default, the application fetches data for CarMax.
3. To view data for a different company, append `?CIK=<CIK_NUMBER>` to the URL, replacing `<CIK_NUMBER>` with the desired CIK.

## Error Handling

The application includes basic error handling to manage failed API requests.

## License

This project is licensed under the MIT License (see LICENSE file for details).
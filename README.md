# Assurant Shares Outstanding Viewer

This is a simple web page that fetches and displays the number of common stock shares outstanding for the company Assurant (CIK 0001267238), based on SEC XBRL data.

## Features
- Fetches data from SEC API endpoint for a given CIK
- Determines and displays the entity name
- Calculates and displays the maximum and minimum number of shares outstanding for fiscal years after 2020
- Supports dynamic loading for different companies via URL query parameter

## How to Run
- Save this code as `index.html`
- Open it in a web browser.
- Optionally, specify a different CIK in the URL query string, e.g., `index.html?CIK=0001018724`.

## Notes
- The data fetch uses [AllOrigins](https://allorigins.win/) as a CORS proxy to avoid cross-origin issues.
- The data is synchronized on page load.

## License
This project is licensed under the MIT License.

---

**Ensure that the accompanying `uid.txt` file contains the specified UID content as provided.**

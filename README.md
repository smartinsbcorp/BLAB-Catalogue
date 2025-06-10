# German B Corps Catalogue

This repository contains a simple catalogue of German B Corps. The `index.html` page automatically loads company information from `data/companies.csv` using JavaScript. To update the website you only need to edit the CSV file—no coding knowledge is required.

## How to update

1. Open [`data/companies.csv`](data/companies.csv) in a spreadsheet program (e.g. Excel, Google Sheets) or edit it directly on GitHub.
2. Each row describes a company with fields such as name, description, website and logo URL.
3. Save the file (or commit your changes if using GitHub). When the page is reloaded, the new data will appear automatically.

The site uses [PapaParse](https://www.papaparse.com/) to read the CSV and generate the company cards dynamically in the browser.

## Local development

Open `index.html` in a web browser. No build step is needed because all data is loaded client side.

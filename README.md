# Pilke Espoonlahti Pamark Order App

## Overview

This simple web application is designed to help manage and generate order lists for Pilke Espoonlahti. It allows users to input order quantities for various items and generate a PDF order list with a professional layout.

## Live Demo

The app is live and can be accessed here: [Pilke Espoonlahti Pamark Order App](https://yuzi2021.github.io/order-app/)

## Features

- Easy-to-use web interface
- Dynamic item list with pre-filled product information
- Input fields for order quantities
- Generates a professional PDF order list
- Automatically numbers items in the generated PDF
- Includes order date on the PDF
- Mobile-friendly design

## How to Use

1. Open the app in a web browser.
2. For each item you want to order, enter the quantity in the "Amount" field.
3. Click the "Generate PDF" button at the bottom of the page.
4. A PDF will be generated and downloaded with the filename format: `Pilke_Espoonlahti_Pamark_Order_YYYY-MM-DD.pdf`

## PDF Output

The generated PDF includes:
- Title: "Pilke Espoonlahti Pamark Order List"
- Current date
- Table with columns: No., Item, Order Number, Unit, Amount
- Only items with quantities greater than 0 are included in the PDF

## Development

This app is built using HTML, CSS, and JavaScript. It uses the following libraries:
- [jsPDF](https://github.com/MrRio/jsPDF) for PDF generation
- [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) for creating tables in the PDF

## Deployment

This app is deployed using GitHub Pages and can be accessed at: https://yuzi2021.github.io/order-app/

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request.

## Support

For support or to report issues, please open an issue in the GitHub repository.

## License

This project is open source and available under the [MIT License](LICENSE).
"Rebuilding GitHub Pages" 

# Country Info

This project is a simple web application that allows users to select a country from a dropdown menu and view its flag and population.

## Features
- Fetches country data from the [REST Countries API](https://restcountries.com/)
- Displays a list of countries in a dropdown menu
- Shows the selected country's flag and population

## Technologies Used
- HTML
- CSS
- JavaScript
- XMLHttpRequest (AJAX)

## How It Works
1. The `loadCountries()` function sends an AJAX request to the REST Countries API to fetch a list of countries.
2. The response is parsed into a dropdown menu where each country is listed.
3. When a user selects a country, the `displayCountryInfo()` function updates the flag and population details.

## Usage
1. Download or clone this repository.
2. Open `index.html` in any modern web browser.

## Code Explanation
- **HTML:** Contains the dropdown menu, image placeholder for the flag, and a paragraph for the population.
- **CSS:** Styles the UI elements for better readability and presentation.
- **JavaScript:** Handles the AJAX request, populates the dropdown, and updates the UI dynamically.

## Preview
![Country Info Preview](preview.png) *(Replace with an actual screenshot if available)*

## License
This project is open-source and available under the MIT License.

CURRENCY CONVERTOR
The Currency Converter is a web application that provides real-time currency exchange functionality using up-to-date exchange rates. Users can convert amounts between different currencies while viewing corresponding country flags for better visual clarity. This lightweight tool is ideal for travelers, businesses, or anyone needing quick currency conversion.

Features
Real-Time Exchange Rates:

Fetches the latest rates from the ExchangeRate-API.
Displays accurate conversion results instantly.
Dynamic Country Flags:

Automatically updates flag images based on selected currencies.
Provides a user-friendly and visually engaging experience.
Preloaded Currencies:

Includes a dropdown list of over 150 currencies with their corresponding country codes.
Smart Defaults:

Pre-selects common currencies (e.g., USD to INR) for convenience.
Retains input amount and handles invalid entries by defaulting to "1."
Interactive Design:

Clean and responsive UI styled with modern CSS.
Easy-to-use dropdown selectors for "From" and "To" currencies.
Technical Description
Frontend:

Built with HTML, CSS, and JavaScript.
Utilizes the Flags API to display country flags dynamically.
Backend:

Exchange rate data is fetched from the https://api.exchangerate-api.com/v4/latest endpoint.
Asynchronous fetch operations ensure a smooth user experience.
Functionality:

Dropdown Population:
Populated dynamically using a predefined countryList object mapping currency codes to country codes.
Exchange Rate Calculation:
Retrieves real-time exchange rates for selected currencies and calculates the converted value.
Error Handling:
Displays user-friendly messages for API errors or invalid input.
Code Structure:

HTML:
Defines the structure with dropdowns, input fields, and buttons.
CSS:
Provides a clean and responsive layout with visually appealing colors and elements.
JavaScript:
Handles dynamic dropdown updates, API calls, and conversion logic.
Usage Workflow
Load the Application:

The app initializes with default currencies (e.g., USD to INR) and fetches the current exchange rate.
Select Currencies:

Use the "From" and "To" dropdowns to pick the currencies you wish to convert between.
Enter Amount:

Input the amount in the "From" field.
Get Exchange Rate:

Click the Get Exchange Rate button to calculate the converted value, which is displayed with the conversion formula (e.g., 1 USD = 80 INR).
Future Enhancements
Add a currency favorites list for quick access.
Include historical exchange rate charts.
Support offline functionality using cached rates.
This application is compact yet versatile, serving as a practical tool for real-time currency conversions with a user-friendly interface.

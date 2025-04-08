The Currency Converter Application is a simple Java-based GUI program designed to perform real-time currency conversions between commonly used currencies, specifically USD (United States Dollar), EUR (Euro), and INR (Indian Rupee). The application leverages the Swing framework to create an interactive interface, making it user-friendly and easy to navigate.

The application allows users to input an amount, select the source and target currencies from dropdown menus, and convert the amount with the click of a button. The conversion process is based on predefined static exchange rates, which are hard-coded into the application for demonstration purposes. These rates can be updated as needed to reflect current market values.

The user interface is built using a GridLayout to organize labels, text fields, dropdown menus, and action buttons efficiently. Upon clicking the "Convert" button, the application processes the user’s input, performs the currency conversion, and displays the result dynamically.

Key features of the application include:

Currency Selection: Users can choose from USD, EUR, and INR for both source and target currencies.

Real-Time Conversion: Conversion occurs instantly upon user action.

Input Validation: The program handles invalid inputs gracefully, providing error messages for non-numeric entries.

Simple, Intuitive UI: The layout ensures clarity, making it accessible even to non-technical users.

While this version uses static exchange rates, the code structure allows for easy modification or enhancement to integrate real-time exchange rate APIs in the future. This makes the application a foundational prototype for more advanced currency conversion systems.


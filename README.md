# Currency Converter

This is a simple currency converter application written in Java. It allows users to convert between different currencies using real-time exchange rates obtained from an API. 

## Installation

To use this application, follow these steps:

1. Clone the repository to your local machine:
   git clone https://github.com/yourusername/currency-converter.git

2. Open the project in your preferred Java development environment.

3. Make sure you have the necessary dependencies installed. This project uses the `org.json` library for JSON parsing. You can download it from [here](https://github.com/stleary/JSON-java).

4. Build and run the `CurrencyConverter.java` file.

## Usage

1. Run the application.

2. Follow the prompts to select the currency you want to convert from and to, and enter the amount you wish to convert.

3. The application will display the converted amount.

4. You can choose to make another conversion or exit the application.

## Important Notice

Please note that this application is currently not functional due to changes in the API it relies on. The API now requires a subscription plan to access exchange rate data, which includes obtaining an SSL certificate. 

When this project was initially developed, the API was freely accessible and supported conversion between more than 200 currencies. However, with the recent changes, users need to subscribe to a plan offered by the API provider to restore functionality.

To make the application work again:

1. Obtain a subscription plan from the API provider's official website.

2. Follow the instructions provided in the subscription plan to obtain the necessary SSL certificate.

3. Modify the `GET_URL` variable in the `sendHttpGETRequest` method of the `CurrencyConverter` class to include the required authentication parameters according to your subscription plan.

4. Rebuild and run the application with the updated URL to enable currency conversions.

## Resources

- [API Documentation]([https://api.exchangeratesapi.io/](https://exchangeratesapi.io/))

## Contributing

Contributions to improve the functionality or update the API integration are welcome. Feel free to fork the repository, make your changes, and submit a pull request.

# currency-converter
This is a Currency Converter web application built using HTML, CSS, and JavaScript. It fetches live exchange rates using an external API and allows users to convert between various currencies.

#Features
Converts currency values from one currency to another.
Utilizes a live exchange rate API for up-to-date conversion rates.
Simple and intuitive user interface.
#Live Exchange Rate API
This project uses an API that provides real-time currency exchange rates. The exchange rate data is fetched from the following link:

API Link: "https://latest.currency-api.pages.dev/v1/currencies/eur.json"

The API format returns exchange rates in JSON format. The rate for conversion is retrieved as follows:

format: /currencies/{fromCurrency}
        where the rate is stored in json[fromCurrency][toCurrency].

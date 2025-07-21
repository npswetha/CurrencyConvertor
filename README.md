## Currency Convertor Application

This is a simple yet functional Flutter-based currency converter application that fetches real-time exchange rates using the [Open Exchange Rates API](https://openexchangerates.org/). It allows users to convert from USD to any currency or between any two currencies using the latest exchange rates.

## Overview

The application supports:
- Real-time currency conversion
- Conversion from USD to any supported currency
- Conversion between any two currencies
- Fetching and displaying live exchange rates and currency names
- Mobile-friendly user interface built with Flutter

## Features

### USD to Any Currency
- Input amount in USD
- Select target currency
- View the converted amount

### Any to Any Currency
- Input amount in any base currency
- Select both base and target currencies
- View the converted result

### UI & Functionality
- Clean, card-based layout using Flutter Material components
- Separate reusable widgets for USD to Any and Any to Any conversions
- Asynchronous data fetching with `FutureBuilder`
- Error handling for invalid inputs
- Form validation and dropdowns with currency list

## Tech Stack

- **Frontend**: Flutter (Dart)
- **API Provider**: Open Exchange Rates
- **Libraries Used**:
  - `http` for API calls

## Setup and Installation

1. Clone this repository:
   https://github.com/npswetha/CurrencyConvertor

3. Navigate into the project directory:
   cd currencyconvertor
   
4. Install dependencies:
   flutter pub get
   
6. Set up your [Open Exchange Rates API key](https://openexchangerates.org/signup):
- Add your API key to the `fetchrates.dart` file in the HTTP request URL.

5. Run the app:
   flutter run

 
## API Usage

The application uses the `/latest.json` endpoint to retrieve exchange rates and `/currencies.json` to retrieve the list of supported currencies.

Example:
https://openexchangerates.org/api/latest.json?app_id=YOUR_APP_ID
https://openexchangerates.org/api/currencies.json






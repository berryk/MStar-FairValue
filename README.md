# MStar-FairValue

A TamperMonkey script that enhances Morningstar watchlists by modifying the API parameters and adding sortable custom columns with Fair Value CAGR data.

## Features

- Intercepts and modifies Morningstar watchlist API requests to include additional fields
- Adds custom columns with Fair Value CAGR calculations
- Supports both XMLHttpRequest and Fetch API interception
- Maintains mappings between tickers, exchanges, and Morningstar security IDs
- Includes caching to prevent duplicate processing and reduce API load

## Installation

1. Install the [TamperMonkey](https://www.tampermonkey.net/) browser extension
2. Create a new script in TamperMonkey
3. Copy and paste the contents of `MorningstarFairValue.js` into the script editor
4. Save the script

## Usage

After installation, simply navigate to Morningstar watchlist pages. The script will automatically intercept API requests and enhance the watchlist with additional data and custom columns.

## License

MIT

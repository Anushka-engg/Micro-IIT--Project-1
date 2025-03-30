# Currency Converter (MICRO IIT PROJECT 1)

## Overview
This project is a **Currency Converter** built using Python in Google Colab. It fetches real-time exchange rates using an API and converts amounts between different currencies.

## Features
- Converts an amount from one currency to another.
- Uses real-time exchange rates from an API.
- Supports multiple currencies.

## Requirements
Before running the script, ensure you have the following installed:
- Python 3
- `requests` library for API calls

Install dependencies using:
```bash
pip install requests
```

## How to Run
1. Download the `.py` file from Google Colab.
2. Open a terminal or command prompt and navigate to the file's directory.
3. Run the script:
   ```bash
   python currency_converter.py
   ```
4. Enter the required details (amount, source currency, target currency) when prompted.

## API Key Setup
The script requires an **API key** for fetching exchange rates. Update the following line in the script with your API key:
```python
API_KEY = "your_api_key_here"
```

## Example Usage
Input:
```
Enter amount: 100
Enter source currency (e.g., USD): USD
Enter target currency (e.g., EUR): EUR
```
Output:
```
100 USD is equivalent to 92.50 EUR
```

## Notes
- Ensure you have a working internet connection to fetch exchange rates.
- The accuracy of conversion depends on the API provider.

## License
This project is for educational purposes and is open-source.


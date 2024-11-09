# Extract or Enter Price and Convert to Bangladeshi Taka Words (Uppercase)

A Tampermonkey userscript for converting numeric prices into words in Bangladeshi Taka format (in uppercase). It extracts a price value from a field, automatically fills a target field, and displays the equivalent amount in words. The script also supports manual input for flexibility.

## Features
- **Automatic Price Extraction**: Pulls price value from a specified input field and copies it to the designated price field.
- **Bangladeshi Taka Conversion**: Converts the price amount to words in Bangladeshi currency format, displayed in uppercase.
- **Manual Input Support**: Allows manual entry of a price value in the designated field with real-time conversion to words.
- **Auto Update on Input Change**: Automatically updates the word conversion if the input price field changes.

## Installation

1. Install [Tampermonkey](https://www.tampermonkey.net/) in your browser.
2. Click on the Tampermonkey icon, select **Create a New Script**, and paste the script code from this repository.
3. Save and activate the script; it will run on pages under `https://salsabeelcars.site/*`.

## Usage

1. Navigate to a form on the [Salsabeel Cars Website](https://salsabeelcars.site/).
2. The script will automatically:
   - Retrieve the value from a specific field and copy it to the `#price` field.
   - Convert the numeric value in `#price` to Bangladeshi Taka words and display it in `#inWord`.
3. You can also manually enter a value in the `#price` field to convert it to words.

## Code Overview

- **convertToWords(num)**: Converts a numeric value to words in Bangladeshi Taka format.
- **updatePriceAndWords(autoInput)**: Controls the extraction, manual entry, and word conversion based on user actions.

## License

This project is licensed under the MIT License.

## Disclaimer

This script is for personal or educational use on the specified website. The author is not responsible for misuse. Ensure compliance with the website’s terms before using this script.

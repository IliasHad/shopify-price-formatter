# Shopify Price Formatter

A lightweight package for formatting Shopify product prices according to various display formats.

## Installation

npm install @your-package-name/shopify-price-formatter


## Usage

```javascript
import { formatPrice } from "@your-package-name/shopify-price-formatter";

const price = 113465 
const formattedPrice = formatPrice({ price, format: "{{ amount }}" });
console.log(formattedPrice); // Output: "$1,134.65"
```

Supported Formats
{{ amount }}: Formats price with two decimal places and uses period as a decimal separator, and comma as a thousand separator.
{{ amount_no_decimals }}: Formats price without any decimal places and uses comma as a thousand separator.
{{ amount_with_comma_separator }}: Formats price with two decimal places and uses comma as a thousand separator.
{{ amount_no_decimals_with_comma_separator }}: Formats price without decimal places and uses comma as a thousand separator.
{{ amount_with_apostrophe_separator }}: Formats price with two decimal places and uses apostrophe as a thousand separator.
{{ amount_no_decimals_with_space_separator }}: Formats price without decimal places and uses space as a thousand separator.
{{ amount_with_space_separator }}: Formats price with two decimal places and uses space as a thousand separator.
{{ amount_with_period_and_space_separator }}: Formats price with two decimal places and uses period as a thousand separator.


License
This package is licensed under the MIT License. See the LICENSE file for details.

Contributing
Contributions are welcome! Please read the CONTRIBUTING.md file for guidelines.

Issues
If you encounter any issues or have suggestions for improvements, please open an issue.


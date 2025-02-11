# POS JS HTML

## Overview
POS JS HTML is a simple Point of Sale (POS) application built using JavaScript and HTML. This application is designed to help small businesses manage sales transactions efficiently.

## Features
- User-friendly interface
- Add and remove items from the cart
- Calculate total price including taxes
- Generate receipts
- Persistent storage using local storage

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/pos-js-html.git
    ```
2. Navigate to the project directory:
    ```bash
    cd pos-js-html
    ```
3. Open `index.html` in the chrome web browser.

## Data format of information from device output
    ```js
    {
        name: 'STMicroelectronics_POS80_Printer_USB',
        displayName: 'STMicroelectronics POS80 Printer USB',
        description: 'POS-80',
        status: 3,
        isDefault: true,
        options: {
        copies: '1',
        device-uri: 'usb://STMicroelectronics/POS80%20Printer%20USB?serial=Printer',
        finishings: '3',
        job-cancel-after: '10800',
        'job-hold-until': 'no-hold',
        'job-priority': '50',
        'job-sheets': 'none,none',
        'marker-change-time': '0',
        'number-up': '1',
        'printer-commands': 'none',
        'printer-info': 'STMicroelectronics POS80 Printer USB',
        'printer-is-accepting-jobs': 'true',
        'printer-is-shared': 'false',
        'printer-is-temporary': 'false',
        'printer-location': 'Michael’s MacBook Pro',
        'printer-make-and-model': 'POS-80',
        'printer-state': '3',
        'printer-state-change-time': '1736073663',
        'printer-state-reasons': 'none',
        'printer-type': '2117636',
        'printer-uri-supported': 'ipp://localhost/printers/STMicroelectronics_POS80_Printer_USB',
        system_driverinfo: 'POS-80'
        }
    }
    ```

## Usage
1. Add items to the cart by entering the item name and price.
2. View the cart to see all added items.
3. Click on the "Checkout" button to calculate the total price and generate a receipt.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, please contact [michael rumack](mailto:michael@ledgedog.com).

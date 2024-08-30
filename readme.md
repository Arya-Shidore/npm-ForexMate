# forexmate

`forexmate` is a simple and easy-to-use Node.js package that allows you to convert currency values using real-time exchange rates. It’s perfect for applications that require currency conversion functionality.


# Installation

To install `forexmate`, use npm:

`npm install forexmate`

## Usage

Here’s a basic example of how to use `forexmate`:


## API

 `forexExchange(fromCurrency: string, toCurrency: string, amount: number): Promise<number>`

-   **fromCurrency**: The currency code you want to convert from (e.g., 'USD').
-   **toCurrency**: The currency code you want to convert to (e.g., 'EUR').
-   **amount**: The amount of money to convert.

Returns a promise that resolves with the converted currency value

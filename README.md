# Currency Converter

A live currency converter built with HTML, CSS and JavaScript. Enter an amount, pick two currencies, and it converts using today's exchange rates.

![Currency Converter converting 100 USD to INR](screenshots/converter.png)

## Features

- Converts between 8 currencies: USD, INR, EUR, GBP, JPY, AED, CAD and AUD
- Live exchange rates from the free [ExchangeRate API](https://www.exchangerate-api.com/docs/free) (`open.er-api.com`)
- Checks the amount before converting (must be a number above 0)
- Shows "Converting..." while it loads, and a clear message if the internet or the API fails
- Results formatted with thousands separators and two decimal places (e.g. `100 USD = 9,507.36 INR`)

## What I used

| Concept | Where |
|---|---|
| Fetch API with `async` / `await` | getting the rates for the chosen currency |
| `try` / `catch` and `response.ok` checks | error handling |
| DOM methods (`getElementById`, `innerText`) | reading the form and showing the result |
| Template literals and `toLocaleString` | building and formatting the result |
| CSS Flexbox | centring the card on the page |

## Run it

No install needed. Download or clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/Vineetsing9019/JavaScriptProject.git
```

## Author

Vineetsing Girase · [GitHub](https://github.com/Vineetsing9019)

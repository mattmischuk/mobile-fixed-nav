# Horizontal Scroll iOS Safari Bug

A repo created to reproduce the dead scroll area on iOS Safari.

## Getting Started

Node.js is a requirement. See [Node.js](https://nodejs.org) for installation instructions.

Run the following commands:

1. `npm install gulp -g`
2. `npm install`
3. `npm start`

## Reproducing Bug

1. Build the codebase locally
2. Open the server on iOS Safari 8+
3. Scroll down the page until the native tap bar recedes
4. Try scrolling the fixed nav at the bottom to the left or right

## Intended Result

At any scroll position the horizontal scroll should function the same whether the native tap bar is open or not.

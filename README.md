# Kaah

Shopify Node and react

<!-- ![example-site](example-site.gif) -->

## Objectives

Build react app using shopify cli

## Shopify App CLI

- [x] Create shopify partner account
- [x] Create Shopify development store to install and test apps
- [x] Ruby 2.5.2+
  - $ brew install ruby
- [x] install the CLI
  - $ brew tap shopify/shopify
  - $ brew install shopify-cli
  - [x] install node
  - [x] Create ngrok account
    - Shopify ClI uses ngrok to create secure tunnel from public internet to your local development
- [x] checkout CLI core commands

  - help
  - connect
  - create
  - logout

- [x] $ shopify create node
  - 1. App name = Kaah
  - 2. type of app = (public)
- [x] cd kaah
  - [x] $ shopify serve
  - [x] do you want to create new url? = yes
  - [x] to install and start using press url.......
  - [x] press install unlisted app
    - [x] embedding the app to the shopify admin - creates very pleasant and easy to use user experience.

  # Building a UI with Polaris
- [x] open project with code
- [x] /pages/index.js add button
      _[x] Product selector button
      _[x] On products - add place holder products from cli
      _[x] command reference
      _[x] Populate command
      ✅ 1. $ shopify populate products
  # Accessing React components
- [x] Shopify App bridge
  - React components
    - ResourcePicker ( runs a model that helps you with list of resources {products})
- [x]import resource picker
- [x] convert index.js to class
- [x] Add ResourcePicker
- [x] Restart server ( shopify serve)
-   * pkill -f node( to reset server)
- [x] Add open, onCancel and onSelection
- [x] Add onSelectionHandle function
- [x] use map to create the product ID's


## Improvements

- []
- []
- []

## Credits

- []
- []

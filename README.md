[![CircleCI](https://circleci.com/gh/CityOfZion/neon-wallet.svg?style=svg)](https://circleci.com/gh/CityOfZion/neon-wallet)

# Neon Wallet

![wallet](/wallet.png)

The aim of this project is to port the current NEO web wallet to electron with a better UI.

## Installation

A standalone app will be available soon. For now, you will need to build the wallet manually.

### Required Tools and Dependencies

  - `npm install -g webpack` Global Webpack
  - `npm install -g jest` Unit testing framework

### Developing and Running

Execute these commands in the project's root directory:

  - `npm install` Installing node dependencies
  - `webpack` or `webpack --watch` for live reload.
  - `npm start` for running the project
  - `npm test` or `npm test-watch` for live testing.

### Support

A gentle reminder, github issues is meant to be used by developers for maintaining and improving the codebase, and is not the proper location for support issues. Questions such as

- Why can't I log in?
- I lost my private key, is there anyway to recover?
- Why is my balance not showing?

should be asked in proper support channels such as the [NEO subreddit](https://www.reddit.com/r/NEO/), or the official [NEO slack](https://neosmarteconomy.slack.com).

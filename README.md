
# Account Abstraction App using Biconomy

A project that uses Biconomy's Account Abstraction SDK to create a smart contract account and transfer tokens. Built on:
* React with NextJS 13
* Biconomy's SDK
* Deployed on Polygon Mumbai Testnet

![homepage](/assets/home.png)

## Key Features

* Login with social media accounts (Google and Facebook)
* Use Two Factor Authentication (optional).
* Fund the account with a faucet or recieve transfers
* Send ERC20 tokens while paying for gas in ERC20 tokens

## How To Use

Clone this repo and then, from your command line:

```bash

# Go into the repository
$ cd  account-abstraction-biconomy

# Install dependencies
$ npm install

# Run the app. This will start the NextJs frontend app.
$ npm start
```

## App Screenshots

### Login Page

![login](/assets/1.png)

### Social Login options

![socials](/assets/2.png)

### Accounts to Login

![accounts](/assets/3.png)

### Two Factor Auth enabling

![tfa](/assets/5.png)

### Transfer process

![transfer-1](/assets/6.png)
![transfer-2](/assets/7.png)
![transfer-3](/assets/8.png)


## Credits

I followed both of these guides to achieve this:

- [LearnWeb3](https://learnweb3.io/lessons/account-abstraction-using-biconomy-social-logins-and-paymasters)

And also the docs for the tools used

- [Biconomy](https://docs.biconomy.io/)

## License

MIT
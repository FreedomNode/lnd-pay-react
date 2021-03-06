# LND Pay React

LND Pay frontend written in React. 

Make sure to install [LND Pay backend](https://github.com/mariodian/lnd-pay) first.

## Install

`yarn install`

or

`npm install`

## Run

Runs the app in the development mode.

`yarn start`

or

`npm start`

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Use

`ReactDOM.render(<LndPay />, document.getElementById('root'));`

### Options

LndPay takes parameters `amount`, `description` and `descriptionHidden` that alter the way UI is build.

Examples:

`ReactDOM.render(<LndPay amount="10" />, document.getElementById('root'));`

`ReactDOM.render(<LndPay description="Coffee payment" />, document.getElementById('root'));`

`ReactDOM.render(<LndPay description="Coffee payment" descriptionHidden />, document.getElementById('root'));`

## Build

Builds the app for production to the `build` folder.

`yarn build`

or

`npm run build`

It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

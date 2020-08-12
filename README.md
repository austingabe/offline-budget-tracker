# offline-budget-tracker
Offline-budget tracker is a progressive web application built with `Node.js` and `MongoDB` that can add expenses and deposits to a user's budget with or without a network connection. When the user is not connected to a network, the input data will be cached, and when the user connects to a network and refreshes the page, the data will be sent to the database. Refresh once more, and the most up-to-date data including submissions while offline will be displayed.

## Installation
First, install [Node.js](https://nodejs.org/en/) and [MongoDB](https://docs.mongodb.com/manual/installation/).<br>
Next, in order to install the necessary dependencies, run `npm install` from the command line while inside the root directory.<br>
Documentation for [Compression](https://www.npmjs.com/package/compression)<br>
Documentation for [Express](https://www.npmjs.com/package/express)<br>
Documentation for [Lite-server](https://www.npmjs.com/package/lite-server)<br>
Documentation for [Mongoose](https://www.npmjs.com/package/mongoose)<br>
Documentation for [Morgan](https://www.npmjs.com/package/morgan)

## Usage
In order to start the application, run `npm start` and navigate to the specified `localhost` location in your browser. The application will load, and the user can access and utilize it as desired.

## Support
For any questions, please contact austinlee721@gmail.com
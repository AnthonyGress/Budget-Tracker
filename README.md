# Budget Tracker [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Screenshot

<a href="https://immense-thicket-58645.herokuapp.com/" target="_blank"><div align="center"><img width="1435" alt="Screen Shot Budget Tracker" src="https://user-images.githubusercontent.com/70029654/130147641-8fbc4552-d25c-4a74-bd42-f9cc86a2085e.png">

</div></a>

## Live Site [Click Here](https://immense-thicket-58645.herokuapp.com/)

## Description

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important.

This is a full stack progressive web appp (PWA) that allows you to add, subtract, and save your budget/expenses both online and offline. It also organizes the data using a graph which provides detailed information about your spending habits over time.

This application's structure follows the Model-View-Controller paradigm. It uses **_MongoDB_** and **_Mongoose_** to connect to a NoSQL MongoDB database for the Models and **_Express.js_** for the Controllers. It also uses **_indexedDB_** for temporary storage of data while offline.

Offline Functionality:

- Enter deposits offline

- Enter expenses offline

When brought back online:

- Offline entries should be added to tracker.

## Table of Contents

- [Description](#Description)
- [Installation](#Installation)
- [Usage](#Usage)
- [Tests](#Tests)
- [License](#License)
- [Collaboration](#Collaboration)

## Installation

### Dependencies: **Requires** **_Node.js_** installed on your computer

To install the npm dependencies cd into the main directory and run:

```
npm i
```

## Usage

This site is live at [Budget Tracker](https://immense-thicket-58645.herokuapp.com/)

To use this node app and create your own local development server, clone the repo down, use the terminal to cd into the root directory. Then run:

```
npm start
```

Use the terminal and start up the server. You can then access the API endpoints through a web browser or Insomnia.

## Tests

To test please run:

```
npm test
```

## License

[MIT License](https://opensource.org/licenses/MIT)

## Collaboration

Please feel free to collaborate with me on this project! Just fork it and submit a well documented pull request.

If you have any questions, please contact me at techx@opayq.com

**This app is strictly for educational purposes only**

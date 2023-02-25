# Backend-Shopper
      
## Description

Backend Shopper is what powers the front-end of a ecommerce app. It's built using JavaScript and helps the app manage all of the products, categories, and tags that are available.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

- [Project repo](https://github.com/shaynefw/Backend-Shopper)
- [Project deployed link](https://shaynefw.github.io/Backend-Shopper/)
- [Project Video Demo](https://drive.google.com/file/d/1raG3xXe_mYRqRKsheDCphAYvvI8qSdUZ/view?usp=sharing)

1. Install Node.js: Before you can install and run the app, you need to have Node.js installed on your computer. You can download the latest version from the official Node.js website: https://nodejs.org/en/download/

2. Download the code: You can download the code for the app from the source repository. Save the code to a directory on your computer.

3. Install dependencies: Open a terminal or command prompt in the directory where the code is saved, and run the following command to install the required dependencies:
```
npm install
```
This will download and install all the required packages listed in the package.json file.

5. Set up environment variables: The app uses environment variables to store sensitive information like database credentials, API keys, or other configuration options. You should create a .env file in the root directory of the app, and add any necessary environment variables. You can copy the example .env.example file and customize it as needed.

6. Seed the database: If the app requires initial data to be added to the database, you should run the seed script to populate the database with data. You can do this by running the following command:
```
npm run seed
```
This will run the seed.js script and add the data from the seed files to the database.

6. Start the app: To start the app, run the following command:
```
npm start
```
This will start the server and make the app available in your web browser. You can access the app by navigating to http://localhost:3001 in your insomnia.

## Usage

1. Download and install Insomnia: If you haven't already, you should download and install Insomnia, which is a popular HTTP client for testing APIs. You can download it from the official website: https://insomnia.rest/download

2. Launch Insomnia: Once you have installed Insomnia, launch the app on your computer.

3. Create a new workspace: In Insomnia, you can create a new workspace to organize your API requests. Click on the "Create" button in the top left corner of the app, and then select "New Workspace". Give your workspace a name, and click "Create".

4. Create a new request: In the workspace, click on the "New Request" button. Enter a name for your request, and select the HTTP method (e.g. GET, POST, PUT, DELETE) that you want to use.

5. Enter the API endpoint: In the "URL" field, enter the API endpoint that you want to access. All of the routes in the routes/index.js file start with /api, so you should include that in your URL. For example, if you want to access the GET /api/products route, you would enter http://localhost:3001/api/products as the URL.

6. Send the request: Once you have entered the URL and any necessary headers or body parameters, click the "Send" button to send the request. You should see the response from the API displayed in the app.

7. Repeat for other routes: You can repeat these steps to access other routes in the app. The available routes are defined in the routes/index.js file, and include /api/categories, /api/products, and /api/tags.

![screenShot](./assets/images/demo.gif)

## Credits

Credits to my professor, instructors, classmates, and tutors for their invaluable support and guidance throughout my learning journey. Also to the developers of the various technologies used, including Google, documentation resources, and AI technologies that have provided valuable assistance and inspiration.

## License

MIT License

Copyright (c) 2023 Shayne Whayne

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Badges

![JavaScript](https://img.shields.io/badge/JavaScript-100%25-yellow)

## Features

Built with JavaScript using Sequelize, which is an Object-Relational Mapping (ORM) library for Node.js.

## How to Contribute

## Tests

## Questions

If you have any questions you can reach me by..

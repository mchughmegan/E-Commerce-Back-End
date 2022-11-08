# E-Commerce-Back-End
UTA Bootcamp Challenge 13

![License: MIT](https://img.shields.io/badge/License-MIT-yellow)

## Description

This project uses express.js to create a E-Commerce Back End application. Once entering the applicable commands in the terminal to install all necessary dependencies, including dotenv, express, mysql2, seeds, and sequelize, the user will be able to view their routes in Insomnia.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)
* [Questions](#questions)

## Installation

In VS Code, enter the following in the Integrated Terminal to install the applicable packages for this application:

```
npm install
```
In the db folder in the Integrated Terminal, enter the following, followed by your mysql password when prompted.
```
mysql -u root -p
```
Then, run the following:
```
SOURCE schema.sql
```
Then, in the main integrated terminal run:
```
node seeds/index.js
```
And finally, run:
```
node server.js
```

## Usage

To view a video walkthrough of the application, click on this link https://drive.google.com/file/d/13a-uCoTGxABZ0jm_RHvoZ__Q_JIFQBTp/view.

After running the necessary commands in the integrated terminal as explained above in installation, the user will see App listening on port 3001! in their Integrated Terminal. 

The user will then open insomnia, and look at the routes for products, categories, and tags. 

## Credits

Thank you to the contributors to npmjs.com for the necessary dependencies for this application.

Thank you to MDN Web Docs for the tutorial on routes, found here https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/routes.

## License
    
    This project is licensed under the MIT License. To learn more about this license, go to:
https://opensource.org/licenses/MIT 

## Questions

If you have any questions, please contact me at megan.mchugh@gmail.com.
For more of my work, please refer to my GitHub page:
[mchughmegan](https://github.com/mchughmegan/)

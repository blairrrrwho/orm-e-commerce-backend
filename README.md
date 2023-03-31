[![License:MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


# ORM E-Commerce Backend
Object-Relational Mapping (ORM): E-Commerce Back End


## Description
This is a MySQL database and application backend built for an e-commerce website. It was built using MySQL2, Express, Sequelize and dotenv.  
This project focused on routes and making changes to a MySQL database using POST, PUT, and DELETE requests, an e-commerce store would have a very similar backend structure.


## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Screenshots](#screenshots)
- [Technologies](#technologies)
- [License](#license)
- [Tests](#tests)
- [Credits](#credits)
- [Contact / Questions](#contact--questions)

## Installation
Clone the repo down onto your local machine. Open the project and make sure your terminal is in the project folder.  
Run 'npm i' in the CLI to ensure you have all the necessary packages installed. You also have the option of running an 'npm init' to personalize your project. 
You will also need to have MySQL already installed on your local machine.  
Log in to MySQL by using the command: 'mysql -u root -p'
When prompted, enter your password for MySQL. 
Create the database by using 'SOURCE db/schema.sql' in the MySQL shell.  
Finally, run 'npm run seed' to seed the database with default data.


## Usage (Instructions/How-To Use)
Run 'npm start' which will sync the database and start the server.


## Demo
Demo URL: <a href="https://vimeo.com/813422897">Full Video</a>


# Screenshots
Examples of each route  
![GET Route 1](./assets/Screenshot1AllCategories.png)  
![GET Route 2](./assets/Screenshot2CategoryByID.png)  
![POST Route](./assets/Screenshot3NewCategory.png)  
![PUT Route](./assets/Screenshot4UpdateCategory.png)
![DELETE Route](./assets/Screenshot5DeleteCategory.png)      


## Technologies
JavaScript, Node.JS, Express.JS, MySQL, Sequelize, dotnev.  


## License
This project is licensed under the MIT license. For more information about this license and what it entails, visit the MIT website <a href="https://opensource.org/licenses/MIT">here</a>


## Tests
The following program is needed to run tests: Insomnia.  
Endpoints were tested with Insomnia. Please refer to the demo video to see the tests in action.  
If you should find any issues, submit a issue with a detailed explanation on how to recreate the bug.


## Credits
Christina Hall and Terry Lequernaque. 


## Contact / Questions
  If you liked this project and want to see more, feel free to check out my other repos [here](https://github.com/blairrrrwho).  
  For any questions or inquiries, you can reach me at blair10324@gmail.com for further information.
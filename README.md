# Tech-Writers-Unite

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
I created a blogging app to give developers a platform to write, publish, and comment on articles. The app requires users to log in to view their user dashboard, view posts and comments, and add posts and comments. Users are also able to edit and delete their own posts.

This project was extremely challenging, partly because I was building this app completely from scratch, and partly because it was the first time I used Handlebars and fetch requests outside of small class activities. I was also writing my own routes for one of the first times.

Link to video demo:

![Preview image](./public/images/preview.png)

## Installation
1. Copy the SSH key in my GitHub repo and paste `git clone <SSHKEY>` in your terminal to create a local copy on your computer\
OR
2. Download the zip file and manually copy the files to your computer
3. Install node by copying and pasting the code `npm init -y` in your terminal
4. Run `npm i` to install the necessary applications 
5. Create a .env file with the following information, using your MySQL password:\
`DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='YOURPASSWORD'`

## Usage
1. Open the index.js file in your terminal\
*Note: Make sure you have the starter code copied first!
3. Run `npm run seed` to seed the files
4. Run `npm run start` to connect to the server
5. Click the 'login' button in the navigation bar
6. To log in, enter existing user information\
OR\
  sign up with a new account
7. Click on the 'Home' button to view all blog posts
8. Click on the 'Dashboard' button to create a new post or delete a post
9. Click the 'Delete' button next to one of your posts to delete it
10. Click the 'Logout' button to log out of your account

## Credits 
I created this app using JavaScript, CSS, Node.js, Express.js, SQL, Sequelize, and Handlebars.

- [Sequelize Validations](https://sequelize.org/docs/v6/core-concepts/validations-and-constraints/)
- [Sequelize many-to-many-relationships](https://sequelize.org/docs/v6/core-concepts/assocs/#many-to-many-relationships)
- [Sequelize advanced-many](https://sequelize.org/docs/v6/advanced-association-concepts/advanced-many-to-many/)
- [W3Schools modals](https://www.w3schools.com/howto/howto_css_modals.asp)

## License
MIT License

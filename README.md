So Yummy
So Yummy is a web application that allows users to search for recipes and save them to their profile. The application was built using React, Node.js, Express, and MongoDB.

Table of Contents
Installation
Usage
Technologies Used
Contributing
License
Installation
To run this application locally, you will need to have Node.js and MongoDB installed on your computer.

Clone this repository:

bash
Copy code
git clone https://github.com/romaniv2511/so-yummy.git
Install the dependencies:

bash
Copy code
cd so-yummy
npm install
cd client
npm install
Create a .env file in the root of the project and add the following variables:

makefile
Copy code
MONGODB_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
Start the server:

sql
Copy code
npm start
Open the application in your browser at http://localhost:3000.

Usage
To use the application, you will need to create an account or log in with an existing account. Once you are logged in, you can search for recipes using the search bar at the top of the page. Clicking on a recipe will take you to the recipe page, where you can view the ingredients and instructions.

To save a recipe to your profile, click the "Save" button on the recipe page. You can view your saved recipes by clicking on the "Saved Recipes" link in the navigation bar.

Technologies Used
React
Node.js
Express
MongoDB
Mongoose
Axios
JWT
Contributing
Contributions to this project are welcome. To contribute, follow these steps:

Fork this repository.

Create a new branch:

arduino
Copy code
git checkout -b my-new-feature
Make your changes and commit them:

sql
Copy code
git commit -am 'Add some feature'
Push to the branch:

perl
Copy code
git push origin my-new-feature
Submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

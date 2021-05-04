## Description

An SQL database using get post put and delete requests on an application.
  
 Below is the gif showing the functionality of the application:
  ![](https://raw.githubusercontent.com/ryokoba689/ecommerce-backeend/master/gifs/comgif.gif)



Link to the video as I was not able to upload properly as it may be too large it is in gif format and downloadable.
  
  ![](https://github.com/ryokoba689/ecommerce-backeend/blob/master/gifs/comvid.webm)
 
## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
## Acceptance Criteria
  
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
``
 
# Installation

  
npm init
npm i
run command
mysql -u root -p
Enter PW when prompted
source db/schema.sql
npm run seed
npm start



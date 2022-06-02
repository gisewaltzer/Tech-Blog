# Tech-Blog
    
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description
 * GIVEN a CMS-style blog site
 * WHEN I visit the site for the first time
 THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
 WHEN I click on the homepage option
 THEN I am taken to the homepage
 WHEN I click on any other links in the navigation
 THEN I am prompted to either sign up or sign in
 WHEN I choose to sign up
 THEN I am prompted to create a username and password
 WHEN I click on the sign-up button
 THEN my user credentials are saved and I am logged into the site
 WHEN I revisit the site at a later time and choose to sign in
 THEN I am prompted to enter my username and password
 WHEN I am signed in to the site
 THEN I see navigation links for the homepage, the dashboard, and the option to log out
 WHEN I click on the homepage option in the navigation
 THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
 WHEN I click on an existing blog post
 WHEN I enter a comment and click on the submit button while signed in
 THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
 WHEN I click on the dashboard option in the navigation
 THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
 WHEN I click on the button to add a new blog post
 THEN I am prompted to enter both a title and contents for my blog post
 WHEN I click on the button to create a new blog post
 THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
 WHEN I click on one of my existing posts in the dashboard
 THEN I am able to delete or update my post and taken back to an updated dashboard
 WHEN I click on the logout option in the navigation
 THEN I am signed out of the site
 WHEN I am idle on the site for more than a set time
 THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments

  ## Table of Contents 
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)
  
  ## Installation
  
  To install necessary dependencies, type the following command into the terminal:
  
  > npm init -y

  >npm i

  ## ScreenShot

  ![Screenshot](./public/assets/images/Screenshot-Tech-Blog.png)
  
  ## Usage

  Once the user has navigated to the homepage, they are given the option of logging in or signing up using their email address and password. Without signing up or logging in, the user is able to view blogpost history, but if they would like to add, delete or update posts or comments, they are prompted to log in or create an account. 
  
  ## Additional Information
  heroku deployment: type 'heroku open' on the Terminal. It will open the Note Taker App.
  URL from heroku: https://blog-jessie.herokuapp.com/
  
  ## License

  This project is licensed under the MIT license.  

 ## Contributing

  Pull requests are welcome. For any major changes, please open an issue first to discuss what you’d like to change. Please make sure to update tests as appropriate.

 ## Tests

 To run, type into bash terminal:
 > npm start

 ## Questions

 If you have any questions, please visit https://github.com/gisewaltzer or email me at gisewaltzer@gmail.com
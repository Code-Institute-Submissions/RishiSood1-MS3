# Milestone Project 3

This is my third project for Code Institute. I have created a movie reviews website which allows users to add their own reviews on movies they have seen. They are also able to view reviews added by other users.

The landing page consists of a search bar which allows users to search movies by name, genre and the year it was released. Also, on the landing page are all the other reviews which have been added on to the website. We have a login page which allows registered users to login into the website. There is also a sign-up page which is for any new users who are not registered to become a registered user. Once a user signs up, their username will be inputted into the database in the users table. Their password will be logged in the database, however using the [?] security feature, their password will not be shown. Once their details are in the table, this will allow users to login to the website. Once the user is logged in, the logout feature will appear in the navigation bar. The reason for this is because we don’t the logout feature to be in the navigation bar all the time, we only want it to appear once a user is logged in. Another feature that only appears when a user is logged in, is the add review feature. Once clicked, it will lead the user to the add review page. Once they have added the review, the data will automatically be inputted into the database and will appear on the landing page with the other reviews.

## UX

This project is for anyone with a love of movies. Users can create, read, update and delete reviews.

### User Stories

* As a movie critic I want to be able to add a new review about a movie. I also want to be able to update or delete my review if necessary. 
* As a person who watches movies, I want to be able to read reviews about upcoming movies.  
* As a person who is involved in the production of movies, I want to be able to see what other people think of the movie I have worked on. 

### Wireframes

## Features 

Navbar – The navbar appears at the top of the screen and all the page links are working. There is a login feature for existing members to sign into the website to add a review. There is also a sign up feature which allows non members to sign up to the website. We also have an add reviews feature, this is only available to users when they have logged into the website. The navbar isn’t fixed to the top of the screen so users will have to scroll back to the top of the screen if they want to use the navbar. When the website is viewed on smaller screen sizes, the navbar should turn into a drop-down list which it does. I tested the navbar on different screen sizes and it worked perfectly on every single one. 

Footer – The Footer appears at the bottom of each page. The social media links are all working, and it leads to my social media pages. In the footer, we also have an email address, this allows users to contact the creator of the page if they have any issues or questions. When the website is viewed on smaller screen sizes, the contents of the footer all stack up on each other and is centred. Similar to the navbar, the footer isn’t fixed to the bottom of the screen, so the users have to scroll back down to the bottom of the screen to view the footer contents. 


### Colours

The pages follow a standard colour scheme with only a few colours being used throughout the whole sight, the colours that were used are listed below:
* #00008B - Blue
* #FFFFFF - White

### Font

Throughout the website, I decided to use 1 font as I thought I would look better than having 2 -3 different fonts. The font I used was Exo as I believed It looked the best out of all the fonts. 

## Technologies Used

### Testing Tools 

I used the following validation services to validate my code:

* W3C Markup Validation Service 
* W3C CSS Validation Service

Both my CSS and HTML passed the validation service without any errors

<h4 align="center"><img src="Documentation/CssValidator.JPG"></h4>


### Testing Methods 

I used the following devices to test my website on smaller screen sizes:

* Samsung S20
* iPad Pro
* Samsung S10

I then used the developer tools on Google Chrome to test the website on different devices. The devices I tested the site on are as follows:

* iPhone X
* iPad
* Moto G4

## Credits

### Content 

* The fonts were used from Google Fonts
* The navbar and form elements were used from bootstrap

### Media

* The images are all free to use images. 

### Acknowledgments 

* The inspiration behind this project was loosely based on the backend development mini project that I created while completing the backend development module.
* I received advice from my mentor Aaron Sinnott
* I also received help from the Code Institute tutoring team who helped me when I had errors which I could not fix myself

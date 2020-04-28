YelpCamp

    A Node.js web application.

Features

    Authentication:

        User login with username and password

        Admin sign-up with admin code

    Authorization:

        One cannot manage posts and view user profile without being authenticated

        One cannot edit or delete posts and comments created by other users

        Admin can manage all posts and comments

    Manage campground posts with basic functionalities:

        Create, edit and delete posts and comments

        Upload campground photos

        Like and comment on campgrounds

        Search existing campgrounds

    Manage user account with basic functionalities:

        Password reset via email confirmation 

        Profile page setup with sign-up

    Flash messages responding to users' interaction with the app

    Responsive web design

Custom Enhancements

    Update campground photos when editing campgrounds

    Update personal information on profile page

    Use Helmet to strengthen security

Getting Started

    This app contains API secrets and passwords that have been hidden deliberately, so the app cannot be run with its features on your local machine. However, feel free to clone this repository if necessary.

Clone or download this repository

git clonehttps://github.com/aiman-mumtaz/yelp-camp.git

Install dependencies

npm install

or

yarn install

Comments in code

Some comments in the source code are course notes and therefore might not seem necessary from a developer's point of view.
Built with
Front-end

    ejs
    Bootstrap

Back-end

    express
    mongoDB
    mongoose
    passport
    passport-local
    express-session
    method-override

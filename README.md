
# TourCamp

TourCamp is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account. 

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.


## Features

- Authentication
    - User can register and login
    - Used Passport for that purpose
- Authorization
    - User needs to be logged in to make any change(add,update or delete)
    - A user can only alter his posts or reviews
- Functionalities
    - Campgrounds are marked on a cluster map using Mapbox API
    - Search any Campground
    - Images of campgrounds are uploaded to Cloudinary
    - Images can be added and deleted after creation of Campground
    - CRUD functions have been implemented on Campgrounds
    - Flash messages were displayed
    - Sessions and cookies were used
    - Every Campground has it's location displayed seperately on a map
    - Create & Delete Reviews for Campgrounds
    - Rate Campgrounds
    - User Authentication
    - Manage Campgrounds you Post


## Demo

https://still-atoll-14540.herokuapp.com/

## Stack
- Front End
    - HTML, CSS, Bootsrap 
    - EJS
- Back End
    - NodeJS , ExpressJS
    - MongoDB
    - cloudinary
    - MapBox
    - passport(local-strategy)
    - JOI
    - connect-flash
    - sessions
    - Nodejs, Express


## Authors

- [Suraj Verma](https://www.github.com/surajverma8787)


## Feedback

If you have any feedback, please reach out to us at surajverma8787@gmail.com



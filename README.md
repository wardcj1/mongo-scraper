# mongo-scraper

![ScreenShot](/public/images/ss002.gif)

## Live Link
 - https://wardcj1.github.io/mongo-scraper

## Overview

A web app that lets users leave comments on the latest news. The app scrapes articles from another site. Whenever a user visits the site, the app will scrape stories from a news outlet. The data includes a link to the story and a headline. Cheerio is used to grab the site content and Mongoose to save it to MongoDB database. All users can leave comments on the stories collected. Users are also allowed to delete whatever comments they want removed. All stored comments are visible to every user.

## Technologies Used:
* MongoDB
* Heroku

npm packages:
* express
* express-handlebars
* mongoose
* body-parser
* cheerio
* request
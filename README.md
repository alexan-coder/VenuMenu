## VenuMenu App

Don't forget to add a readme that includes an app description, a link to an ERD, the technologies you used to build the app, and instructions to install the app from scratch

## Description

VenuMenu is a web app that allows users to search venues by name or location. The data is pulled from the Songkick API. Once a user searches a venue VenuMenu provides results including the name, address, telephone number and a link to the venue website. The web app allows the user to sign in/up with twitter which opens up new features. 

## User Stories

User can sign up / sign in with Twitter account
User can search Venues by name
User can comment on Venues with a description of their opinion

## Technologies

Ruby 2.1.2
PostgreSQL Database
OmniAuthorization
Rails
Javascript
HTML
CSS
JQuery
Adobe Photoshop
Adobe Illustrator
Songkick API
After effects


## What's next?

Upvoting and downvoting to rate venues 
Clickable venues to take the user to a page for that particular venue
use the map box api to link to the Songclick API and get the latitude/longitude to display a map 
upcoming events on individual venue page
possible yelp rating next to the venue name

## Set Up

bundle install
bundle exec rake db:create
bundle exec rake db:migrate

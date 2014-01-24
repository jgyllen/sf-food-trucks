## SF Food Trucks

This is a simple web app that serves as an experiment in integrating with the [Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript/). It allows a user to search for food trucks in San Francisco and display the results on a map.

You can see the app running [here](http://sfft.herokuapp.com/).

### Data

The food trucks data was taken from [DataSF](http://www.datasf.org/).

### Tech

The app uses the following technologies:
* Bootstrap
* HAML
* jQuery + Backbone.js
* Sinatra

### Installation

You need Ruby 2.1.0 and Bundler.

1) Clone git repo

2) Install gems:

    $ bundle

3) Start app:

    $ bundle exec rackup -p 4567

4) Visit http://localhost:4567

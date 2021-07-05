## Welcome to RoTech Official Website 
This Website is hosted using GitHub Pages. You can also Join the Rotech [GitHub Org]() , and Contribute to our latest opensource projects. You can also Add Events, Projects, Your Organization or Company Free Sponsor for the Webinars, Event and Projects . 
## Adding a Single Event to Rotech Official Website
go to the `_events` folder and inside the folder create an file for example `test.md` . inside the test.md file add the following details 

``
---
facebook_id:
title: 
start_time: 'yyyy-mm-dd hh:mm'
end_time: 'yyyy-mm-dd hh:mm'
location: 
actions:
  - label: Tickets
    url: 'TICKET URL'
---
You can also add more details of your event here.
``

## Adding a Series Event

# Setup

### 1. Install Ruby & Node

#### Mac OS X

Install [brew](http://brew.sh/) if you don't have it, and then install Ruby & Node by running:

```
brew install ruby node
```

#### Windows

You can download Node.js [here](https://nodejs.org/en/) and Ruby [here](http://rubyinstaller.org/downloads/).
Make sure that it's working by testing whether you have command line access to ```npm``` and ```gem```.

### 2. Clone this repository

Go to the directory you want this project to be in (can be anywhere) and run:

```
git clone https://github.com/techsoc/website-2015.git
```

### 3. Install Jekyll

In order to keep our Jekyll version in sync, we'll be using [bundler](http://bundler.io/). Install it by running:

```
gem install bundler
```

Then cd to the website folder and run:

```
bundle install
```

..which will install all Ruby dependencies.

### 4. Install Gulp

Gulp will help fix our CSS by adding all vendor prefixes as well as regenerate the site whenever changes are made. Install it by cd'ing to this project and running:

```
npm install && npm install -g gulp
```



## Modifying HTML

**Never edit anything in the `_site` folder.** It is autogenerated & will overwrite your changes.



## Feedreader portfolio project

In project #6 of udacity's Frontend Nanodegree you are given a web-based application that reads RSS feeds and are tasked with writing a test suite for the app.

### Libraries, frameworks and APIs used

* Jasmine
* Jquery


### Getting started

1. Clone the repository

  ```bash
  $ git clone https://github.com/WarrenAdams/feedreader-testing

  ```

1. Run a local server for the project in the dist folder.

  ```bash
  $> cd /feedreader-testing
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080


#### Project Requirements and Features

* Write a test that loops through each feed in the `allFeeds` object and ensures it has a name and url defined and that the name and url is not empty.

* Write a test that ensure the menu is working as expected.

* Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

* Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

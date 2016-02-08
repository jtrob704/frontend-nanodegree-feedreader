# Project Overview

This application performs 7 Javascript tests on a RSS feedreader using the Jasmine testing framework. You can learn more about the Jasmine testing framework here: http://jasmine.github.io/

Jasmine tests in this application:

A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
A new test suite named "The menu".
A test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
A test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. Remember, loadFeed() is asynchronous so this test wil require the use of Jasmine's beforeEach and asynchronous done() function.
A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes. Remember, loadFeed() is asynchronous.

## How to run the application

To run the application you can download the repository ZIP and open the index.html in your favorite web browser. The tests will run and the results will be displayed at the bottom of the page.

If you would prefer not to download the repository you can visit a live version of the application here: http://jtrob704.github.io/frontend-nanodegree-feedreader
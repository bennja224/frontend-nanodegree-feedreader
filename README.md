# Project Overview

This project was to create tests using Jasmine for a RSS feed reader in the Udacity Frond-End Nano Degree (FEND).

[Jasmine](http://jasmine.github.io/) 

## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". 

This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!


## What I learned?

How to write test cases using a pre-existing application and explored the Jasmine spec file in **./jasmine/spec/feedreader.js.  

## How to run?
Launch index.html from https://github.com/bennja224/frontend-nanodegree-feedreader/blob/master/index.html

Any questions please let me know. 


# How I completed this project?

* Reviewed the Feed Reader Testing [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric)
* Reviewed the functionality of the UdaciFeeds application
* To understand how the application worked I explore the application's HTML (**./index.html**), CSS (**./css/style.css**) and JavaScript (**./js/app.js**) 
* Explore the Jasmine spec file in **./jasmine/spec/feedreader.js** and review the [Jasmine documentation](http://jasmine.github.io).
* Edited the `allFeeds` variable in **./js/app.js** to make the test fail, refreshed index.html to visualize the failure and then returned the `allFeeds` variable to a passing state.

* Wrote 7 tests ensuring that they are not dependent on each other:
** RSS Feeds 
Test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
Test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.

** The menu
Test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
Test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.

** Initial Entries
Test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

** New Feed Selection
Test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.



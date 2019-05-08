# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development." This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!


## What I  have learnt?

I have learnt how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.


## How will this help my career?

Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.

Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.


# Development Strategy

For a refresher (or reference) before you begin writing code, I recommend reviewing the content from [JavaScript Testing](https://www.udacity.com/course/javascript-testing--ud549). My project will be evaluated by a Udacity code reviewer according to the [Feed Reader Testing project rubric](https://review.udacity.com/#!/rubrics/18/view). Please review for detailed project requirements.

1. I have read the starter code very carefully
    * Opened up `index.html` and review the functionality of the application within browser
    * Read the code in `app.js` and also read all code comments
    * Checked out `style.css` and styling applied to the application
2. Explored the Jasmine spec file in `feedreader.js`
    * This is the file in which I have written tests
    * read all code comments here as well
    * Review the [Jasmine documentation](http://jasmine.github.io) if needed
3. Edited the `allFeeds` variable in `app.js` to make the provided test fail
    * Seen how Jasmine visualizes this failure in my application
    * Return the `allFeeds` variable to a passing state after reviewing the failed test
4. Written a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined _and_ that the URL is not empty
5. Written a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty
    * Check the previous test and compare with this one.
6. Written a new test suite named `"The menu"`
    * Applied specs and suits for the menu and directly we get the class name from the html code with thw help of $ function.
7. Written a test that ensures the menu element is hidden by default
    * I have to analyzed the HTML and the CSS to determine how the hiding/showing of the menu element is implemented.
    * Code in `app.js` and menu-hidden is declared to be false first and then after clicking changes to be true.
8. Written a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display itself when clicked, and does it hide when clicked again?
    * Compare the code with the previous test code.
9. Written a test suite named `"Initial Entries"`
    * Loadfeed is asynchronous so I have used Jasmine's beforeEach , done function and assigned 0 to the loadfeed.
10. Written a test that ensures when the `loadFeed` function is called and completes its work, the length should be at least a single `.entry` element within the `.feed` container
    * Jasmine's `beforeEach()`function is called once before each spec in the describe in which it is called.
    * `loadFeed()` function in `app.js` is asynchronous and 0 is loaded to declare as initial.
11. Written a test suite named `"New Feed Selection"`
12. Written a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes
    * Declare two variables, assign loadfeed 0 as before for first variable, assign .feed class data from html and compare with second variable assign loadfeed 1 ,if equals then done is successfully worked.

Additionally, note that:

 * No test should be dependent on the results of another
 * Callbacks are used to ensure that feeds are loaded before they are tested
 * Error handling is implemented for undefined variables and out-of-bound array access
 * When completed, all of my tests are passed
 * So I have successfully completed my test cases.

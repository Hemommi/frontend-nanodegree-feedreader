# Front-End Web Developer Nanodegree Udacity
## Project: Feed Reader Testing

All tests are placing within $() function. Some of tests requires DOM elements.

### Steps required to successfully run the applications:
1.  Download all files.
2.	Run index.html in your browser.
3.	RSS Feeds – first test. It tests to make sure that the allFeeds variable has been defined and  it’s not empty.
a)	Test loops through each feed in the allFeeds object and ensures it has an URL defined and that URL is not empty.
b)	Test loops through each feed in the allFeeds object and ensures it has a name defined and that name is not empty.
4.	Test suite – The Menu.
a)	Test that ensures the menu element is hidden by default.
b)	Test that ensures the menu changes visibility when the menu icon is clicked. Test has two expectations: menu display when clicked and hide when clicked again.
5.	Test suite – Initial Entries.
a)	Test that ensures when the loadFeed function is called and completes its work. There is at least single .entry element within .feed container. Test requires the use of Jasmine’s beforeEach and asynchronous done() function.
6.	Test suite – New Feed Selection. Test ensures when a new feed is loaded by the loadFeed function that the content changes. Test requires the use of Jasmine’s afterEach function. 


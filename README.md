
# Udacity Feed Reader Testing

In this project you are given a web-based application that reads RSS feeds.

## Getting Started

Click [here](https://nivax07.github.io/feed-reader/) to play the live version.
OR
You can clone this repo by typing

```
https://github.com/Nivax07/feed-reader.git
```

## Tests uses jasmine-3.1.0

1. A test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.

2. A test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.

3. A test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.

4. A test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.

5. A test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

6. A test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

# feed-reader	


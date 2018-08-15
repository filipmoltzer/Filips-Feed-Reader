# Feed Reader Testing Project using Jasmine test

### In this project I have used Jasmine to write test suites which control that the code is correct

### **Usage**:
1. Clone/download the git repository
2. Navigate to your local copy of the index.html via your web browser
3. To start with, there are no errors in the test so jasmine will have no red bars in the bottom of the site.
4. Test the jasmine specs by edit the app.js, example:
-  **URL is defined & not empty**: Remove the url content inside the allFeeds array and refresh website.
-  **name is defined & not empty:** Remove the name content inside the allFeeds array and refresh website.
- **Menu is hidden by default:** Delete the .menu-hidden class from the index.html and refresh website.
- **Feed container contains entry element:** Delete the .entry class from the index.html and refresh website.
- **Content changes when new feed is loaded:** Edit the loadFeed functions id parameter in feedreader.js to be the same and refresh website.

5. Restore order by undo the code you have edited and all the specs will pass again.

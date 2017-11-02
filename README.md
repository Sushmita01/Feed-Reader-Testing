## Feed Reader Testing


In this project we have a web-based application that reads RSS feeds. Using the Jasmine library, I have written several test modules which check whether the website is functioning as its supposed to without any human intervention.

### Steps required to run the application:
 1. Download the zip file of the gitHub repository 
 2. Save the file locally somewhere and run index.html from your browser
 3. The test results are loaded at the bottom of the website

### Tests present

1. RSS Feeds
   - are defined
   - has URL defined and URL is not empty
   - has name defined and name is not empty
2. The menu
   - is hidden by default
   - changes visibility when clicked
3. Initial Entries
   - should have atleast single entry element
4. New Feed Selection
   -  changes content

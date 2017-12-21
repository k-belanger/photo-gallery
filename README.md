# Slack Photo Gallery Challenge
December 21, 2017

## Project Objective:
Create a web page that shows a grid of photo thumbnails; when a thumbnail is clicked, the photo should be displayed in a lightbox view,with the ability to move to the next / previous photos and display the photo title. You can use any public API that returns photos


## What I did:
- Created a fully responsive photo gallery with lightbox.
- The photo gallery is built using pure JS, no jQuery or other libraries / frameworks.
- Gallery uses the flickr api for images.


## Next Steps I would have taken had time allowed:
- Remove the lightbox overlay from the DOM and create, insert and display it dynamically when it was active via JavaScript instead.
- Create configuration settings so user could easily customize gallery by setting flickr gallery ID and number of images to display without having to update JS file
- Loop through the photos continuously in lightbox. Once you reach the last photo, instead of removing the next button the next button would take you back to the first photo in the series.
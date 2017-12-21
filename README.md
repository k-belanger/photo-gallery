# Slack - Photo Gallery Challenge
December 21, 2017

## Project Goal:
Create a web page that shows a grid of photo thumbnails; when a thumbnail is clicked, the photo should be displayed in a lightbox view,with the ability to move to the next / previous photos and display the photo title. You can use any public API that returns photos


## What I did:
- Created a responsive photo gallery with a lightbox.
- The photo gallery is built using plain JavaScript with no assistance from any other frameworks or libraries.
- The photo gallery uses the Flickr api for images.
- Tested in the latest versions of Chrome, Safari, Firefox and Edge


## A few enhancements I would make time permitted:
- Remove the lightbox overlay from the DOM and instead, create, insert and display the overlay dynamically when it is active via JavaScript.
- Create a configuration settings object to be inserted in the HTML file which would allow the user to configure the gallery by setting the Flickr gallery ID and the number of images to display without having to update the JS file.
- Ability to loop through the photos continuously in the lightbox. For instance, once you reach the last photo, instead of removing the next button the next button would take you back to the first photo in the series.
- Tested in and adapted for older browser support.
# Horiseon

## Purpose
Showcase Horiseon's services and benefits within accessibility guidelines and with refactored CSS.

Changes and optimizations included:
* Re-ordered CSS to follow the flow of HTML semantic elements
* Removed the Hero image from CSS and added it to index.html with an alt attribute for improved accessibility
* Updated .hero class to access the .hero img and make it fit to the screen the same way the previous css rules did
* Added the semantic elements "header" and "article" for e-readers to easily identify page content (https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)
* Changed the class "content" to "services" for improved accessibility and to match the benefits section
* Removed unncessary classes and refactored them under the "service" class
* Added some CSS comments to help with code readability; separated headers, footers, and body text with comments
* Added comments to explain the need for the additional .float-left and .float-right classes
* Added a <title> tag to give a more descriptive page title for improved accessibility
* Added null alt attributes to images in the services and benefits sections to denote that they are decorative images (reference: https://www.w3.org/WAI/tutorials/images/decorative/#:~:text=In%20these%20cases%2C%20a%20null,from%20that%20in%20adjacent%20text)

## Screenshot

![Screenshot](https://github.com/powerar/horiseon/blob/main/screenshot.jpg?raw=true)

## Built With
* HTML
* CSS

## Website
https://powerar.github.io/horiseon

## Contribution
Made with ❤️ by Andrew Power

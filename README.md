# How to Vist The Netherlands
---
# User Experience (UX)

* ## User Stories
    * First time visitor goals
        1. Gain a basic background on the country
        2. Discover cities they might not have heard of
        3. Discover attrations and places to visit in the cities
        4. Be able to find the places on a map

    * Returning visitor goals
        1. Find addresses for recommended places quickly and easily
        2. Find maps for navigation
        3. Be able to provide feedback on places they have visited
        4. Give recommendations
        5. Find new cities through either the ones currently on the site or through future updates

    * Frequent visitor goals
        1. Check to see if there are any new cities
        2. Check for any new activities
        3. Provide feedback and recommendations

* ## Design
    * Colour Scheme
        * The main colour theme is orange, this is the Dutch colour. I used [HTML Color Codes](https://htmlcolorcodes.com/) to create a shade of orange which was user friendly but also sticking to the theme
    * Typography
        * The font used for the site was imported from Google Fonts. I chose Roboto Condensed for a modern, easy to read style with Sans-serif as a fallback.
    * Imagery
        *

* ## Wireframes
    * Mobile Wireframe - [Link](https://imgur.com/a/jJWagMW)
    * Tablet Wireframe - [Link](https://imgur.com/a/DBMiehy)
    * Desktop Wireframe - [Link](https://imgur.com/a/UZnnQt6)

---
# Features

* Responsive on all devices

---
# Technology Used

## Languages Used
[HTML5](https://en.wikipedia.org/wiki/HTML5)
--
[CSS3](https://en.wikipedia.org/wiki/CSS)

## Frameworks, Libraries & Programs Used
1. [Visual Studio Code](https://code.visualstudio.com/)
    * Visual Studio Code was used to complie the code to complete the website.
2. [Balsamiq](https://balsamiq.com/)
    * Balsamiq was used during the design process to create the Wireframes
3. [Jira](https://www.atlassian.com/software/jira)
    * Jira was used to create a sprint to aid the development on the project
3. [Git](https://git-scm.com/)
    * Git was used for version control
4. [Github](https://github.com/)
    * Github is used to store the code
5. [Bootstrap 5.3](https://getbootstrap.com/)
    * Bootstrap was used to assist with the styling and responsivness of the site
6. [Font Awesome](https://fontawesome.com/icons)
    * Font Awesome was used to add styling to the site through icons
7. [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/)
    * Chrome Dev Tools was used to debug minor issues and as an aid when styling the website
8. [Hex Color Codes](https://htmlcolorcodes.com/)
    * Used to provide color codes for the website
9. [Google Fonts](https://fonts.google.com/)
    * Used for the typography for a modern but easy to read design
10. [RGBA Color Picker](https://rgbacolorpicker.com/)
    * RGBA Color Picker was used to convert the orange hex code to allow me to change the opicity of the header and footer

---
# Testing

The W3C Markup Validator and the W3C CSS Validator were used to validate the code and ensure that there were no syntax errors in the project. No errors were found.

* [W3C Markup Validator](https://validator.w3.org/)
* [W3C CSS Validator](https://validator.w3.org/)

* Google Dev Tools was used to check responsive design
    * Form input was not responsive
        * [W3 Schools](https://www.w3schools.com/howto/howto_css_responsive_form.asp) guide was used to fix this

* [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/) was used to check performance
    * index.html
        * 95 performance
        * 90 Accessibility
        * 95 Best Practices
        * 100 SEO
    * rotterdam.html, utrecht.html and dordretcht.html
        * 98 performance
        * 90 Accessibility
        * 95 Best Practices
        * 100 SEO
    * gallery.html
        * 71 performance
        * 92 Accessibility
        * 100 Best Practices
        * 100 SEO
    * contact.html
        * 97 performance
        * 93 Accessibility
        * 100 Best Practices
        * 100 SEO

* Devices used to test
    * Desktop/Laptop
        * 16" laptop
        * 32" widescreen monitor

    * Tablet Devices
        * Samsung Galaxy Tab S6
        * Samsung Galaxy Tab A8

    * Mobile Devices
        * Samsung Galaxy S21FE
        * Samsung Galaxy S23 Ultra

---
# Bugs

## Known Bugs

### Gallery Page
* The performance score of 71 is low, further development of this is required.[dotcom-tools](https://www.dotcom-tools.com/website-speed-test) was used to test the loading speed. The average load time is 1.33 seconds, this feels acceptable until the next update.

## Fixed Bugs

### Header Section
* I wanted to impliment a Bootstrap navigation snippit which would ensure the navigation bar is responisve for mobile and tablet and also due to the city name sizes the hamburger menu suits smaller devices better as it looks much cleaner and is far more user friendly. 
    * Bootstrap navigation templates fills the full width of the screen so I customised their recommended code snippet to suit the needs of this website.
    * The hamburger icon was placed to the left of its container so I used google dev tools to inspect the area and find the section of Bootstrap which needed overiding.
    * The hamburger menu icon was defaulted to black, to change this to white I had to change the Bootstap nav bar theme to dark and then overide the background colour.

### Footer Section
* I styled the footer to stick to the bottom of the page and be responsive to all devices sizes. Once I added my main content using Bootstrap grid the footer moved up the page and was stuck under the Bootstrap columns. To fix this issue I refered to 'CSS Secrets. Better Solutions to Everyday Web Design Problems' by Lea Verou (Page 290 - 291)

---
# Credits

## Code

* Navigation section
    * [Bootstrap documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/) as a guide for making the responsive navigation bar

* Carousel (Gallery Page)
* [Bootstrap 5](https://getbootstrap.com/docs/5.3/components/carousel/) was used for the gallery page

* [W3 Schools](https://www.w3schools.com/)
    * Used throughout the project to trouble shoot

* [Stack Overflow](https://stackoverflow.com/)
    * The forum was used throughout the project to trouble shoot

* [CSS Secrets. Better Solutions to Everyday Web Design Problems by Lea Verou](https://www.oreilly.com/library/view/css-secrets/9781449372736/)
    * This book was refered to for support during my project

* [Duda](https://blog.duda.co/responsive-google-maps-for-your-website)
    * This blog was used to help with the responsive design of Google maps

* [Adobe Community Forum](https://community.adobe.com/t5/dreamweaver-discussions/setting-embedded-youtube-videos-to-fill-the-screen-on-any-resolution-with-media-queries/m-p/10459087)
    * Used for CSS snippet to make Youtube iframe responsive

## Content

* All content was written by the developer

## Media

* [Wallpaper Abyss](https://wall.alphacoders.com/tag/netherlands-wallpapers)
    * Wallpaper Abyss was used for the background image

* [Pit YouTube Channel](https://www.youtube.com/watch?v=aFJ1fPIhJAY)
    * 4k cinematic video used on the homepage

* [Google Maps](https://www.google.com/maps)
    * Used to show a city map on each city page



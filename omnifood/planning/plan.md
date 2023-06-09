# Omnifood Plan

## Step 1: Define Goals

* Goal of Project: Show what Omnifood does, how it works, and in which cities it operates in. Then, make people sign up on a subscription plan.
* Audience: Busy peple who don't have time to co ok or don't like it. 
    
## Step 2: Plan

One--page webpage containing infoormation provided by Omnifood, with simple navigation.

* Content: provided by Omnifood in form of text document and a couple of images.
* Navigation: Also provided by Omnifood in a text document.

## Step 3: Sketch

![Header](Section0.png)

![Features](Section1.png)

![Favorite Meals](Section2.png)

![How it Works](Section3.png)

![Cities](Section4.png)

![Customer Testimonials](Section5.png)

![Signup Form](Section6.png)

![Contact Form](Section7.png)

![Footer](Section8.png)

## Step 4: Design and Develop Website

* Pick Colors and Fonts

    ![Main Color](color.png)

    ![Font](font.png)
    
* Code project --- see files in the repo: `build-responsive-real-world-websites-with-html5-css3/omnifood`
    * **resources folder** is for content created by us, **vendors folder** is for provided content from the customer
    
### Coding Sections

text content in: `../../provided_course_files/omnifood/contents/omnifood-content.docx` (also pages and rtf formats)

#### Section 0: Header

Learn:
* put text on an image
* make image darker
* make image as high as the browser viewport
* make a vertically and horizontally centered box
* design buttons
* the 4 link states in CSS: link, visited, hover, active
* CSS3 transitions for small animations
* create simple navigation

#### Section 1: Features

Learn:
* put content on a website directly from CSS with the `:after` pseudo-class
* use fluid-grid
* use icons

#### Section 2: Meals

Learn:
* make grid of images
* do a 'zoom-in' transition using only CSS
* make `<img>` elements darker

#### Section 3: How-it-works

Learn:
* draw circles with CSS
* new technique to make separations between sections
* incorporate App Store and Play Store buttons

#### Section 4: Cities

Learn:
* use small icons aligned with text
* style generic links

#### Section 5: Customer Testimonials

Learn:
* create a new background-image effect
* effectively communicate what customers have to say

#### Section 6: Sign-up 

Learn:
* design with border radius
* create box shadows with CSS

#### Section 7: Contact

Learn:
* HTML elements to create forms: form, label, input, select, option, textarea
* how to style these various elements

#### Section 8 : Footer

* Note: in a more complicated website, the footer usually repeats the main navigation ---  but not necessary in our case

Learn:
* build simple footer
* use social icons

#### Make Page Responsive with Media Queries

* breakpoints can be at standard screen sizes OR at nearby points where the design starts to look bad

![Screen Breakpoints](breakpoints.png "Screen Breakpoints")
(sizes for iPhone and iPad from 2015)

#### Consistent Browser Appearance

* each browser renders HTML and CSS slightly differently
* view on multiple browsers to check/test
* use CSS browser prefixes to make CSS3 appear the same in every browser
     
     ![Browser Prefixes](browserPrefixes.png "Browser Prefixes")
     
     * Note: in Brackets, use autoprefixer extension: `Edit -> Auto prefix selection`
* JS scripts for older browsers     

#### jQuery for Effects

* [Magnific Popup](https://dimsemenov.com/plugins/magnific-popup/)
* [Tooltipster](https://www.heteroclito.fr/modules/tooltipster/)
* [Maplace.js](http://ch-ny.com/content/themes/bridge-child/js/libs/maplace.js/)
* [Typer.js](https://steven.codes/typerjs/)
* [One Page Scroll](http://peachananr.github.io/onepage-scroll/Demo/demo.html)

Learn:
* sticky nav
    * uses [Waypoints](http://imakewebthings.com/waypoints/) to trigger the sticky nav when scrolling
* scrolling to elements
* add animations on scroll
    * uses [Animate.css](https://animate.style/)
* making the nav responsive

#### Favicon

* used [Favicon Generator](https://realfavicongenerator.net/)

## Step 5: Optimization

Basic things we will do:
1. optimize heavy images
    * change the image dimensions
        * make sure to find the image size when it is its largest size due to the site being responsive
        * if not inspecting on a high resolution screen, size the image twice as big to account for that
        * can resize easily in preview on a mac
        * [Optimizilla](https://imagecompressor.com/)
2. minify CSS and jQuery code
    * this removes comments and white space, making it very hard to read --- so only do as a final step before launching
     site
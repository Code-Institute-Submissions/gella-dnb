THE PROJECT:

WHAT IS IT?
Build a front end website website for a 1960's rock band or a similar idea of your own. For this project, I have chosen to build a website for a Jungle / Drum and Bass artist named Gella. Gella is a friend of mine and has had alot of success in the last couple of years.

BRIEF:
Primary target audiences are Jungle / drum and bass fans and potential fans who wish to hear music by Gella and to
Use the site to access his music and publicise upcoming gigs, and to contact Gella to enquire about performing, remixing and collaberations.
The following assets to be showcased on the website:
Photos
Audio clips (via Soundcloud)
Links to Facebook, soundcloud and instagram etc.

PURPOSE OF WEBSITE
Based on the brief, the aim of the website (in both functionality and design) was produce a functional website that essentially showcasws Gellas music and live dates to current and new fans.

The initial stages
Intially I researched Gellas social media and spoke to him in person I also looked at other drum and bass artists websites, to help me build a picture of the audience I was targeting, as well as help me create a "story" for the purpose of the site.
The site needs To be the equivolent of 5 pages
sketched ideas for a simple multi-page layout to get the basic components in a clear minimal format. 
draft up rough ideas of content in wireframe program and settled on a final design. (Balsamic wireframe included: /assets/Gella.bmpr)

The following decisions were made to start the site:

Page layout
The basic multi page layout seemed to fit the minimal solution of for presnting the music and live dates contact form in an easy and workable fashion for the user as it followed basic conventions of a website.
The simpleness of the design also suited it to responsive design, nothing would need to be taken out to fit on smaller devices.
I kept with minimal design, with striking images and minimal writen content.

Colours and Fonts
I wanted to keep the header footer and background a monochrome darker grey and used coolors.co to match vivid contrasting colours for different sections.I used a plain white for the text and kept the same font throughout apart from one element of the footer. The simpleness and minimalness of the design seemed to match the general theme for Electronic music websites and I wanted to keep that feel.


Navigation:
I decided on fixed navigation to ensure that the nav links were always visible, making the site intuative to navigate. The footer was not fixed to allow as much content to be displayed without scrolling.

Home page:

I liked the idea of using a slideshow to introduce the website, The simpleness of the nav bar, brand logo, footer and striking images, that are also links.


Music:
I chose to use embed music from Gellas Soundcloud page, It offered a clean interface with images and playlists which included remixes and Gellas own music. It is also a nice link to Gellas sound cloud page to explore his music further.


HOW IT WAS BUILT
The main framework in building the Gella site was Bootstrap V4.1.
Icons for social media were from Font Awesome.
Fonts were Google Fonts.

Plugins:

https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" 
https://code.jquery.com/jquery-3.3.1.slim.min.js" 
https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" 
https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" 
https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" 

Resources:

https://getbootstrap.com/
https://www.w3schools.com/
https://stackoverflow.com/
slackbot Forums
https://coolors.co/

Code/Framework Used Per Section

Navigation = Bootstrap Navbar

Carousel = Bootstrap (with help from stackoverflow to fix responsiveness of pictures)

About section

Bootstrap Grid system

Music:
iframes from soundcloud organised using Bootstrap grid system

Tour:
container with background image
Basic bootstrap table

Contact:

Bootstrap form and grid system

Footer:

Bootstrap grid system.
Font awesome for social links and Code institute for icon borders and code
ASCII code for Copyright (thank you mentor!)

Fonts throughout courtesy of Google fonts (https://fonts.googleapis.com/css?family=Montserrat|Shadows+Into+Light)

HOW IT WAS TESTED
Summary
I primarily tested the site as it was built through google chrome and the google chrome devTools and the device toolbar for responsviness 
AND also tested it physically viewing it on mobile, tablet, mac and windows laptop, windows desktop, and different browsers (firefox, safari, google chrome, opera)
What was tested
External links (to social media, particulalry music)
Internal links (Navbar links worked accordingly)
Contact form for enquiries
Container margins did not overflow, and each page started undee the nav bar, and each grid filled its relevent section and moved responsivly.
Checked images to ensure they were responsive and displayed appropriately on smaller screens
Ensuring drop down menu and burger icon worked for navigation on smaller devices (needed to ensure JS script in head)
Ensure content was straight tand to the point and easy to read.
Make sure soundcloud iframes were being responsive and displayed properly.
HTML and CSS validation via w3.org.

ISSUES ENCOUNTERED PRIOR TO DEPLOYMENT:
The Carousel would distort / stretch images on smaller screens. After consulatation with Mentor and using forums I found that I had fixed the height of the picture in pixels. The solution was to re-do the images dimensions in an imaging editing program and set height to 100%, in this way they all remained the same size and reduced in proportion for smaller devises.
To make the site more minimal I originally intened the navigation menu to slide out from the right hand side when you hovered over a menu button. I could not get this to stay in a fixed navigation bar and it was not responsive so favoured the static navigation menu.

DEPLOYING THE WEBSITE:

Website deployed on Github.
Tested the final published version in the same manner as I documented above in the How It was Tested section
Issues Encountered:

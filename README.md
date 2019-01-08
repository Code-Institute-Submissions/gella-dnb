# THE PROJECT

Build a front end website website for a 1960's rock band or a similar idea of your own. For this project, I have chosen to build a website for a Jungle / Drum and Bass artist named Gella. Gella is a friend of mine and has had alot of success in the last couple of years.

## Brief

Primary target audiences are Jungle / drum and bass fans and potential fans who wish to hear music by Gella, to find out about upcoming gigs and to contact Gella to enquire about performing, remixing and collaberations.
The following assets to be showcased on the website:
Photos
Audio clips (via Soundcloud)
Links to Facebook, soundcloud and instagram etc.

## Purpose

Based on the brief, the aim of the website is to produce a functional website that showcasws Gellas music and live dates to current and new fans and to provide a means to contact him.

It was also decided that the about section would include basic information on the tools Gella uses to make music as this was of interest to fellow electronic music fans. 

### The initial stages

Intially I researched Gellas social media and spoke to him in person I also looked at other drum and bass artists websites, to help me build a picture of the audience I was targeting, as well as help me create a "story" for the purpose of the site.
The site needs To be the equivolent of 5 pages
I started by drawing ideas for a simple multi-page layout to get the basic components in a clear minimal format. 
I then drafted up rough ideas of content in a wireframe program and settled on a final design. (Balsamic wireframe included: /preperation/Gella.bmpr)

The following decisions were made to start the site:

### Page layout

The basic multi page layout with basic conventions for navigation footer and brand logo seemed fit for presenting the music and live dates contact form.
The simpleness of the design also suited it to responsive design, nothing would need to be taken out to fit on smaller devices.
I kept with a minimal design, with striking images and minimal written content.

### Colours and Fonts

I wanted to keep the header, footer and background a monochrome darker grey and used http://coolors.co to match vivid contrasting colours for different sections. I used a plain white for the text and kept the same font throughout apart from one element of the footer. The simpleness and minimalness of the design seemed to match the general theme for Electronic music websites and I wanted to keep that feel.


### Navigation

I decided on fixed navigation to ensure that the nav links were always visible, making the site intuative to navigate. The footer was not fixed to allow as much content to be displayed without scrolling.

### Home page

I liked the idea of using a slideshow to introduce the website, The simpleness of the nav bar, brand logo, footer and striking images, that are also links.


### Music:

I chose to use embed music from Gellas Soundcloud page, It offered a clean interface with images and playlists which included remixes and Gellas own music. It is also a nice link to Gellas sound cloud page to explore his music further.


## How it was built

The main framework in building the Gella site was Bootstrap V4.1.3.
Icons for social media were from Font Awesome.
Fonts were from Google Fonts.

#### Plugins:

- https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css 

- https://code.jquery.com/jquery-3.3.1.slim.min.js 

- https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js

- https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js 

- https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css

- https://fonts.googleapis.com/css?family=Montserrat|Shadows+Into+Light

#### Resources:

- https://getbootstrap.com

- https://www.w3schools.com

- https://stackoverflow.com

- Stack overflow Forums

- https://coolors.co

#### Code/Framework Used Per Section

##### Navigation

- Bootstrap Navbar

##### Carousel 
- Bootstrap (with help from stackoverflow to fix responsiveness of pictures)

##### About section

- Bootstrap Grid system

##### Music
- iframes from soundcloud organised using Bootstrap grid system

##### Tour
- container with background image
- Basic bootstrap table

##### Contact

- Bootstrap form and grid system

##### Footer

- Bootstrap grid system.
- Font awesome for social links and Code institute for icon borders and code
- ASCII code for Copyright (thank you mentor!)

Fonts throughout courtesy of Google fonts
 - https://fonts.googleapis.com/css?family=Montserrat|Shadows+Into+Light

#### How it was tested

I primarily tested the site as it was built through google chrome and the google chrome devTools and used the chrome device toolbar for responsviness. 

I further tested it physically viewing it on mobile, tablet, mac and windows laptop, and different browsers (firefox, sSafari, Google Chrome, Explorer)

#### What was tested
- External links (to social media, particulalry music)

- Internal links from Nav bar and links from carusel pictures.

- Contact form for enquiries

- Container margins did not overflow, and each page started under the nav bar

- Grids filled its relevent section and moved responsivly.

- Checked images to ensure they were responsive and displayed appropriately on smaller screens.

- Ensure drop down menu and burger icon worked for navigation on smaller devices (needed to ensure JS script in head)

- Ensure content was straight forward, to the point and easy to read.

- Ensure soundcloud iframes were being responsive and displayed properly.

- HTML and CSS validation via w3.org.

### Issues encountered

The Carousel would distort / stretch images on smaller screens. After consulatation with Mentor and using forums I found that I had fixed the height of the picture in pixels. The solution was to re-do the images dimensions in an imaging editing program and set height to 100%, in this way they all remained the same size and reduced in proportion for smaller devises.

To make the site more minimal I originally intened the navigation menu to slide out from the right hand side when you hovered over a menu button. I could not get this to stay in a fixed navigation bar and it was not responsive so favoured the static navigation menu.

### Deploying the website

- Website deployed on Github.

- Tested the final deployed version in similar way to the previous version. 
- Found that the footer wording seemed disjointed and so removed margin on offset column to put the two blocks of text on same row.
- The multiple selection box on the contact form is displayed in a 3d style in safari which does not match the flat style intended.



### Future plans

- To include video footage from a live gig, possibly in the carousel, to make a high impact landing page.

- To put headline information from each page in brief on the home page.

- More information button on Carousel, rather than using whole image as link


# Credits

### Content
Gella provided information on his music workflow for the about section
### Media
The photos used in this site were obtained from Gellas facebook page with his permission.

Music was gained through Gellas soundcloud page with permission
### Acknowledgements

I received inspiration for this project from 
- Gella himself 
- Other drum and bass websites 
- Fellow students work on the Code institute course (via Slack)
- Previous learning from the code institue
- My mentor, Antonija Šimić



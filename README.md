# <center>Akrágas Website</center>

For over two thousand years the city of Akrágas, now known as Agrigento or The Valley of Temples, has **astounded visitors**.<br>
And yet many people are still unaware of its existence.

The Akrágas webite seeks to introduce Akrágas to a wider audience.
Using evocative, representative images and video; interesting facts, quotes and historical context, as well a direct link to booking site - this website will connect people to the place <br>

As someone with ties to the ancient city *(my grandafather and our ancestors are from the area)* I am passionate about sharing this remarkable location with the world and hope that Akrágas, Agrigento and the island of Sicily can enjoy increased and ongoing interest from tourists, historians and adventure seekers alike.

***

## UX (User Experience)

- ### User Stories
- #### First Time Visitor Goals
    - a. As a First Time Visitor, I want to easily understand the content and subject matter of the website.
    - b. As a First Time Visitor, I want to be able to easily navigate the site to see content and subject matter.
    - c. As a First Time Visitor, I want to see visual examples of the subject matter.
    - d. As a First Time Visitor, I want to read interesting and pertinent quotes and facts which help explain why the subject matter is remarkable.
    - e. As a First Time Visitor, I want to learn how I might be able to visit the place in person.
    - d. As a First Time Visitor, I want to see Social Media links to see further (real-time) information and content.


- #### Returning Visitor Goals
    - a. As a Returning Time Visitor, I want to easily understand the content and subject matter of the website.
    - b. As a Returning Time Visitor, I want to have the ability to ask questions directly of the website owners.
    - c. As a Returning Time Visitor, I want to understand that the content matter stretches back thousands of years from the original city, Akrágas, to moderns-day Agrigento and The Valley of the Temples.
    - d. As a Returning Time Visitor, I want to discover other similar locations through footer links (Unesco).

- #### Frequent User Goals
    - a. As a Frequent User, I want to be able to refer others to the site.
    - b. As a Frequent User, I want to see if there are any updates regarding ongoing archaelogical investigations.

- ### Design
    - #### Colours
        - Shades of red to echo Sicilian identity (flag), but using duskier tones
        - A complimentary light dusky blue to emulate sky and sea
        - White and bright red for contrast and important sections (About) and well as UX (Buttons)
        - I am pleased with this revised colour scheme as I feel it pays homage to traditional tones yet makes a feature of the bright red which expresses the vitality that this ancient site still holds to this day

    - #### Typography
        - Typefaces used are Lexend Peta for titles/headers and Open Sans for body text with Sans Serif as the fallback if fonts aren't imported correctly.

    - #### Imagery
        - Imagery will be vitally important for conveying the scale and scope of this archaelogical site. Video will be further uesful in showing how Akgrágas was believed to look when the ancient coty was flourishing.

- #### Wireframes
    - #### Desktop Wireframe [view](https://github.com/charliekranz/Akragas/blob/master/assets/wireframes/Akragas-Wireframe-diagram-v1.pdf)<br>
    - #### Mobile Wireframe  [view](https://github.com/charliekranz/Akragas/blob/master/assets/wireframes/Akragas-Mobile-wireframe.pdf)<br>


## Features

- ### Header Section - allows user to see site identity and concept via iconography. (Will hide icon on mobiles)
    
- ### Navigation Section - allows user to navigate to different sections / features

- ### Hero-Home Section - captures user's attention and conveys subject matter using compelling images and quote

- ### About Section - shows user the 3d model recreation video, conveys a summary of topic and includes another interesting quote

- ### Timeline Section - allows user to see an overview of important evenrs relating to topic

- ### The Temples Section - allows users to see an overview of Temples and breakdown of each

- ### Gallery Section - allows users to see a selection of images

- ### Visit Section - allows user to see location on Google map and click-link to Booking website

- ### Contact Section - allows users to send message and/or visit social media accounts

- ### Footer Section - a secondary navigation section. (may look at adding links to associated websites like UNESCO)

- ### Responsivity - Responsive across devices

## Development history

### Midway point - 18/9 <br>
I am quite pleased at how the website is shaping-up. 
Creating the mock-up ahead of development was hugely helpful as it meant some of the vital critical thinking was done early in the process.
I still had some hang-ups with logic around rows and cols and expect I will continue to sort that code a bit further.
I was delighted at the ability to target and style elements and used the Developed Tools often to test first.
<br>
Some of the changes I made to the initial plan include the colour palette and header icon. 
I felt the yellow, although indicative of the Sicilian flag, didn't sit as nicely in the design.
I used colour palette resources on Adobe and Paletteon website to look at more harmonious palettes.
I didn't pursue designing a header icon because I was happy at how the font awesome icon looked and knew I would repeat it throughout the site.
As well I liked the Google font being used and fet that this was strong on it's own (for mobile devices)
<br>
After speaking with Ignatius, who is mentoring me, I will focus on some restyling, using semantic code and clear annotation of code attribution.
There are one or two features such as relocating the social icons on smaller devices and possible using captions on image gallery (when clicked).

## Debugging
- Need to address: baguetteBox.min.js:7 Uncaught (in promise) TypeError: Failed to execute 'exitFullscreen' on 'Document': Document not active. 
Appears to be a known error: https://github.com/feimosi/baguetteBox.js/issues/212. May replace gallery entirely with fancybox option. Fixed by replacing with fancybox
- Surface Duo not seeming to conform to pixel size breakpoint of embed video box - Fixed with CSS restyling
- favico wasn't appearing. Got fic from <https://stackoverflow.com/questions/46163065/github-pages-website-favicon-not-showing>

## Technologies Used

***

## Testing

***

## Deployment

This was deployed on GitHub Pages and can be viewed at: <a href="https://charliekranz.github.io/Akragas/" target="_blank">https://charliekranz.github.io/Akragas/</a>

- ### Before my mid-point meeting with Ignatius, I deployed the website by:
- Selecting the repository in GitHub account
- Clicked on Settings 
- In GitHub Pages section, selected Master Branch as source
- Clicked Save 
- Shared the url of the published site


***

## Credits

#### README

- <https://github.com/Code-Institute-Solutions/readme-template/blob/master/README.md>
- <https://www.markdownguide.org/basic-syntax/>

#### Bootstrap

- <https://getbootstrap.com/docs/4.4/layout/grid/>
- <https://css-tricks.com/snippets/css/a-guide-to-flexbox/#flexbox-background>
- <https://hackerthemes.com/bootstrap-cheatsheet/>

#### Google Fonts

- <https://www.gyanblog.com/gyan/how-to-use-google-fonts-website-bootstrap/>

#### Colours
- <https://paletton.com/>

#### Hints 
I relied on Bootstrap Documentation, past Code Institute lessons and project code and W3 Schools threads for Hints
Some examples:
- Centering the embedded video <https://stackoverflow.com/questions/22433616/how-can-i-align-youtube-embedded-video-in-the-center-in-bootstrap/22433845>


#### Additional Code Used

Favicon
- <https://favicon.io/favicon-converter/>

Slider Comparion
- <https://www.w3schools.com/howto/howto_js_image_comparison.asp>

Hover css
- <https://ianlunn.github.io/Hover/#effects>

Gallery Template 
- <https://tutorialzine.com/2018/03/3-amazing-bootstrap-4-gallery-templates>
- <http://fancyapps.com/fancybox/3/>

HR line
- <https://stackoverflow.com/questions/41411155/does-bootstrap-4-have-a-built-in-horizontal-divider>



#### Content, Text and Images

- <https://www.brown.edu/Departments/Joukowsky_Institute/courses/greekpast/4770>
- <http://www.perseus.tufts.edu/hopper/artifact?name=Akragas&object=site>
- <https://www.ancient.eu/agrigento/>
- <https://www.parcovalledeitempli.it/en/>
- <https://www.wikiwand.com/en/Valle_dei_Templi>
- <https://www.petersommer.com/blog/archaeology-history/goethe-in-sicily#:~:text=The%20%22Temple%20of%20Concordia%22%20at,preserved%20examples%20of%20its%20kind.>
- <https://www.wildwinds.com/coins/greece/sicily/akragas/i.html>
- <http://thewanderingscot.com/photos/2014%20Tunisia-Sicily-Malta/Sicily/midis/IMG_4461.jpg>
- Sicily and Its Islands - A complete guide. Uga La Rosa, Editor




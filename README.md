# H1 Saplings Care Guide
[link]()
---

This website was created as a guide for new plant-parents, or for those who are looking at getting into plant care. This website was created purely for educational purposes. 

# H2 Business/Social Goals: 

* To help beginners choose their first plant by automatically filtering out hard-to-look-after plants and providing them with options based on ease of care and flexibility in the environment they are to be cared for. 
* To re-assure people that plant care is not as hard as it looks, nor is it time-consuming and encourage them to take it up.
* Provide reach and build credibility for the author as a reliable and experienced source. 
* Help local plant shops and earn a small commission from links. 

# H2 UX goals:

Home/Introduction Page: 
* As a first-time visitor, I may be already intimidated by the idea of plant-care, and want to visit a website that is
 easy to navigate, 
 easy to understand, 
 and attractive (and complies with a set colour scheme that adheres to a plant theme). 
* As a first-time visitor, I want to be encouraged and inspired by the content on the website to buy my first plant (not necessarily from the links provided in the plant cards). 
* As a recurring visitor, I want to feel confident in that the information provided is from a reliable source. 

Care/Problems Page: 
* As a first-time visitor, I want to find quick and concise guidance on problems I encounter as a first time plant parent. 
* As a first-time visitor, I want to know what is causing the problem and know how to avoid it. 
* As a recurring visitor, I want to be able to recognise common denominators in plant problems and be able to avoid them as best practice. 
* As a recurring visitor, I want to be able to send a message in case I have a problem that is not listed and be assured that my message has reached the author. 

# H1 Structure
---
This website is composed of three separate pages, to break up the guide into digestible and easy-to-understand chunks.

The structure of the website sections is as follows: 

1. Home/Introduction Page
    * Navigation
    * Header with Title
    * Introduction to the author
    *Easy to care for plant cards with flip-on-hover functionality. These provide a short and concise intro to the plant and why they are beginner-friendly. 
    * Footer
2. Care/Problem Page
    * Navigation
    * Brief Introduction and Reassurance section on common problems plant-parents encounter. 
    * Problem cards with slide functionality. 
    First card talks about the problem. 
    Second card shows an image of the problem so users who mightn't know what the issue is can compare their plant visually. 
    Third card is a short and concise guide on ridding the problem.
    * Footer
3. Contact Page
    * Navigation
    * Contact Form
    * Footer

The navigation and footer are common across all pages, interlinking the pages and to social platforms, like github, linkedin, and instagram. 

The information is kept mostly graphical (images, icons), so that the websites is easy to understand and comparisons can be made visually. The website is designed to mitigate text information overload. 

The final page is a simple message form where users can submit any questions or queries to the author. 

# H1 Scope of Website
---
The scope of the website is as follows: 

1. Header bar with navigation and logo. The navigation bar navigates to three different pages. 
2. An introduction band with an image and a heading for each page (unless the content is completely self-explanatory, as on the contact page). 
3. An introduction paragraph and image on the home and care pages. 
4. An image band with dynamic cards that display photos and information on:hover. 
5. Links to local locations in Ireland where these plants may be purchased, and links where relevant to commercial products that can help with certain problems beginners may encounter. 
6. A message form where users can submit their queries. 
7. Links to social medias (in this case personal, but if the website was an actual blog, these would be affiliated plant accounts). 

# H1 Strategy
In order to come up with the most appropriate structure for the website, I needed to define certain factors like audience, key information, and common things users will look out for in guides on plants. 

Target Audience: 

* Beginner/ intermediate plant-parents. 
* Age category: 16+
* People with sick plants. 
* People with an interest in houseplants. 

Considerations for these users: 

* Clear, short, and concise information on best plants to buy for beginners. 
* Desirable-looking photos. 
* Quick-fixes (care page)
* Contact form for any additional queries or concerns. 

This website is designed to be self-serviced, so that users can find information quickly and be able to use it as a guideline for plantcare. The contact form is there as a plan B and a fallback for any concerns outside of this website's scope. 

As most content is viewed on phonescreens nowadays, creating a mobile-first application is a key consideration for the website's design. 

# H1 Skeleton Frames
--- 
[link]()

Note: The website has deviated slightly from this design for better responsiveness and content positioning. 

The main idea was to keep as much of the content as possible visual, so that the user (especially the first time visitor) wouldn't feel overwhelmed with information. 

The header of the home page was changed slightly as I felt the visual appeal of the built product didn't reflect the same aesthetic value as what I imagined the wireframe to represent. As such, switching to the current header layout also allowed for a more fluid responsiveness and simplicity towards user experience.  

The cards on the home and care pages provide an engaging and light solution to balancing the ratio of visual:text information. They are placed under the intro sections so users know exactly what the cards are for. 

# H1 Aesthetics
1. Colour Palette
The colours chosen for this website were a selection of greens, dark grey and white. This was to mimick the colours of nature and tie the theme of the website to the object of focus (plants). While a shade of brown would seem like an appropriate alternative to dark grey, I felt like there wasn't enough contrast with the greens and whites, so opted for the darker option. 

2. Fonts
The _font-family_ for the website is : Arial. 

![Arial]()

I kept things simple, and opted for one font across the entire website. This was to ensure a coherent and simple theme throughout, with headings differentiated by _color_ and _font-weight_ in CSS. 

As Arial is a sans-serif font, it is considered significantly more legible than serif, narrow, or decorative fonts. For optimal user experience, creativity is added using the above CSS properties, while keeping the typeface itself recognisable and legible. 

Arial is a built-in CSS font, so nothing needed to be embedded/downloaded. 

Alternatives considered: Verdana, Helvetica. 

# H1 Features
---
1. Responsiveness
This website is fully responsive, designed with a mobile-first approach. 

2. Contrast
Text on any image background is given a color and opacity (either black or white, at 30-40% transparency). This gives the text a sufficient backdrop for legibility and contrast, while allowing the _background-image_ to seep through and create a more visually-appealing design. Text on a black background is given an off-white _color_, and text on a whte background is given a _color_ value of darkgrey (as set in the root colours in CSS), for improved legibility and contrast.  

# H3 Navbar
The navbar is consistent throughout the whole website, with a logo and three simple links to the other pages. On all screens over 550px (made larger as phone screens seem to be growing wider and wider these days), the navbar links are positioned in the middle of the screen, else in the far right corner with a set _margin_ value to offset it from the screen edge. 

# H3 About
The about section is on two pages (first blocks of paragraph text on the home and care pages). 

The home page block introduces the author with an image (courtesy of Unsplash), and a personal paragraph on the author. While the information generated in the block of text is a personal account, the image is of someone else as I am not photogenic in the slightest. 

The Care about paragraph (or intro) is there to reassure the visitor that encountering problems while caring for plants is completely normal, and not to worry if they come across something unusual. It then mentions the cards below and encourages users to go view them. 

Both of these sections are designed to be simple and to-the-point. 

# H3 Cards
The cards are key to the pages they are positioned on (home and care pages). 

On the home page, the cards provide an interactive way of introducing beginners and intermediates to possible plant options, while also hiding text from immediate view. The click me! navigation indicator gives a hint to the cards' fuctionalities, which may not be immediately obvious to users. The functionality here is a flip on:hover effect, with the image of the plant on the front, and text with a link on the back. 

On the care page, the structure of the cards is similar, but instead has three cards positioned one on top of the other, each of which (except the middle) slide in opposite directions to reveal all three. Depending on the screen size, these cards either slide out on the X-axis (if the screen is over 900px), or on the Y-axis (if it is smaller). This ensures all content is kept legible and visible at all times. Also, since phone content tends to be oriented long-side-vertically, this kind of design made more sense. While I had considered re-using the same functionality from the home-page cards, I needed to display information in a more concise and sectioned manner.  

# H3 Contact Form
This form is the object of focus on the third page. This is here for users to submit their queries and concerns to the author. It is strutured with basic user-side validation using relevant and correct input types and the _required_ attribute. I had considered using HTML pattern regex, but it seemed unnecessary as all of the validation was handled by in-built functionality. This was tested several times with different inputs. 

# H1 Technologies 
The website's responsive design was made possible using the following technologies: 

* HTML5 - used for structuring and content
* CSS3 - used for adding styles to the content for legibility and aesthetic appeal
* FontAwesome - used for icons 
* Firefox Developer Tools - used for debugging the website during production
* Lighthouse - An extension I used for testing the performance, accessibility, best practices and SEO of my site (result shown under debugging below). 
* GitHub - For code storage,version control and deployment
* Git - for  commiting through terminal and pushing to Github for storage. 
* VSC - The IDE I developed the project in.
* Balsamiq/Sketches - for a clear understanding of the structure I wanted my website to follow. 
* Grammarly - Because even as a native speaker, my English is all over the gaff. 
* Unicorn Revealer -  
* Tiny.png - for compressing my images (to improve performance of my website). 
* Color Contrast Accessibility Validator - check legibility of my text on different backgrounds for better accessibility. 
* W3C Markup Validation Service - to validate my HTML for potential errors. 
* W3C CSS Validation Service - to validate my CSS code. 
* Freeformatter CSS Beautify - to ensure I formatted my CSS correctly. 
* Freeformatter HTML Beautify - to ensure I formatted my HTML correctly. 
* AmIResponsive - to create the responsive image. 

# H1 Testing & DeBugging
---
# H3 Testing

* (As a first-time visitor, I may be already intimidated by the idea of plant-care, and want to visit a website that is
 easy to navigate, 
 easy to understand, 
 and attractive (and complies with a set colour scheme that adheres to a plant theme).)

Upon entering the website, the visitor is greeted with a minimalist header aesthetic - directing focus to the middle of the header where a reassuring heading - "complete care guide for beginners" - is placed. There is a simple mnavigation bar at the top of the page, which is immediately visible due to its contrasting background colour. 

* As a first-time visitor, I want to be encouraged and inspired by the content on the website to buy my first plant (not necessarily from the links provided in the plant cards). 

Further down the page, content is kept clean and concise, to make sure the visitor isn't distracted by anything unnecessary. The cards are made dynamic and interesting, following the volor scheme of the site and providing 1-2 quick sentences on why a specific plant is an ideal choice for a beginner or someone looking for something non-time-consuming. 

* As a recurring visitor, I want to feel confident in that the information provided is from a reliable source. 

The intro begins to build credibility to the author by introducing themselves, showing an image of them surrounded by plants, and mentioning growing up around houseplants. 

Care/Problems Page: 
* As a first-time visitor, I want to find quick and concise guidance on problems I encounter as a first time plant parent. 

The intro at the top of this page reassures users that experiencing difficulties in plant care is completely normal and not to worry, and then directs users further down the page to the cards. The cards near the bottom of the page are designed similarly to those on the home page, but required more information (thus the design change from flip to translate). 

* As a first-time visitor, I want to know what is causing the problem and know how to avoid it. 
The cards slide out with the first showing a heading describing the problem and the usual cause, the second an image of the problem (from Unsplash), and the third a 'quick fix' of the problem, written clearly and concisely. 

* As a recurring visitor, I want to be able to recognise common denominators in plant problems and be able to avoid them as best practice. 

This is where the icons come into place - as a first time visitor they may not be immediately recognisable (hence the text being at the top of the card), but as a recurring visitor who has likely looked through the cards simply for the dynamic layout, they may be able to quickly come to a conclusion on the possible cause simply from the icon. 

* As a recurring visitor, I want to be able to send a message in case I have a problem that is not listed and be assured that my message has reached the author. 

A contact button is provided at the bottom of the second page, and as a separate third page for any queries the user may have.

# H3 DeBugging

This is where tools like Lighthouse (extension), HTML and CSS validators, and simple responsiveness testing using the Firefox developer environment (CTRL + M) came into play. 

**image
While the scores from the Lighthouse report are quite decent, there was still room for improvement with regards to the overall performance of the website.

To work on this, I needed to: 
* reduce the size of my images using Tiny.png without losing out on quality - there was a potential savings of 658KiB. 
* explicitly use width and height attributes in my HTML for img instead of setting this using CSS - a classic example of just because my HTML and CSS validated as corrected, doesn't make it right or best practice. 
* serve static assets with an efficient cache policy - I wasn't entirely sure what this meant so had to research it and add it to the site. 
* ensure my links have discernible names for better accessibility - something I missed and added in later. 
* ensure my images are displayed with the correct aspect ratio as the original image. 

# H3 Known Bugs & Fixes 
I made sure to debug common and often missed bugs like links to socials and other websites. Everything was working correctly, but this is a good habit to have for common debugging. 

I also ran a contrast test using Color Contrast Accessibility Validator to see if my text and its backgrounds were legible. The results I received were a little confusing, as some of thr text was read on completely different background colours than what they are actually placed on, and as such I decided to disregard the score I got. (See image below from the validator and the actual site). 


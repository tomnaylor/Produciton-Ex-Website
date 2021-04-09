![ProductionEx logo](assets/images/productionex-header-logo.png)

# **ProductionEx**


![Capture](assets/readme/responsive-capture.JPG)

**View live site:** https://tomnaylor.github.io/codeinstitute-ms1/


Welcome to ProductionEx, a production software package for Festivals, Theatres and other complex events. We are a leading standard in managing production information for a range of events, from Glastonbury festival to the stage production of mirror cracked. We collate, validate and deliver timely information, and automate many tasks backstage production tasks.  

For my MS1, I wanted to create a front-end sales website for a web app I designed for a festival my employer host bi-annually. The website is aimed as a sales tool to provide details, exmaples, prices and user stories to the potential client before they get in touch to enquire about their specific needs.


## Table of contents
* [UX](#ux)
    * [User Stories](#user-stories)
    * [Site Owners Goals](#site-owners-goals)
    * [Design](#design)
        * [Original sketch](#original-sketch)
        * [Wireframes](#wireframes)
        * [Fonts](#font-family)
        * [Icons](#icons)
        * [Colours](#colours)
        * [Hero image](#hero-image)
* [Features](#features)
    * [Existing Features](#existing-features)
        * [Navigation](#navigation)
        * [Hero Image](#hero-image)
        * [Sign up buttons](#sign-up-buttons)
        * [Sign up modal](#sign-up-modal)
        * [Features Section](#features-section)
        * [Success stories](#success-stories)
        * [Pricing](#pricing)
        * [Guides](#guides)
        * [Contact Us](#contact-us)
        * [Footer](#footer)

## UX

### User Stories
As a user…
* I want to hear feedback from current users of the software
* I want to find examples of prices for a similar size event
* I want to try a demo before I agree to buy
* I want a quick way to sign up
* I want to view some how-to videos / guides
* I want to easily get in touch if I have any questions
* I want to know how resilient the software is and how it works on a green-field festival site
* I want to feel assured that the software will be supported for years to come
* I want the website to work flawlessly, as proof of the software itself

### Site Owners Goals
* Sales website to promote a theatre and festival production software application
* Website should work across mobile, tablet and desktop
* Professional and confident design
* Pages to include use cases, example prices, demos and guides for existing users
* Call to action for sign up in multiple places
* Demo request and contact details should be visible and easy to find
* Provide testimonials from other clients (look up b2b notes)
* Provide comprehensive how-to videos and written guides
* Promote the product as the industry standard
* Provide a professional and flawless UX to promote confidance in the software itself.


### Design

#### Original sketch
I drew an outline sketch first to get a basic feel of a design. 
![Concepts sketch](assets/readme/concepts-sketch.jpg)

#### Wireframes
After the initial sketch, I then moved to Balsamic and created a wireframe for the three responsive sizes (desktop, tablet and mobile). You can [view the PDF wireframe here](assets/readme/wireframe-index.pdf)

#### Font family
To provide a reliable and fast font library, I have used [Google Fonts](https://fonts.google.com/ "Google Fonts"), picking two complimentary fonts.

For headings and words I want to stand out I've used the [Lato](https://fonts.google.com/specimen/Lato?preview.text=ProductionEx&preview.text_type=custom "Google fonts: Lato") font. 

For the remaining text I chose the [Raleway](https://fonts.google.com/specimen/Raleway?preview.text=ProductionEx&preview.text_type=custom "Google fonts: Raleway") font.

#### Icons
To add a more familiar feel to the website, I have added icons to sit alongside (and sometimes instead of) text links and buttons. I choose the [Font Awesome library](https://fontawesome.com/ "Font Awesome"). 

#### Colours
![Accent](https://via.placeholder.com/100/F9440D/fff?text=F9440D)
![Accent light](https://via.placeholder.com/100/ff7755/fff?text=ff7755)
![Light](https://via.placeholder.com/100/f7f6e7/fff?text=f7f6e7)

#### Hero image
I used the website **unsplash** to find an image that would work as the hero background.

![Hero image](https://images.unsplash.com/photo-1470229722913-7c0e2dbbafd3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1950&q=80)
https://unsplash.com/photos/NYrVisodQ2M


## Features

### Existing Features

#### Navigation
I have tried to make a intuative, accessable and reactive navigation bar that stays useful across different screen sizes and devices. For desktop the navigation has at its centre the logo which also acts as the home link. On Table the logo hides to leave space for the actual links, and on mobile the entire menu is hidden and a hamburger icon provides a button to toggle the menu on and off.

#### Hero Image
I have used a hero image that spans the width of the viewport and 80% of the height. It includes a curved bottom and also hosts the h1 heading, tag line and a call to action button. The image URL changes as the screen size reduces to make downloading the image quicker on mobile and tablet devices.

#### Sign up buttons
The sign up buttons are see throught the site as the main call to action (and the end goal for the website). The buttons and text link in the footer all trigger the sign up form modal and use javascript to add / remove a class to hide the form when not needed.

#### Sign up modal
This is designed to sit on top of the page when the user clicks on the sign up buttons seen across the site. There is a semi-transparent background that covers the site behind the modal itself. The form has some elements that are required and some that are not. There are text, date, phone, email and textarea inputs. Required fields also have a small asterix to highlight they are needed. Simple html form validation is also used for required inputs.

#### Features Section
The features section is designed to give a quick outline of some of the capabilities of the software. I split them up into 3 common headings for the industry and include a short description for how the software can improve each area. On smaller screens these stack under each other to maintain their width. On mobile they change to 80% fixed width.

#### Success stories
The client logos share the same size as the feature cards above. However these boxes have a fixed height and a logo as the background (as a transparent PNG). When you hover over each logo you get a description of the client relationship, what they use the software for and a review from the client themselves. Javascript was used to create the mouseover effect.

#### Pricing
The pricing boxes again share the same size as the above but like the features section they arn't fixed heights. They include an increasing battery icon to convay the scope of the requirements, an example price and an example description of the type of event that would need that degree of administration.

#### Guides
Guides work in two ways. As a prospective client they show off the software and how easy it is to use. Additionaly, as a current user it keeps them visiting the website for helpful tips and guides on new features or as training for new staff on how to use the system.

#### Contact Us
I wanted to have a contact section at the bottom of the page as a means to get quick correspondance from the visitor with the aim to push sales. The form is delibratley simple with only a few fields to make sure there are few barriors to asking about the software.

#### Footer
The footer provides a "most recent" list of news / guides / papers etc to highlight whats new on the system. It also provides a sitemap with other links (aka. terms etc.) that arn't important to put on the main site navigation. There is also a contacts section with international phone numbers, email and social links across various platforms.

### Features left to implement
* White papers and blog posts that backup knowledge of the sector
* Interviews with users on location to prove real-world reliability
* Automated tool to calculate price based on a selection of features
* Feature to dynamically highlight where you are on the page by altering the class of the respective link and stick main nav to the top of the viewport.


## Technologies used

### Languages
* HTML
    * HTML is used as the markup language in a single index.html file
* CSS
    * A single CSS file style.css is used for all screen sizes which also imports the font and icon Libraries
* Javascript
    * The project uses a small amount of javascript to toggle the mobile navigation and the provide the pop-up sign up form and client testimonials.

### Libraries
* Google Fonts (Lato and Raleway)
* FontAwesome (for icons and brand logos)

### Tools
* GitHub
* GitPod
* W3C HTML and CSS validators
* Google Lighthouse
* Balsamic (Wireframe)
* Concepts (Initial drawing)


## Testing

### Manual Testing
I have preformed manual tests on a number of browsers and devices to cover most scenarious and feel assured the website works as intended for all visitors. This included using google dev tools to simulate different screen sizes and using a real android and apple phone.

#### Navigation menu
I want the navigation items to have a margin around them so they stand apart; the internal links to scroll smoothly to the corresponding section; and on mobile the menu to slide out of view behing a hanburger icon.

I tested the navigation on mobile with chrome and safari and on desktop with chrome, edge and firefox, also using the browsers developer tools. The navigation in desktop and mobile views worked across all the devices although the scroll speed seems to differ slightly.

#### Current user testimonials
I wanted to give feedback and information on current clients but not take up too much space on scree. For this reason I choose to use a popup when the user hovered over the clients logo. To do this I first tried a mouseover javascript trigger. When tested the popup text toggled on and off everytime the mouse moved. The intended outcome was for the text to appear when you entered the logo box and hide again once you've left the text description.

To achieve this I used a mouseenter event to open it and a mouse leave to close the popup. This worked, but only on the first client. I used [this advice](https://stackoverflow.com/questions/50793136/javascript-click-function-only-works-on-first-element) to adapt the code to work for each client.

#### Sign up and contact forms
The UX of the form was tested across the devices above, which included the styling of the placeholder text and the position of the lable relative to the input element. All browsers and devices rendered the form in the expected way.

Both forms were tested across the browsers and devices:

* Required inputs were left empty to check if the form could be submitted.
* Email, phone and date inputs were tested with invalid entries.
* Valid form submitted to check the method and action are correct.

All form imputs worked as expected, the form did not submit when required inputs were empty, but the phone input allowed any character. I used the regex pattern option taken from [this site](https://martinwolf.org/before-2018/blog/2015/04/html5-telephone-input-validation/) to validate the input.


### Discovered Bugs

* **Sign up button**
  * Sign-up button would move below hero image and disapeer behind the main section in mobile devices.
  * To fix the issue I changed the position to use bottom and not top to ensure that whatever the height of the hero image, the CTA stayed 100px from the bottom.

* **Hover client logo**
  * The popup description would open and close quickly as the mouse moved over the client logo container.
  * Changed onmouseover to two seperate calls to mouseenter and mouseleave so the javascript function wasn't trigged on every mouse move.

* **Multiple client logos**
  * The popup description would only open on the first container.
  * With help from [Mamun](https://stackoverflow.com/users/7461381/mamun) in [this post](https://stackoverflow.com/questions/50793136/javascript-click-function-only-works-on-first-element) I altered the javascript to loop thru each matching query.

* **Main nav items**
  * When the screen size reduced to circa. 750px, the top navigation links crashed into each other
  * In the tablet only CSS I removed the centre logo to give the menu items more space

* **Mobile home link**
  * When in mobile view the home logo is removed for space. This was the  link back to the top of the index page. This stopped the user from being able to navigate easily.
  * I added a mobile only home link at the top of the navigation ul list.

* **Videos slowed page loads**
  * Adding the video guides reduced the lighthouse score as each video (x3) preloaded.
  * I added the preload="none" to each video and then to make them visually appealing, I added a poster image to show before playing the media.

* **Sign-up modal**
  * On mobile devices with small height screens the fixed position modal wasn't able to be scrolled. This ment that most of the form inputs were not accessable
  * Changed the height to 100% and removed the bottom and right css entries to allow the box to expand to show all the contents.

* **Transitions**
  * All transitions happened on page load (which started from the non styled state)
  * This seems to be a bug with the chrome browser. I used advice on [this page](https://github.com/LeaVerou/prefixfree/issues/99) and added an empty script tag at the bottom of the body. This seems to have stopped the issue for me.

* **favicon** 
    * Developer tools report a 404 file missing for favicon.ico I hav't yet implemented an icon for the site.

* **Phone number format**
    * The form input for phone number allowed any text entry.
    * I used a regex pattern taken from [this page](https://martinwolf.org/before-2018/blog/2015/04/html5-telephone-input-validation/) to validate the input

## Deployment
The final website has been deployed to github via their pages option. Written in gitpod, after each commit and push, the master branch on github was updated with the local commit. My normal workflow would include
* git pull if not working with the most up-to-date fields
* git commit with a useful comment
* git push to sync with github  

The URL for the github page is https://tomnaylor.github.io/codeinstitute-ms1/

### Running a local copy
If you would like to run a local copy of this website, you would simply need to clone the master git repo. There are no servers to configure, the website uses only HTML, CSS and Javascript.


## Credits

### Content

* Javascript help with looping thru elements from [stackoverflow](https://stackoverflow.com/questions/50793136/javascript-click-function-only-works-on-first-element)
* Javascript to stop mouseover toggling the client text from [stackoverflow](https://stackoverflow.com/questions/43379883/onmouseover-eventlistener-onto-all-children)
* How to target a class or ID using javascript written by [Melanie Phillips](https://medium.com/@melaniecp), found [in this article](https://medium.com/@melaniecp/how-to-target-an-html-class-or-id-with-javascript-1f360a4a0310)
* Telephone validation pattern taken from [Martin Wolf](https://martinwolf.org/) on their [blog post](https://martinwolf.org/before-2018/blog/2015/04/html5-telephone-input-validation/)   
* Help with a screen reader class from [webaim](https://webaim.org/techniques/css/invisiblecontent/)
* CSS to shake the CTA button, help from [Sarah Drasner](https://css-tricks.com/author/sdrasner/) from css-tricks [here](https://css-tricks.com/snippets/css/shake-css-keyframe-animation/)

### Media

* Hero image was taken by [Yvette de Wit](https://unsplash.com/@yvettedewit) seen [here](https://unsplash.com/photos/NYrVisodQ2M)

### Acknowledgements

The inspiration behind this website was based on work i've done in the past. Currently I work in theatre, and while we might be currently dark, it is an insiring sector to work in. I'd like to build software that takes advantage of what I know and would very much like to release a project like this in the future.

I'd like to thank my mentor [Caleb Mbakwe](https://github.com/caleboau2012), who really helped define the project goals and helped put myself in both the user and the owners shoes. After each session I would have a list of topics to look at or suggestions for changes.

I would also like to thank the Slack community and CyC group for helping the course feel less "remote" and my partner that has needed to do ever more work around me.
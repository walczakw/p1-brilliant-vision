# Brilliant Vision


## Introduction

The “Brilliant Vision” is a small business website of a local opticians in Killarney, Ireland. 
The site targets anyone needing opticians services and provides essential information for potential customers such as a list of services offered, the appointment booking form, location of the store with its opening hours and a google map. It also contains a ‘Gallery’ page showcasing glasses and sunglasses.

[View the live project here](https://walczakw.github.io/p1-brilliant-vision/)

![Responsive Mockup](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/responsive-mockup.png)


## Index

1. [**Introduction**](#introduction)
2. [**UX**](#UX)
    * [***Site Objectives***](#site-objectives)
    * [***User stories and Project board***](#user-stories-and-project-board)
    * [***Wireframes***](#wireframes)
    * [***Color palette choice and Accessibility***](#color-palette-choice-and-accessibility)
3. [**Features**](#features)
    * [***Existing Features***](#existing-features)
    * [***Features Left to Implement and Possible Improvements***](#features-left-to-implement-and-possible-improvements)
4. [**Testing**](#testing)
    * [***Validator Testing***](#validator-testing)
    * [***Testing Responsiveness***](#testing-responsiveness)
5. [**Deployment**](#deployment)
6. [**Credits**](#credits)
    * [***Content***](#content)
    * [***Media***](#media)
    * [***General Reference***](#general-reference)
    * [***Acknowledgements***](#acknowledgements)

     
## UX

### Site Objectives 
The following information was gathered to find common goals and then to form the site requirements.

#### Main external user's goals
- To find information about services offered.
- To find information about location, phone number, email and opening hours.
- To find information about how to book an appointment.

#### Main site owner's goals
- To provide location information together with a google map to help potential customers with finding the store more easily.
- To provide a way of booking an appointment for the customers.
- To provide a way of sending online queries for the customers.
- To show examples of glasses and sunglasses offered in the form of 'Gallery' page.
- To provide all site elements in an accessible way, especially for people with visual impairments.

### User stories and Project board
- The site requirements were put into user stories. [Link](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/user-stories/USER-STORIES.md) to a separate document listing all user stories.
- The user stories were then converted into issues for development. The Github Project was created to manage the issues. Any bugs found during the development process that were not fixed immediately were also added to the board. [Link to Project's board](https://github.com/walczakw/p1-brilliant-vision/projects/1)
  - Four columns were added to the Project's board: 'To do', 'In progress', 'Testing' and 'Done'.
  - A label was assigned to each issue for easier identification on a board.
  - Once the issue was developed and tested it went to a 'Done' column and status changed to 'closed'.

### Wireframes
The wireframes were created using the [Balsamiq](https://balsamiq.com/) tool. 
[Link](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/wireframes/wireframes.pdf) to all wireframes in .pdf format.
- Firstly, the basic concept was added to display the site on mobile devices (phones and tablets). The goal was to show the layout of each element on the site. [Link to wireframe](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/wireframes/wireframe-mobile-and-tablet.png)
- Secondly, a separate wireframe was added to show how images on the 'Gallery' page will be displayed on bigger screens (e.g. tablets). [Link to wireframe](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/wireframes/wireframe-gallery-page-tablet.png)
- Lastly, the wireframes for the desktop were added together with more details such as potential color choice or sample images. These wireframes also include additional pages: 'Query form', 'Thank you' and '404 error'. [Link to wireframe](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/wireframes/wireframe-desktop.png)
- During the development stage, some changes were made to the initial concept. Main changes:
  - The decision has been made to put sections of the website into separate pages rather than to have a one scrollable page. This was to reduce the number of nav bar menu items by one so that there would be more space on smaller screens. This would not be necessary if a 'hamburger' type of menu was planned.
  - The landing page ('Hero' section) now has a background image visible at 100% screen width and 85% view height. This change was applied after receiving feedback from a test user who looked at the wireframes and suggested it for a more "professional" look.

### Color palette choice and Accessibility
- When choosing the color pallete, Accessibility  played a big role. The colors had to be visible to people with different visual impairments as much as possible. 
- The color 'red' was picked as the main color and then the right shade of 'red' has been chosen to correspond well with the main 'Hero' image and company's logo. The [Adobe Color](https://color.adobe.com/create/image) 'extract theme' tool was used.
- Then, colors for main text, background colors and links were picked to match the site's design and also to be WCAG 2.0 compliant at the same time. 
- Each color was checked using different contrast checking tools, e.g. [WebAIM](https://webaim.org/resources/contrastchecker/)
- The [Contrast Grid](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%23012340%0D%0A%23A62639%0D%0A%23FFFFFF%0D%0A%23E8E9ED%0D%0A%23004C8F%0D%0A%0D%0A%0D%0A%0D%0A&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa) was also generated to only show AAA compliant color combinations.
- These are the final colors for the Brilliant Vision site:

![Color Contrast Grid](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/validators-screenshots/contrast-grid-wcag.png)


## Features 

### Existing Features

- __Header with Navigation__

  - Featured on all pages, the fully responsive, fixed header includes links to the Home, Gallery, Location and Contact pages and is identical in each page to allow for easy navigation.
  - The logo is also clickable and brings the user to the Home page.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Header](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/header.png)


- __The landing page image__

  - The landing includes an image with text overlay to allow the user to see the company's name, purpose and overall location. 
  - This section also includes a 'Book your appointment' button for a quick access to the booking form which brings value to users wanting to quickly access this feature.

![Hero](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/hero.png)


- __Services section__

  - The Services section allows the user to see an overview of services offered together with images for visual representation for some of the services.
  -  This section will help users decide if the business provides services needed.

![Services](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/services.png)


- __The Footer__ 

  - The footer section includes the phone number for the Brilliant Vision.
  - The footer section also includes links to the relevant social media sites for the Brilliant Vision. The links will open in a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media.

![Footer](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/footer.png)


- __Gallery__

  - The Gallery page displays a selection of images of glasses and sunglasses to catch the user's attention.
  - This section is valuable to the user as they will be able to see the latest offer.

![Gallery](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/gallery.png)


- __Location Page__

  - The Location page displays business address, phone number, email, opening times and a google map.
  - This section will benefit users who want to quickly check where the Brilliant Vision is located and what the latest business hours or contact details are.

![Location](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/location.png)


- __Contact Page__

  - The Contact page consists of a form.
  - This section will benefit users who want to send general query or make an appointment. There is an option to pick a preferred time of the day as well.
  - Please note that the data sent through the form are not currently saved anywhere. There is no database connected. However, This can be developed in the future.

![Contact](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/contact.png)


- __Thank You Page__

  - The Thank You page provides a confirmation for the users after they have sent a form through the Contact page.
  - This section will benefit users by providing affirmation that the form has been sent successfully.
  - There is a button to allow users to go back to the Home page

![Thank You](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/thank-you.png)


- __404 Page__

  - The 404 error page provides information to the users that the url they have entered cannot be found.
  - There is a button to allow users to go back to the Home page

![404](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/404.png)


### Features Left to Implement and Possible Improvements
- The header would benefit from having a hamburger style for menu items for mobile screens.
- The Contact form page could be connected to the database to save data entered and sent by the users.
- The calendar feature could be added so that users can pick exact time and day for the appointment and see the available times/days.
- The iframe for google map could be added using JavaScript as recommended by google. Currently, the WC3 html validator points to error due to the 'width 100%' applied to iframe. This was applied to make a map responsive. Unfortunately, using JavaScript was out of scope for this project at this time.
- The whole website could be one scrollable page.
- The Services section could be expanded so that each service is clickable. Users could see more information about each service.
- Two more sections could be added: 'About Us' and 'Testimonials' to the Home page.
- The tooltips could be added for the social media icons in the footer.
- The media queries section of the css file could be refactored to list media queries by screen size and not by sections. The screen sizes could be limited to only a few most common so that there are less breakpoints. 
The current implementation was done by adding media queries after finishing each section of the site. The better approach would perhaps be to test the site at the end and then find common breakpoints.


## Testing 

- All features developed (including user stories) were tested when in the 'Testing' column of the Project's board.
The same process was applied to the fixed bugs. [Link to Project's board](https://github.com/walczakw/p1-brilliant-vision/projects/1)
- The whole website with all its pages was also tested again after finishing the development.
- The following web browsers were used for testing:
  - Chrome (version 101.0.4951.67)
  - Firefox (version 100.0.2)
  - Edge (version 101.0.1210.53)
  - Opera (version 87.0.4390.25)

### Validator Testing 
The following validator tools were used. For detailed report with screenshots refer to a separate file [here](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/testing/VALIDATOR-TESTING.md)
- HTML:
  - [W3 validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fwalczakw.github.io%2Fp1-brilliant-vision%2Findex.html)
- CSS:
  - [Jigsaw validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fwalczakw.github.io%2Fp1-brilliant-vision%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- Accessibility:
  - [WAVE validator](https://wave.webaim.org/report#/https://walczakw.github.io/p1-brilliant-vision/index.html)
- Performance:
  - Lighthouse validator (Google Chrome Dev Tools)

### Testing Responsiveness 
- The website with all its pages was tested for responsiveness using Google Chrome Dev Tools and picking different screen widths and different mobile and tablet devices.
- The Brilliant Vision is fully responsive from the screen width 280px as a minimum (eg. Samsung Galaxy Fold)


## Deployment

The site was deployed to GitHub pages by following the steps below:
  1. In the GitHub repository, navigate to the Settings tab and then click on 'Pages' (from the menu on the left)
  2. From the source section drop-down menu, select the Main Branch and click 'Save'
  3. Once the site has been deployed, the link to it will be displayed with the information: "Your site is published at..."

The live link can be found here - https://walczakw.github.io/p1-brilliant-vision/

Alternatively, a local copy of this repository can be made by pasting the code below into a terminal:
  - `git clone https://github.com/walczakw/p1-brilliant-vision.git`


## Credits 

### Content 
- Text:
  - A research was done by checking 20+ different US based Opticians websites to find services offered. Then, nine most common services were picked for the 'Services' section of the Brilliant Vision home page.
  - The text for the 'Location' page features a fictional address and opening hours.
- Map:
  - The map for the 'Location' page was taken from [Google Maps](https://www.google.com/maps)
- The website mockup for the README was generated using [techsini.com](https://techsini.com/multi-mockup/)
- The favicon was generated using [realfavicongenerator.net](https://realfavicongenerator.net/) and then tested using [favicon checker](https://realfavicongenerator.net/favicon_checker?ignore_root_issues=true#.YomRT1SZNEa)
- The fonts used were imported from [Google Fonts](https://fonts.google.com/)
- The font pairings were found using [fontjoy.com](https://fontjoy.com/)

### Media
- The glasses icon for the Brilliant Vision logo and favicon was taken from [FREE SVG](https://freesvg.org/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- The images used for the 'Home' and 'Gallery' pages were taken from this open source sites: 
  - [Pexels](https://www.pexels.com/)
  - [Unsplash](https://unsplash.com/)
- Images were compressed using [TinyPNG](https://tinypng.com/)

### General Reference
- During development process the following websites were used for reference when additional information was needed:
  - HTML & CSS advice:
    - [MDN](https://developer.mozilla.org/en-US/)
    - [w3schools](https://www.w3schools.com/)
    - [CSS TRICKS](https://css-tricks.com/)
  - Creating accessible forms and general accessibility advice:
    - [w3.org](https://www.w3.org/WAI/tutorials/forms/)
    - [webaim](https://webaim.org/techniques/forms/controls)
  - Font size guidelines:
    - [learnui.design](https://learnui.design/blog/mobile-desktop-website-font-size-guidelines.html)
    - [material.io](https://material.io/design/typography/the-type-system.html#type-scale)
- The following README examples were read for an inspiration before writing README for Brilliant Vision:
  - ['Love Running' project](https://github.com/lucyrush/readme-love-running)
  - [David Bowers](https://github.com/dnlbowers/modern-buddhism)
  - [Matt B](https://github.com/MattBCoding/leinster-trophy)
  - [StevenWeir038](https://github.com/StevenWeir038/islandAQUAdesign)

### Acknowledgements
Special thank you to Code Institute mentor [Daisy Mc Girr](https://github.com/Daisy-McG) for providing feedback and improvement suggestions during development of this project.
